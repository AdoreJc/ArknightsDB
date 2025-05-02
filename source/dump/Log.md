# Log

**Namespace:** ` `


## Fields

- `LogType logType`

- `String logString`

- `String stacktrace`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Log
{
	public LogType logType; // 0x10
	public String logString; // 0x18
	public String stacktrace; // 0x20
	public Action`1 callback; // 0x28


	// RVA: 0x29bb200 VA: 0x7594fd3200
	public Void .ctor() { }
}
```