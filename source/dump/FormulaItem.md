# FormulaItem

**Namespace:** ` `


## Fields

- `String m_itemId`

- `Int32 m_count`

- `SubType m_subType`

- `UIItemViewModel m_itemModelCache`


## Properties

- `UIItemViewModel model`

- `Int32 storage`


## Methods

- `UIItemViewModel get_model()`

- `Int32 get_storage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FormulaItem : IFormulaItem, IHotfixable
{
	private String m_itemId; // 0x10
	private Int32 m_count; // 0x18
	private SubType m_subType; // 0x1c
	private UIItemViewModel m_itemModelCache; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_model; // 0x8
	private static DelegateBridge __Hotfix0_get_storage; // 0x10

	public UIItemViewModel model { get; }
	public Int32 storage { get; }

	// RVA: 0x3d64ac4 VA: 0x759637cac4
	public Void .ctor(String itemId, Int32 count, SubType subType) { }
	// RVA: 0x3d64c28 VA: 0x759637cc28
	public UIItemViewModel get_model() { }
	// RVA: 0x3d64d0c VA: 0x759637cd0c
	public Int32 get_storage() { }
}
```