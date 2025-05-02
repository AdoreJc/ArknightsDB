# CustomLogger

**Namespace:** `Sirenix.Serialization`


## Methods

- `Void LogWarning(String)`

- `Void LogError(String)`

- `Void LogException(Exception)`


## Dump
```C#
// Dll : Sirenix.Serialization.Config.dll
// Namespace : Sirenix.Serialization
public class CustomLogger : ILogger
{
	private Action`1 logWarningDelegate; // 0x10
	private Action`1 logErrorDelegate; // 0x18
	private Action`1 logExceptionDelegate; // 0x20


	// RVA: 0x61be924 VA: 0x75987d6924
	public Void .ctor(Action`1 logWarningDelegate, Action`1 logErrorDelegate, Action`1 logExceptionDelegate) { }
	// RVA: 0x61bea24 VA: 0x75987d6a24
	public Void LogWarning(String warning) { }
	// RVA: 0x61bea48 VA: 0x75987d6a48
	public Void LogError(String error) { }
	// RVA: 0x61bea6c VA: 0x75987d6a6c
	public Void LogException(Exception exception) { }
}
```