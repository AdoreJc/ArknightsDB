# TabAdapter

**Namespace:** ` `


## Fields

- `ShopRecommendState m_closure`

- `Boolean m_isInitialRender`


## Methods

- `Void <>xLuaBaseProxy_NotifyDataSetChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TabAdapter : SimpleLayoutAdapter
{
	private ShopRecommendState m_closure; // 0x20
	private Boolean m_isInitialRender; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_NotifyDataSetChanged; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge __Hotfix0_RenderView; // 0x18

	public override Int32 count { get; }

	// RVA: 0x2475544 VA: 0x7594a8d544
	public Void .ctor(ShopRecommendState closure) { }
	// RVA: 0x24755e8 VA: 0x7594a8d5e8
	public override Void NotifyDataSetChanged() { }
	// RVA: 0x2475668 VA: 0x7594a8d668
	public override Int32 get_count() { }
	// RVA: 0x24756fc VA: 0x7594a8d6fc
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x24759d0 VA: 0x7594a8d9d0
	private Void <>xLuaBaseProxy_NotifyDataSetChanged() { }
}
```