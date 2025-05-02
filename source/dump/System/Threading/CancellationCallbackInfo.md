# CancellationCallbackInfo

**Namespace:** `System.Threading`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
internal class CancellationCallbackInfo
{
	internal readonly Action`1 Callback; // 0x10
	internal readonly Object StateForCallback; // 0x18
	internal readonly ExecutionContext TargetExecutionContext; // 0x20
	internal readonly CancellationTokenSource CancellationTokenSource; // 0x28
	private static ContextCallback s_executionContextCallback; // 0x0


	// RVA: 0x611b7a8 VA: 0x75987337a8
	internal Void .ctor(Action`1 callback, Object stateForCallback, ExecutionContext targetExecutionContext, CancellationTokenSource cancellationTokenSource) { }
	// RVA: 0x611be9c VA: 0x7598733e9c
	internal Void ExecuteCallback() { }
	// RVA: 0x611c9d8 VA: 0x75987349d8
	private static Void ExecutionContextCallback(Object obj) { }
}
```