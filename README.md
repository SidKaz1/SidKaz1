- 👋 Hi All,

- 💞️ I’m looking for help.
-
I am getting the following error. I tried to get a solution on google but no sucess. Please help me on this

--->
## R Session Startup Failure Report

### RStudio Version

MISSING VALUE

Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) QtWebEngine/5.12.8 Chrome/69.0.3497.128 Safari/537.36

### Error message

[No error available]

### Process Output

The R session exited with code 2. 

Error output:

```
[4708:9028:20211221,155747.926:ERROR crashpad_client_win.cc:491] CreateProcess: The system cannot find the file specified. (2)

```

Standard output:

```
[No output emitted]
```

### Logs

*C:/Users/492726/AppData/Local/RStudio-Desktop/log/rsession-492726.log*

```
21 Dec 2021 15:47:55 [rsession-492726] ERROR r error 4 (R code execution error) [errormsg: Error in .Call("rs_rstudioLongVersion", PACKAGE = "(embedding)") :
"rs_rstudioLongVersion" not available for .Call() for package "(embedding)"
]; OCCURRED AT class rstudio::core::Error __cdecl rstudio::r::exec::evaluateString(const class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,struct SEXPREC **,class rstudio::r::sexp::Protect *) src/cpp/r/RExec.cpp:314; LOGGED FROM: int __cdecl rstudio::r::session::RReadConsole(const char *,char *,int,int) src/cpp/r/session/RStdCallbacks.cpp:295

```

####


System Information
--------------------------------------------------
sysname        : Windows       
release        : 10 x64        
version        : build 19042   
nodename       : D-40B07640D150
machine        : x86    

RStudio 2021.09.1+372 "Ghost Orchid" Release (99999999999999999999999999999999, 2021-11-08) for Windows
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) QtWebEngine/5.12.8 Chrome/69.0.3497.128 Safari/537.36
                
