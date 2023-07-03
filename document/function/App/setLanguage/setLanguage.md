# setLanguage

## Description

Set a default language for the app from the pre-defined languages in language settings.

## Input / Parameter

| Name | Description | Input Type | Default | Options | Required |
| ------ | ------ | ------ | ------ | ------ | ------ |
| lang | The name of the language to be set as default. | String | - | - | Yes |

## Output

### Default Output

| Description | Output Type |
| ------ | ------ |
| The new language that has been set. | String |

## Video

Coming Soon.

## Example

The user wants to change the default language (English) of their App.

### Steps

1. Go to language setting tab add language "chinese", add label "Language" and assign chinese word for the label as below:

    ![](../../../../document/function/App/setLanguage/setLanguage-step-1.png?raw=true)
    
2. Draw a Label with "Language" Caption, a button "setLanguage"

    ![](../../../../document/function/App/setLanguage/setLanguage-step-2.png?raw=true)
    
3. Call the function

    ![](../../../../document/function/App/setLanguage/setLanguage-step-3.png?raw=true)
    
4. Reload

    ![](../../../../document/function/App/setLanguage/setLanguage-step-4.png?raw=true)

### Result

The word "Language" will be changed to "语言选择". <br />

![](../../../../document/function/App/setLanguage/setLanguage-result-1.png?raw=true)

## Links