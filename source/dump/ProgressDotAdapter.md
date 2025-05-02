# ProgressDotAdapter

**Namespace:** ` `


## Fields

- `GrocerySellView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ProgressDotAdapter : SimpleLayoutAdapter, IHotfixable
{
	private GrocerySellView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x289e7b4 VA: 0x7594eb67b4
	public Void .ctor(GrocerySellView closure) { }
	// RVA: 0x289ec7c VA: 0x7594eb6c7c
	public override Int32 get_count() { }
	// RVA: 0x289ecf0 VA: 0x7594eb6cf0
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```