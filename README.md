# -Readme.md
1 Задача
Excel
Option Explicit 'Ïåðåìåííûå îáúÿâëÿòü ÿâíî
Sub qwerty4()
Dim N As Single
Dim M As Single
Dim X As Single
Dim Y As Single
Dim min As Single
Worksheets("Ëèñò4(7)").Select
N = InputBox("Ââåäèòå ñòîðîíó áàññåéíà
M = InputBox("Ââåäèòå ñòîðîíó áàññåéíà")
X = InputBox("Ââåäèòå ðàññòîÿíèå îò áîðòèêà")
Y = InputBox("Ââåäèòå ðàññòîÿíèå îò áîðòèêà")
If X < Y Then
min = X
Else
min = Y
End If
MsgBox ("min=") & CByte(min)
Cells(6, 2).Value = ("min=") & CByte(min)
End Sub

Тест по Good Line
