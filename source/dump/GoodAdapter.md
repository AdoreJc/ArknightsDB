# GoodAdapter

**Namespace:** ` `


## Fields

- `GroceryHomeView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GoodAdapter : SimpleLayoutAdapter, IHotfixable
{
	private GroceryHomeView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x286392c VA: 0x7594e7b92c
	public Void .ctor(GroceryHomeView closure) { }
	// RVA: 0x28641a0 VA: 0x7594e7c1a0
	public override Int32 get_count() { }
	// RVA: 0x286422c VA: 0x7594e7c22c
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```