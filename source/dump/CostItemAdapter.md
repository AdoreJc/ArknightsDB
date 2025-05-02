# CostItemAdapter

**Namespace:** ` `


## Fields

- `RecruitGachaConfirmView m_closure`

- `Boolean m_ignoreUsedOutStyle`


## Properties

- `Boolean ignoreUsedOutStyle`


## Methods

- `Void set_itemList(List`1)`

- `Void set_ignoreUsedOutStyle(Boolean)`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CostItemAdapter : SimpleLayoutAdapter
{
	private RecruitGachaConfirmView m_closure; // 0x20
	private List`1 m_itemList; // 0x28
	private Boolean m_ignoreUsedOutStyle; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_set_itemList; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge __Hotfix0_set_ignoreUsedOutStyle; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x28

	public List`1 itemList { set; }
	public override Int32 count { get; }
	public Boolean ignoreUsedOutStyle { set; }

	// RVA: 0x2708efc VA: 0x7594d20efc
	public Void .ctor(RecruitGachaConfirmView closure) { }
	// RVA: 0x270a1f0 VA: 0x7594d221f0
	public Void set_itemList(List`1 value) { }
	// RVA: 0x270bfd8 VA: 0x7594d23fd8
	public override Int32 get_count() { }
	// RVA: 0x2708f90 VA: 0x7594d20f90
	public Void set_ignoreUsedOutStyle(Boolean value) { }
	// RVA: 0x270c058 VA: 0x7594d24058
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x270c3a0 VA: 0x7594d243a0
	private Void _OnItemCardClicked(Int32 position) { }
}
```