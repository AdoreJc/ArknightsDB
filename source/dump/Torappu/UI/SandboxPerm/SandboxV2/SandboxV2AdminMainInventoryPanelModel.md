# SandboxV2AdminMainInventoryPanelModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <topicId>k__BackingField`

- `SandboxV2AdminMainInventoryItemShowType <itemShowType>k__BackingField`

- `Int32 <currClickItemIdx>k__BackingField`

- `Boolean <isSingleMode>k__BackingField`


## Properties

- `String topicId`

- `SandboxV2AdminMainInventoryItemShowType itemShowType`

- `Int32 currClickItemIdx`

- `Boolean isSingleMode`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `SandboxV2AdminMainInventoryItemShowType get_itemShowType()`

- `Void set_itemShowType(SandboxV2AdminMainInventoryItemShowType)`

- `Void set_allItem(List`1)`

- `Void set_showItemList(List`1)`

- `Int32 get_currClickItemIdx()`

- `Void set_currClickItemIdx(Int32)`

- `Boolean get_isSingleMode()`

- `Void set_isSingleMode(Boolean)`

- `Void Init(String)`

- `Void Reload()`

- `Void _LoadAllItem(String)`

- `SandboxV2AdminMainInventoryItemModel _AddItemToAll(String, Int32)`

- `Boolean SetCurrItemViewType(SandboxV2AdminMainInventoryItemShowType, Boolean)`

- `Int32 _ItemSort(SandboxV2AdminMainInventoryItemModel, SandboxV2AdminMainInventoryItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainInventoryPanelModel : IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	private SandboxV2AdminMainInventoryItemShowType <itemShowType>k__BackingField; // 0x18
	private List`1 <allItem>k__BackingField; // 0x20
	private List`1 <showItemList>k__BackingField; // 0x28
	private Int32 <currClickItemIdx>k__BackingField; // 0x30
	private Boolean <isSingleMode>k__BackingField; // 0x34
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_itemShowType; // 0x10
	private static DelegateBridge __Hotfix0_set_itemShowType; // 0x18
	private static DelegateBridge __Hotfix0_get_allItem; // 0x20
	private static DelegateBridge __Hotfix0_set_allItem; // 0x28
	private static DelegateBridge __Hotfix0_get_showItemList; // 0x30
	private static DelegateBridge __Hotfix0_set_showItemList; // 0x38
	private static DelegateBridge __Hotfix0_get_currClickItemIdx; // 0x40
	private static DelegateBridge __Hotfix0_set_currClickItemIdx; // 0x48
	private static DelegateBridge __Hotfix0_get_isSingleMode; // 0x50
	private static DelegateBridge __Hotfix0_set_isSingleMode; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x60
	private static DelegateBridge __Hotfix0_Reload; // 0x68
	private static DelegateBridge __Hotfix0__LoadAllItem; // 0x70
	private static DelegateBridge __Hotfix0__AddItemToAll; // 0x78
	private static DelegateBridge __Hotfix0_SetCurrItemViewType; // 0x80
	private static DelegateBridge __Hotfix0__ItemSort; // 0x88
	private static DelegateBridge __Hotfix0_CheckItemShowType; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public String topicId { get; set; }
	public SandboxV2AdminMainInventoryItemShowType itemShowType { get; set; }
	public List`1 allItem { get; set; }
	public List`1 showItemList { get; set; }
	public Int32 currClickItemIdx { get; set; }
	public Boolean isSingleMode { get; set; }

	// RVA: 0x24d6b58 VA: 0x7594aeeb58
	public String get_topicId() { }
	// RVA: 0x24d6bc0 VA: 0x7594aeebc0
	private Void set_topicId(String value) { }
	// RVA: 0x24d6c44 VA: 0x7594aeec44
	public SandboxV2AdminMainInventoryItemShowType get_itemShowType() { }
	// RVA: 0x24d6cac VA: 0x7594aeecac
	private Void set_itemShowType(SandboxV2AdminMainInventoryItemShowType value) { }
	// RVA: 0x24d6d28 VA: 0x7594aeed28
	public List`1 get_allItem() { }
	// RVA: 0x24d6d90 VA: 0x7594aeed90
	private Void set_allItem(List`1 value) { }
	// RVA: 0x24d6e14 VA: 0x7594aeee14
	public List`1 get_showItemList() { }
	// RVA: 0x24d6e7c VA: 0x7594aeee7c
	private Void set_showItemList(List`1 value) { }
	// RVA: 0x24d6f00 VA: 0x7594aeef00
	public Int32 get_currClickItemIdx() { }
	// RVA: 0x24d6f68 VA: 0x7594aeef68
	public Void set_currClickItemIdx(Int32 value) { }
	// RVA: 0x24d6fe4 VA: 0x7594aeefe4
	public Boolean get_isSingleMode() { }
	// RVA: 0x24d704c VA: 0x7594aef04c
	public Void set_isSingleMode(Boolean value) { }
	// RVA: 0x24d70cc VA: 0x7594aef0cc
	public Void Init(String topic) { }
	// RVA: 0x24d714c VA: 0x7594aef14c
	public Void Reload() { }
	// RVA: 0x24d71dc VA: 0x7594aef1dc
	private Void _LoadAllItem(String topic) { }
	// RVA: 0x24d7d48 VA: 0x7594aefd48
	private SandboxV2AdminMainInventoryItemModel _AddItemToAll(String itemId, Int32 count) { }
	// RVA: 0x24d7a68 VA: 0x7594aefa68
	public Boolean SetCurrItemViewType(SandboxV2AdminMainInventoryItemShowType showType, Boolean forceRefresh) { }
	// RVA: 0x24d8014 VA: 0x7594af0014
	private Int32 _ItemSort(SandboxV2AdminMainInventoryItemModel item1, SandboxV2AdminMainInventoryItemModel item2) { }
	// RVA: 0x24d7f90 VA: 0x7594aeff90
	public static SandboxV2AdminMainInventoryItemShowType CheckItemShowType(SandboxPermItemType itemType) { }
	// RVA: 0x24d81b4 VA: 0x7594af01b4
	public Void .ctor() { }
}
```