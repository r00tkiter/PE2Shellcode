# PE2Shellcode

Converts PE so that it can be then injected just like a normal shellcode.

# How to use

Optional parameter.  

> P2S.exe &lt; path of PE&gt; [output path] [-?]  
> [-r] Rc4 encrypt  
> [-c] Compress PE file  

i.e.
> P2S_x86.exe test.exe test_x86.bin -c -r  
> P2S_x64.exe test64.exe test_x64.bin -r
