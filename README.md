# A Meteor compatible Emoji Picker

> After trapsing through a tonne of emoji pickers for Meteor project. It became pretty apparent that most of them didn't work, or were just pretty terrible. This emoji picker is pure, vanilla JavaScript, so should be compatible with most JS projects. However, I've specifically built this for the intent to use with Meteor. 

## How do I use it?

This plugin can be installed via NPM:

```
npm install meteor-emoji
```

Or Meteor 

```
meteor add georgemccann:meteor-emoji-picker
```

Include the meteorEmoji.min.js file from the 'dist' folder in your project, and then use:

```js
new MeteorEmoji();
```

Now you can add emoji pickers to your input fields! For a full width emoji picker, simply add the attribute `data-meteor-emoji-large="true"` to your field. This will create an always open, full width emoji picker below the desired input box.

If you want the classic "press a button to open" style picker, just use `data-meteor-emoji="true"` on an input field. 



