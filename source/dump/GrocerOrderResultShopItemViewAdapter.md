# GrocerOrderResultShopItemViewAdapter

**Namespace:** ` `


## Fields

- `GroceryOrderResultGoodItemView m_closure`


## Methods

- `IEnumerator PlayEnterAnim()`

- `Single _GetDelay(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GrocerOrderResultShopItemViewAdapter : SimpleLayoutAdapter
{
	private GroceryOrderResultGoodItemView m_closure; // 0x20
	private const Single DELAY_START; // 0x0
	private const Single DELAY_FIRST_SHOP; // 0x0
	private const Single DELAY_SECOND_SHOP; // 0x0
	private const Single DELAY_THIRD_SHOP; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_PlayEnterAnim; // 0x18
	private static DelegateBridge __Hotfix0__GetDelay; // 0x20

	public override Int32 count { get; }

	// RVA: 0x2893f3c VA: 0x7594eabf3c
	public Void .ctor(GroceryOrderResultGoodItemView closure) { }
	// RVA: 0x2894040 VA: 0x7594eac040
	public override Int32 get_count() { }
	// RVA: 0x2894148 VA: 0x7594eac148
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2894598 VA: 0x7594eac598
	public IEnumerator PlayEnterAnim() { }
	// RVA: 0x289466c VA: 0x7594eac66c
	private Single _GetDelay(Int32 index) { }
}
```