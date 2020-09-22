<div align="center">

## Create and save into \.txt files\.


</div>

### Description

This will create and write into a *.txt file of your choice. Put this code in a timer and you have yourself a keystroke logger. You can save the contents of a textbox into a file also.
 
### More Info
 
Put this code in a button and it will save the contents of a textbox.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Abdul Kudrath](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/abdul-kudrath.md)
**Level**          |Unknown
**User Rating**    |4.3 (30 globes from 7 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/abdul-kudrath-create-and-save-into-txt-files__1-1910/archive/master.zip)





### Source Code

```
' code for saving into a .txt file
' put into a button
open "path and filename" for append as 1
' example C:\demo.txt
print #1, text1.text
close 1
```

