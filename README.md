<div align="center">

## Converting Decimal numbers to Binary


</div>

### Description

A function for converting decimal numbers to binary. Very fast.
 
### More Info
 
Decimal number (Long)

Binary number (string)


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[K\. Mehdi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/k-mehdi.md)
**Level**          |Unknown
**User Rating**    |4.8 (24 globes from 5 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Math/ Dates](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math-dates__1-37.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/k-mehdi-converting-decimal-numbers-to-binary__1-795/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
DecValue = Val(Text1.Text)
BinValue = ""
Do
TempValue = DecValue Mod 2
  BinValue = CStr(TempValue) + BinValue
DecValue = DecValue \ 2
Loop Until DecValue = 0
'Print
'Print BinValue
Text2.Text = BinValue
End Sub
```

