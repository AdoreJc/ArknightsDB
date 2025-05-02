# DoubleBufferedList

**Namespace:** `Torappu`


## Fields

- `UInt16 m_eCounter`


## Properties

- `Int32 count`

- `Boolean isEmpty`

- `Boolean isInLoop`


## Methods

- `Int32 get_count()`

- `Boolean get_isEmpty()`

- `Boolean get_isInLoop()`

- `Boolean Remove(T)`

- `Void Clear()`

- `Void _ForwardEnumeratorOnDispose(ForwardEnumerator)`

- `Void _BackwardEnumeratorOnDispose(BackwardEnumerator)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DoubleBufferedList`1 : IEnumerable`1, IEnumerable, IHotfixable
{
	protected List`1 m_internalList; // 0x0
	protected List`1 m_cachedBuffer; // 0x0
	private UInt16 m_eCounter; // 0x0
	private Stack`1 m_forwardEnumeratorPool; // 0x0
	private Stack`1 m_backwardEnumeratorPool; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x0
	private static DelegateBridge __Hotfix0_get_isInLoop; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge _c__Hotfix1_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Add; // 0x0
	private static DelegateBridge __Hotfix0_Remove; // 0x0
	private static DelegateBridge __Hotfix0_Clear; // 0x0
	private static DelegateBridge __Hotfix0_GetEnumerator; // 0x0
	private static DelegateBridge __Hotfix0_GetInversedEnumerator; // 0x0
	private static DelegateBridge __Hotfix0_System.Collections.IEnumerable.GetEnumerator; // 0x0
	private static DelegateBridge __Hotfix0__ForwardEnumeratorOnDispose; // 0x0
	private static DelegateBridge __Hotfix0__BackwardEnumeratorOnDispose; // 0x0

	public Int32 count { get; }
	public Boolean isEmpty { get; }
	public Boolean isInLoop { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_count() { }
	// RVA: 0x VA: 0x0
	public Boolean get_isEmpty() { }
	// RVA: 0x VA: 0x0
	public Boolean get_isInLoop() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x VA: 0x0
	public virtual Void Add(T element) { }
	// RVA: 0x VA: 0x0
	public Boolean Remove(T element) { }
	// RVA: 0x VA: 0x0
	public Void Clear() { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x VA: 0x0
	public IEnumerator`1 GetInversedEnumerator() { }
	// RVA: 0x VA: 0x0
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x VA: 0x0
	private Void _ForwardEnumeratorOnDispose(ForwardEnumerator enumerator) { }
	// RVA: 0x VA: 0x0
	private Void _BackwardEnumeratorOnDispose(BackwardEnumerator enumerator) { }
}
```