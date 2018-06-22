#Show Formatting marks in CKeditor

**Word has a feature to Show or hide formatting marks**
Formatting marks like dots (…) for spaces or arrows (→) for tab characters are used in Word to show the text layouts of documents. 
You might find these formatting marks useful when you're designing content with a specific look in mind.

This is not possible in a web WYSIWYG editor.

In this configuration of CKeditor it is now possible!.
- For the "dot" as whitespace a font with a "dot" instead of a whitespace is used
- For the Paragraph / Hard breaks a CSS styling is used
- The Tab and Soft breaks are replaced by another character.

Keep in mind that when you save this you must remove arrow used for the softbreak and replace the arrow for the tab (if you use it).

![Formatting marks](CKEditorFormattingMarks.png?raw=true "Formatting marks")    

