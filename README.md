## Synopsis

qpjson (Quick & Pretty JSON) is a simple Alfred v2 workflow for converting smooshed up JSON into beautiful, properly whitespaced JSON.

## Dependencies & Requirements

qpjson works with a Sublime Text plugin called Pretty JSON. The plugin works with both version 2 and version 3 of Sublime Text, and so does qpjson.
The plugin can be found here: https://packagecontrol.io/packages/Pretty%20JSON

If Alfred does not currently have Accessibility access through System Preferences, you will be prompted to allow Alfred to control your computer the first time you execute the workflow. This step is required for the workflow to function properly.

## Use

You can use qpjson with either hotkeys or keywords in Alfred. By default the hotkeys are ⇧^⌘J to prettify json that is selected, and ⌥⌘V to to prettify json that is in your clipboard. You can change these in the Workflow section of Alfred's preferences.

You can also open Alfred, type "json", and paste in your json data that you want beautified.

## Code Example

Here is some digusting JSON barf for you to experiment on.

`{"widget":{"debug":"on","window":{"title":"Sample Konfabulator Widget","name":"main_window","width":500,"height":500},"image":{"src":"Images/Sun.png","name":"sun1","hOffset":250,"vOffset":250,"alignment":"center"},"text":{"data":"Click Here","size":36,"style":"bold","name":"text1","hOffset":250,"vOffset":100,"alignment":"center","onMouseUp":"sun1.opacity = (sun1.opacity / 100) * 90;"}}}`