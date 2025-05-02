# OutputItemListAdapter

**Namespace:** ` `


## Fields

- `ItemRepoOptionalVoucherView m_closure`

- `UIStringEvent OnAddItemClickEvent`

- `UIStringEvent OnDetailClickEvent`

- `UIStringEvent OnMinusItemClickEvent`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class OutputItemListAdapter : SimpleLayoutAdapter
{
	private ItemRepoOptionalVoucherView m_closure; // 0x20
	public UIStringEvent OnAddItemClickEvent; // 0x28
	public UIStringEvent OnDetailClickEvent; // 0x30
	public UIStringEvent OnMinusItemClickEvent; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x2d374e0 VA: 0x759534f4e0
	public Void .ctor(ItemRepoOptionalVoucherView closure) { }
	// RVA: 0x2d37b1c VA: 0x759534fb1c
	public override Int32 get_count() { }
	// RVA: 0x2d37bb0 VA: 0x759534fbb0
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```