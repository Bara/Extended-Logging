Extended Logging
============

[![Alt text](https://travis-ci.org/Bara20/Extended-Logging.svg?branch=master)](https://travis-ci.org/Bara20/Extended-Logging)

is a small extension to the normal logging include. The log entries are sorted categorically. This plugin created by default (provided that such level is in use) the level folder (trace, debug, info, warn and error), if no path name is specified. Otherwise it would look like this 'addons/sourcemod/logs/path'. You can define the file name self and insert in the file name a date (optimal).

### Functions:
 + Log_Default(const String:path[] = "", const String:file[] = "file", const String:date[] = "",  const String:format[], any:...)
 + Log_Trace(const String:path[] = "", const String:file[] = "file", const String:date[] = "",  const String:format[], any:...)
 + Log_Debug(const String:path[] = "", const String:file[] = "file", const String:date[] = "",  const String:format[], any:...)
 + Log_Info(const String:path[] = "", const String:file[] = "file", const String:date[] = "",  const String:format[], any:...)
 + Log_Warn(const String:path[] = "", const String:file[] = "file", const String:date[] = "",  const String:format[], any:...)
 + Log_Error(const String:path[] = "", const String:file[] = "file", const String:date[] = "",  const String:format[], any:...)
 + Log_File(const String:path[] = "", const String:file[] = "file", const String:date[] = "", ELOG_LEVEL:level = INFO, const String:format[], any:...)

### Levels:
 + 0 - DEFAULT
 + 1 - TRACE
 + 2 - DEBUG
 + 3 - INFO
 + 4 - WARN
 + 5 - ERROR

### Download:
 + https://github.com/Bara20/Extended-Logging