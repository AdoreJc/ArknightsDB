# ValidStageEnumerator

**Namespace:** `Torappu`


## Fields

- `Int64 m_targetTs`


## Methods

- `Void Dispose()`

- `Boolean MoveNext()`

- `Void Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ValidStageEnumerator : IEnumerator`1, IEnumerator, IDisposable, IHotfixable
{
	private Int64 m_targetTs; // 0x10
	private KeyValuePair`2 m_current; // 0x18
	private IEnumerator`1 m_rawEnum; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_Current; // 0x8
	private static DelegateBridge __Hotfix0_System.Collections.IEnumerator.get_Current; // 0x10
	private static DelegateBridge __Hotfix0_Dispose; // 0x18
	private static DelegateBridge __Hotfix0_MoveNext; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28

	public KeyValuePair`2 Current { get; }
	private Object System.Collections.IEnumerator.Current { get; }

	// RVA: 0x3540024 VA: 0x7595b58024
	public Void .ctor(Int64 targetTs, IEnumerator`1 rawEnum) { }
	// RVA: 0x35400c4 VA: 0x7595b580c4
	public KeyValuePair`2 get_Current() { }
	// RVA: 0x3540128 VA: 0x7595b58128
	private Object System.Collections.IEnumerator.get_Current() { }
	// RVA: 0x35401c0 VA: 0x7595b581c0
	public Void Dispose() { }
	// RVA: 0x35402b4 VA: 0x7595b582b4
	public Boolean MoveNext() { }
	// RVA: 0x3540564 VA: 0x7595b58564
	public Void Reset() { }
}
```