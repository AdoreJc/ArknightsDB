# ThreadHelper

**Namespace:** `System.Threading`


## Fields

- `Delegate _start`

- `Object _startArg`

- `ExecutionContext _executionContext`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading
internal class ThreadHelper
{
	private Delegate _start; // 0x10
	private Object _startArg; // 0x18
	private ExecutionContext _executionContext; // 0x20
	internal static ContextCallback _ccb; // 0x0


	// RVA: 0x6122468 VA: 0x759873a468
	internal Void .ctor(Delegate start) { }
	// RVA: 0x6122498 VA: 0x759873a498
	internal Void SetExecutionContextHelper(ExecutionContext ec) { }
	// RVA: 0x61224a0 VA: 0x759873a4a0
	private static Void ThreadStart_Context(Object state) { }
	// RVA: 0x61225ac VA: 0x759873a5ac
	internal Void ThreadStart(Object obj) { }
	// RVA: 0x61226bc VA: 0x759873a6bc
	internal Void ThreadStart() { }
	// RVA: 0x61227b0 VA: 0x759873a7b0
	private static Void .cctor() { }
}
```