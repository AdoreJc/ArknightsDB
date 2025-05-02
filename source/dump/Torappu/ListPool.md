# ListPool

**Namespace:** `Torappu`


## Fields

- `Options m_options`


## Properties

- `Int32 allLoadedCnt`

- `Int32 availableUnusedCnt`


## Methods

- `Int32 get_allLoadedCnt()`

- `Int32 get_availableUnusedCnt()`

- `Void Recycle(ReusableList`1)`

- `Void Reset()`

- `Void ClearUsingLinksOnly()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ListPool`1 : IHotfixable
{
	private Options m_options; // 0x0
	private ObjectPool`1 m_objectPool; // 0x0
	private static DelegateBridge __Hotfix0_get_allLoadedCnt; // 0x0
	private static DelegateBridge __Hotfix0_get_availableUnusedCnt; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Allocate; // 0x0
	private static DelegateBridge __Hotfix0_Recycle; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_ClearUsingLinksOnly; // 0x0
	private static DelegateBridge __Hotfix0__NewList; // 0x0

	public Int32 allLoadedCnt { get; }
	public Int32 availableUnusedCnt { get; }

	// RVA: 0x VA: 0x0
	public Int32 get_allLoadedCnt() { }
	// RVA: 0x VA: 0x0
	public Int32 get_availableUnusedCnt() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Options options) { }
	// RVA: 0x VA: 0x0
	public ReusableList`1 Allocate() { }
	// RVA: 0x VA: 0x0
	public Void Recycle(ReusableList`1 list) { }
	// RVA: 0x VA: 0x0
	public Void Reset() { }
	// RVA: 0x VA: 0x0
	public Void ClearUsingLinksOnly() { }
	// RVA: 0x VA: 0x0
	private ReusableList`1 _NewList() { }
}
```