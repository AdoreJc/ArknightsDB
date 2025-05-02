# InterlockItemAdapter

**Namespace:** ` `


## Fields

- `Act1LockFinalDetailView m_closure`


## Methods

- `Act1LockFinalItemView _GetItemView(Int32)`

- `Single GetItemWidth(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InterlockItemAdapter : SimpleLayoutAdapter
{
	private Act1LockFinalDetailView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0__GetItemView; // 0x10
	private static DelegateBridge __Hotfix0_GetItemWidth; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20

	public override Int32 count { get; }

	// RVA: 0x33ab930 VA: 0x75959c3930
	public Void .ctor(Act1LockFinalDetailView closure) { }
	// RVA: 0x33acac0 VA: 0x75959c4ac0
	public override Int32 get_count() { }
	// RVA: 0x33acb54 VA: 0x75959c4b54
	private Act1LockFinalItemView _GetItemView(Int32 position) { }
	// RVA: 0x33abe70 VA: 0x75959c3e70
	public Single GetItemWidth(Int32 position) { }
	// RVA: 0x33accd0 VA: 0x75959c4cd0
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```