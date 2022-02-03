# extension-spoofer

A simple Python 3.8.0 script to spoof the extension of a Windows executable file.

# Usage

```

C:\Users\Sploups21> python3 extension-spoofer.py

Enter the complete path to the executable to spoof (in the form of C:/titi/toto/file.exe or C:\titi\toto\file.exe):
> C:\Users\Sploups21\Desktop\file.exe

Enter the extension to spoof : pdf

[V] Extension spoofed with success.

```
  
## Tip

It is recommended to choose a filename finishing by the same letters of your extension since the extension is not removed but simply reversed, thanks to the Unicode code "U+202E".

So since the extension of your original Windows executable is ".exe", it's more coherent to rename it by a word finishing by "exe", like "reflexe" for example, and to remove the last three characters of it so you will get "refl.exe".

Thanks to this method, an executable named refl.exe, which spoof extension is pdf, will give you reflexe.pdf while an executable named titi.exe, which spoof extension is pdf, will give titiexe.pdf, which is less discrete.

You can find some french words finishing by "exe" in Wordlist_FR.txt

You can then change manually the icon of your file corresponding to the extension you choosed to spoof. 

## Example

