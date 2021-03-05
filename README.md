# cereal
Sub pra()     a = Hoja1.Cells(4, 4)     b = Hoja1.Cells(4, 3)     i = i     sw = True     While (sw)     Hoja1.Cells(4, i + 4) = a     Hoja1.Cells(4, i + 3) = b     p = InputBox("desa continuar si/no")     If p = "si" Then     i = i + 1     Else     sw = False     End If     Wend      End Sub
