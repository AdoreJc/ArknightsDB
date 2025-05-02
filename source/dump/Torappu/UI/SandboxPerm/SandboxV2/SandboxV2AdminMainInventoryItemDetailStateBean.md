# SandboxV2AdminMainInventoryItemDetailStateBean

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <topicId>k__BackingField`

- `Int32 <defaultItemIdx>k__BackingField`


## Properties

- `String topicId`

- `Int32 defaultItemIdx`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Void set_itemList(List`1)`

- `Int32 get_defaultItemIdx()`

- `Void set_defaultItemIdx(Int32)`

- `Void SetItemList(List`1, Int32, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainInventoryItemDetailStateBean : IStateBean, IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	private List`1 <itemList>k__BackingField; // 0x18
	private Int32 <defaultItemIdx>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_itemList; // 0x10
	private static DelegateBridge __Hotfix0_set_itemList; // 0x18
	private static DelegateBridge __Hotfix0_get_defaultItemIdx; // 0x20
	private static DelegateBridge __Hotfix0_set_defaultItemIdx; // 0x28
	private static DelegateBridge __Hotfix0_SetItemList; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public String topicId { get; set; }
	public List`1 itemList { get; set; }
	public Int32 defaultItemIdx { get; set; }

	// RVA: 0x24d29d4 VA: 0x7594aea9d4
	public String get_topicId() { }
	// RVA: 0x24d2a3c VA: 0x7594aeaa3c
	private Void set_topicId(String value) { }
	// RVA: 0x24d2ac0 VA: 0x7594aeaac0
	public List`1 get_itemList() { }
	// RVA: 0x24d2b28 VA: 0x7594aeab28
	private Void set_itemList(List`1 value) { }
	// RVA: 0x24d2bac VA: 0x7594aeabac
	public Int32 get_defaultItemIdx() { }
	// RVA: 0x24d2c14 VA: 0x7594aeac14
	private Void set_defaultItemIdx(Int32 value) { }
	// RVA: 0x24d2c90 VA: 0x7594aeac90
	public Void SetItemList(List`1 items, Int32 currIdx, String topic) { }
	// RVA: 0x24d295c VA: 0x7594aea95c
	public Void .ctor() { }
}
```