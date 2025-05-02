# UnionLogger

**Namespace:** ` `


## Methods

- `Boolean Add(ILogger)`

- `Boolean Remove(ILogger)`

- `Void Log(ref)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class UnionLogger : ILogger
{
	private ListSet`1 m_loggers; // 0x10


	// RVA: 0x6744d20 VA: 0x7598d5cd20
	public Boolean Add(ILogger logger) { }
	// RVA: 0x6744e64 VA: 0x7598d5ce64
	public Boolean Remove(ILogger logger) { }
	// RVA: 0x674541c VA: 0x7598d5d41c
	public Void Log(ref LogMessage msg) { }
	// RVA: 0x6744bf0 VA: 0x7598d5cbf0
	public Void .ctor() { }
}
```