# PoolWorker
Use CreateThreadpoolWork to execute shellcode

Compile: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\csc.exe /platform:x64 /target:exe /unsafe PoolWorker.cs

PoolWorker has Mimikatz embedded as CSharp classes in shellcode format, all low level API calls to kernel32.dll and ntddl.dll is done by 
find baseaddress and then loop through and look for hash ROR13 function name.


