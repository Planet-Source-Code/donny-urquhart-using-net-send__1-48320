<div align="center">

## Using Net Send


</div>

### Description

This is a one line tutorial on how to use Net Send to send messages over a network.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Donny urquhart](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/donny-urquhart.md)
**Level**          |Beginner
**User Rating**    |3.7 (33 globes from 9 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/donny-urquhart-using-net-send__1-48320/archive/master.zip)





### Source Code

```
'You need 2 text boxes(Text1, username or IP of the victim(receiver))(Text2, message to send) and a command button(command1)
'In command1 put:
shell "net send " & text1.text & " " & text2.text
'Simple wasn't it. :)
```

