
# History : shrug
## Prehistory

I was tired of Googling the shrug emoticon, so I endeavored to create a bookmarklet to insert it.

The version implementation worked with INPUT and TEXTAREA elements, but not with websites using a ContentEditable DIV.

The alternative version copies the emoticon to the clipboard.  A paste operation (CTRL-V) is needed to finish inserting the emoticon.

Thusly, emoticons are inserted by either 1 click or 1 click + 1 keyboard shortcut.  Progress!

At this point of development, there are two independent bookmarklets.

## 2020-04-13

### Start of History

* [x] GitHub repo created
* [x] files created
* [x] js code copied from bookmarks
* [x] documentation begun

### Requirements

At this stage, no changes to features  
Two separate links/bookmarks

#### shrug_insert

when cursor is in INPUT or TEXTAREA, click link.    
emoticon text is inserted into respective form element

#### shrug_clipboard

click link  
put cursor into form element or editable HTML element  
upon pasting text, emoticon will appear in respective element

_(make use of onpaste event handler of HTML element and  
  `ClipboardEvent.clipboardData.getData( "text/plain" )` to monitor clipboard)_

### Development

_(not started)_

### Testing

_(not started)_
