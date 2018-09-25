# Ergodox
- https://configure.ergodox-ez.com/layouts/zb7d/latest/0
  
# XCode
/Applications/Xcode.app/Contents/Frameworks/IDEKit.framework/Resources/IDETextKeyBindingSet.plist

– Delete current line: ctrl + shift + k
– Duplicate current line: ctrl + shift + c
– Insert line below: ctrl + o
– Insert line above: ctrl + shift + o

##Insertion and indentation

<key>Insert New Line Below</key>
<string>moveToEndOfLine:, insertNewline:</string>
<key>Insert New Line Above</key>
<string>moveUp:, moveToEndOfLine:, insertNewline:</string>
<key>Duplicate Current Line</key>
<string>selectLine:, copy:, moveToEndOfLine:, insertNewline:, paste:, deleteBackward:</string>



##Deletion

<key>Delete Current Line</key>
<string>selectLine:, delete:</string>
