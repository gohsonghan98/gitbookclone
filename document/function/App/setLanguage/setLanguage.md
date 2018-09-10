# setLanguage

### Description

Set the default language of the app based on the languages setup in language settings.

### Flowchart

- N/A

### Input / Parameters

| No | Name | Description | Data Type | Required |
| ------ | ------ | ------ |------ | ------ |
| 1 | lang | Name of the language. | String | Yes | 


### Scenario / Use Case

The user override the default language (English) of their App.

### Step

1. Go to language setting tab add language "chinese", add label "Language" and assign chinese word for the label as below:

    ![](setLanguage-step-1.png?raw=true)
    
2. Draw a Label with "Language" Caption, a button "setLanguage"

    ![](setLanguage-step-2.png?raw=true)
    
3. Call the function

    ![](setLanguage-step-3.png?raw=true)
    
4. Reload

    ![](setLanguage-step-4.png?raw=true)


### Result

The word "Language" will be changed to "语言选择". <br />

![Flowchart](setLanguage-result-1.png?raw=true)

### Video

- N/A
<!--[![Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/StTqXEQ2l-Y?t=35s)-->

### Notes

- In the language setting, the word used for mapping is case sensitive.