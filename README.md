# Native Emoji Picker

#### Modified version of [Meteor-Emoji-Picker](https://github.com/CreateMarketing/Meteor-Emoji-Picker)

> This emoji picker is pure, vanilla JavaScript, so should be compatible with most JS projects. 

Demo: https://native-emoji-picker.netlify.com

## How do I use it?

This plugin can be installed via NPM:

```
npm install https://github.com/dshemendiuk/native-emoji-picker.git
```


Include the meteorEmoji.min.js file from the 'dist' folder in your project, and then use:

```js
new MeteorEmoji();
```

Now you can add emoji pickers to your input fields! For a full width emoji picker, simply add the attribute `data-meteor-emoji-large="true"` to your field. This will create an always open, full width emoji picker below the desired input box.

If you want the classic "press a button to open" style picker, just use `data-meteor-emoji="true"` on an input field. 



