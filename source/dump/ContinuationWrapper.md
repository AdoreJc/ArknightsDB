# ContinuationWrapper

**Namespace:** ` `


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class ContinuationWrapper
{
	internal readonly Action m_continuation; // 0x10
	private readonly Action m_invokeAction; // 0x18
	internal readonly Task m_innerTask; // 0x20


	// RVA: 0x5fd7f68 VA: 0x75985eff68
	internal Void .ctor(Action continuation, Action invokeAction, Task innerTask) { }
	// RVA: 0x5fd836c VA: 0x75985f036c
	internal Void Invoke() { }
}
```