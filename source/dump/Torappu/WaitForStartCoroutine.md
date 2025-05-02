# WaitForStartCoroutine

**Namespace:** `Torappu`


## Fields

- `Boolean m_isFinished`

- `IEnumerator <wrappedRoutine>k__BackingField`


## Properties

- `IEnumerator wrappedRoutine`


## Methods

- `IEnumerator get_wrappedRoutine()`

- `Void set_wrappedRoutine(IEnumerator)`

- `IEnumerator _WrappedRoutine(IEnumerator)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class WaitForStartCoroutine : CustomYieldInstruction
{
	private Boolean m_isFinished; // 0x10
	private IEnumerator <wrappedRoutine>k__BackingField; // 0x18

	public override Boolean keepWaiting { get; }
	public IEnumerator wrappedRoutine { get; set; }

	// RVA: 0x677b724 VA: 0x7598d93724
	public override Boolean get_keepWaiting() { }
	// RVA: 0x677b734 VA: 0x7598d93734
	public IEnumerator get_wrappedRoutine() { }
	// RVA: 0x677b73c VA: 0x7598d9373c
	private Void set_wrappedRoutine(IEnumerator value) { }
	// RVA: 0x677b744 VA: 0x7598d93744
	public Void .ctor(IEnumerator routine, Func`2 startCoroFunc) { }
	// RVA: 0x677b7b0 VA: 0x7598d937b0
	private IEnumerator _WrappedRoutine(IEnumerator routine) { }
}
```