# TaskExceptionHolder

**Namespace:** `System.Threading.Tasks`


## Fields

- `ExceptionDispatchInfo m_cancellationException`

- `Boolean m_isHandled`


## Methods

- `Void SetCancellationException(Object)`

- `Void AddFaultException(Object)`

- `Void MarkAsUnhandled()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
internal class TaskExceptionHolder
{
	private static readonly Boolean s_failFastOnUnobservedException; // 0x0
	private readonly Task m_task; // 0x10
	private LowLevelListWithIList`1 m_faultExceptions; // 0x18
	private ExceptionDispatchInfo m_cancellationException; // 0x20
	private Boolean m_isHandled; // 0x28

	internal Boolean ContainsFaultList { get; }

	// RVA: 0x612e598 VA: 0x7598746598
	internal Void .ctor(Task task) { }
	// RVA: 0x61354a0 VA: 0x759874d4a0
	private static Boolean ShouldFailFastOnUnobservedException() { }
	// RVA: 0x61354a8 VA: 0x759874d4a8
	protected override Void Finalize() { }
	// RVA: 0x612e194 VA: 0x7598746194
	internal Boolean get_ContainsFaultList() { }
	// RVA: 0x612e5c8 VA: 0x75987465c8
	internal Void Add(Object exceptionObject, Boolean representsCancellation) { }
	// RVA: 0x613586c VA: 0x759874d86c
	private Void SetCancellationException(Object exceptionObject) { }
	// RVA: 0x6135930 VA: 0x759874d930
	private Void AddFaultException(Object exceptionObject) { }
	// RVA: 0x6135e4c VA: 0x759874de4c
	private Void MarkAsUnhandled() { }
	// RVA: 0x612e378 VA: 0x7598746378
	internal Void MarkAsHandled(Boolean calledFromFinalizer) { }
	// RVA: 0x612e5d4 VA: 0x75987465d4
	internal AggregateException CreateExceptionObject(Boolean calledFromFinalizer, Exception includeThisException) { }
	// RVA: 0x612e8bc VA: 0x75987468bc
	internal ReadOnlyCollection`1 GetExceptionDispatchInfos() { }
	// RVA: 0x6135ebc VA: 0x759874debc
	internal ExceptionDispatchInfo GetCancellationExceptionDispatchInfo() { }
	// RVA: 0x6135ec4 VA: 0x759874dec4
	private static Void .cctor() { }
}
```