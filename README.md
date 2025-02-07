# LionDance

A bookmarklet that types the clipboard into the current cursor location for the purpose of entering pinyin into Google Translate.


# Code Snippits

Note this does not trigger a space event properly:
```
"wo shi".split("").forEach(c => ta.dispatchEvent(new KeyboardEvent('keypress', {
 'charCode': c.charCodeAt(0),
})));
```
