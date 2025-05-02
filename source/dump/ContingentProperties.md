# ContingentProperties

**Namespace:** ` `


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class ContingentProperties
{
	internal ExecutionContext m_capturedContext; // 0x10
	internal ManualResetEventSlim m_completionEvent; // 0x18
	internal TaskExceptionHolder m_exceptionsHolder; // 0x20
	internal CancellationToken m_cancellationToken; // 0x28
	internal Object m_cancellationRegistration; // 0x30
	internal Int32 m_internalCancellationRequested; // 0x38
	internal Int32 m_completionCountdown; // 0x3c
	internal LowLevelListWithIList`1 m_exceptionalChildren; // 0x40


	// RVA: 0x612f184 VA: 0x7598747184
	internal Void SetCompleted() { }
	// RVA: 0x612f1ac VA: 0x75987471ac
	internal Void UnregisterCancellationCallback() { }
	// RVA: 0x612c1bc VA: 0x75987441bc
	public Void .ctor() { }
}
```