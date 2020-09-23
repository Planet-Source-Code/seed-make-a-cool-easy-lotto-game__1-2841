<div align="center">

## \!\!\!\*\!Make a cool EASY Lotto Game\!\*\!\!\!


</div>

### Description

MAKE AN EASY LOTTO GAME!!! ***UPDATED***
 
### More Info
 
You're going to need 3 Labels to start. You can add more once you get the hang of it. You also need 1 Command button. Make it's caption "OK", and the Labels captions blank. Follow the simple instructions below.

You can alter this code to your convienience. Here are some nifty things you could change:

You could use text boxes instead of labels. You would have to change every "Label1.Caption" to "Text1.Text" and so on.

You can add as many more text boxes or labels as you'd like, as long as you adjust the code accrodingly.

If your smart enough, you could make it a simple password entry screen, but you'd have to do some easy error handling and you'd have to use text boxes instead of labels.

If your smart enough, you could make a simple lotto game to share with your friends and family. - SeeD (o:


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SeeD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/seed.md)
**Level**          |Unknown
**User Rating**    |2.3 (35 globes from 15 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/seed-make-a-cool-easy-lotto-game__1-2841/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
 Label1.Caption = Int(rnd * 10)
 Label2.Caption = Int(rnd * 10)
 Label3.Caption = Int(rnd * 10)
If (Label1.Caption = Label2.Caption) And (Label3.Caption = Label2.Caption) Then
 MsgBox "You Win!", 8, "Winner!"
End If
End Sub
```

