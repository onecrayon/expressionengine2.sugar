# expressionengine2 Espresso Sugar


**NB:** This sugar for compatibility with [Espresso 2](http://macrabbit.com/espresso/2/) - for Espresso 1.x you should use the 1.1.2-legacy tag.

**This sugar has been converted from [Anthony Short's](https://github.com/anthonyshort/) [ee1 sugar](https://github.com/anthonyshort/expressionengine.sugar) - the majority of the work is his, (though I *think* he in turn converted it from the [EE TextMate bundle](http://www.chrisruzin.net/entry/textmate_expressionengine_bundle/) ). All this version does is update that sugar to work with ee2 and rename things so that it plays nice with the ee1 sugar, and add a few extra snippets. It almost certainly contains the odd bug - if you find one please do open an issue or pull request...**

This sugar gives you access to the ee2 template syntax within [Espresso](http://macrabbit.com/espresso/), giving you codesense, itemizers and more. 

## Download and Install

### Via Git (for easy updates)

- open a terminal session
- `cd ~/Library/Application Support/Espresso/Sugars/`
- `git clone git://github.com/tomdavies/expressionengine2.sugar.git`
- restart Espresso

### Manually

- Use the download link at the top of the page
- Rename the folder that downloads to "expressionengine2.sugar"
- Double click the sugar and it's installed. 
	
## Theme

Themed to match [Anthony Short's quiet night theme](http://github.com/anthonyshort/quiet-night.foam/tree/master)
	
## Known Bugs

- There are duplicate auto completes in the drop-down menu. This will be fixed soon, but is there as I am getting the sugar ready to do tag-sensitive auto completes. 

## To Dos

### New

- Integrate some of the interesting stuff from [https://github.com/wesbaker/ExpressionEngine2.tmbundle]

### From ee1 sugar

- Text Actions
- File Actions
- Common Formatting dates in the codesense
- IP to Nation
- Referrer Tag
- RSS Tag
- Trackback Tag
- Simple Commerce
- Common Plugins