# Fuzzers
各种Fuzzing工具搜集

## NET Fuzz

- **Fuzz OPC UA implementations**   
This is a black box fuzzing solution targeting the OPC UA protocol. The fuzzing is based on the mutational fuzzing engine boofuzz.    
https://github.com/fkie-cad/blackbox-opcua-fuzzing

- **Http fuzzer with go**   
go语言的http fuzzer，需要自己写插件
https://github.com/JonCooperWorks/httpfuzz    

- **mutiny Fuzzer**   
利用流量嗅探进行Fuzz的工具   
https://github.com/Cisco-Talos/mutiny-fuzzer 


## File Fuzz
- **PE-AFL**    
pe-afl combines static binary instrumentation on PE binary and WinAFL   
https://github.com/wmliang/pe-afl

- **tinyAFL**    
TinyAFL is built on top of AFL and TinyInst.

It can be fuzz on windows user-mode application without source (supports both x32 and x64) but it is not so reliable and dirty. It still has some instrument bugs, I will fix it when I fully understand TinyInst     
https://github.com/linhlhq/TinyAFL    


https://github.com/JaanusKaapPublic/Vanapagan

https://github.com/aflnet/aflnet
