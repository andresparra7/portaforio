# portaforio
portaforio de codigos de programacion
# taller en clases  
~~~
Sub hotel()
 a = Int(InputBox("cuantas noches se hospedo"))
 If a > 3 Then
 b = a * 5 / 100
 c = a - b
 d = c * 100
 MsgBox "tiene que pagar: " & d & "dolares"
 Else
 e = a * 100
 MsgBox "tiene que pagar: " & e & "dolares"
End If
End Sub
~~~
# repetir variable
Sub p()
For a = 1 To 7
MsgBox "peeeeee"
Next
~~~
# codigo generador de datos
Sub nombres()
For x = 2 To 21

c = ap.Cells(x, 1)
 Z = Int(Len(c))
 q = Mid(c, Z - 1, 2)
 ap.Cells(x, 2) = q
 Next x
 
End Sub
