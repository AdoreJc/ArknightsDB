# ConsoleLogger

**Namespace:** `UnityEngine`


## Fields

- `LogBuilder m_logBuilder`


## Methods

- `Void Log(ref)`


## Dump
```C#
// Dll : Hypergryph.Log.dll
// Namespace : UnityEngine
public class ConsoleLogger : ILogger
{
	private LogBuilder m_logBuilder; // 0x10


	// RVA: 0x5ec19fc VA: 0x75984d99fc
	public Void .ctor(LogBuilder logBuilder) { }
	// RVA: 0x5ec1a2c VA: 0x75984d9a2c
	public Void Log(ref LogMessage msg) { }
	// RVA: 0x5ec1ad4 VA: 0x75984d9ad4
	private static Void LogToUnity(LogLevel level, String msg, Exception exception, Object context) { }
}
```