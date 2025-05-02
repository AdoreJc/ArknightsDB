# UniEquipArchiveModuleListState

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `UniEquipArchiveModuleCollectionView _view`

- `RectTransform _equipOwnFilterContainer`

- `UniEquipArchiveFilterHolder _equipOwnFilterPrefab`

- `RectTransform _equipTypeFilterContainer`

- `UniEquipArchiveEquipTypeFilterHolder _equipTypeFilterPrefab`

- `Boolean m_isInited`

- `EquipOwnFilterHandler m_equipOwnFilterHandler`

- `UniEquipArchiveFilterHolder m_equipOwnFilterHolder`

- `EquipTypeFilterHandler m_equipTypeFilterHandler`

- `UniEquipArchiveEquipTypeFilterHolder m_equipTypeFilterHolder`

- `UniEquipArchiveModuleCollectionStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _LoadData()`

- `Void _UpdateData()`

- `Void _InitView()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnEquipItemClick(String)`

- `Void _OnEquipCharPartClick(String)`

- `Void _OnSortClick(Int32)`

- `Void _OnTypeFilterClick()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveModuleListState : PopupFadeState, IValueMsgReceiver
{
	private UniEquipArchiveModuleCollectionView _view; // 0x70
	private RectTransform _equipOwnFilterContainer; // 0x78
	private UniEquipArchiveFilterHolder _equipOwnFilterPrefab; // 0x80
	private RectTransform _equipTypeFilterContainer; // 0x88
	private UniEquipArchiveEquipTypeFilterHolder _equipTypeFilterPrefab; // 0x90
	private Boolean m_isInited; // 0x98
	private EquipOwnFilterHandler m_equipOwnFilterHandler; // 0xa0
	private UniEquipArchiveFilterHolder m_equipOwnFilterHolder; // 0xa8
	private EquipTypeFilterHandler m_equipTypeFilterHandler; // 0xb0
	private UniEquipArchiveEquipTypeFilterHolder m_equipTypeFilterHolder; // 0xb8
	private UniEquipArchiveModuleCollectionStateBean m_stateBean; // 0xc0
	public const Int32 ON_EQUIP_ITEM_CLICK; // 0x0
	public const Int32 ON_EQUIP_ITEM_CHAR_PART_CLICK; // 0x0
	public const Int32 ON_SORT_CLICK; // 0x0
	public const Int32 ON_TYPE_FILTER_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x18
	private static DelegateBridge __Hotfix0__LoadData; // 0x20
	private static DelegateBridge __Hotfix0__UpdateData; // 0x28
	private static DelegateBridge __Hotfix0__InitView; // 0x30
	private static DelegateBridge __Hotfix0_OnMessage; // 0x38
	private static DelegateBridge __Hotfix0__OnEquipItemClick; // 0x40
	private static DelegateBridge __Hotfix0__OnEquipCharPartClick; // 0x48
	private static DelegateBridge __Hotfix0__OnSortClick; // 0x50
	private static DelegateBridge __Hotfix0__OnTypeFilterClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x22e7e3c VA: 0x75948ffe3c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22e7ea4 VA: 0x75948ffea4
	private Void _InitIfNot() { }
	// RVA: 0x22e8270 VA: 0x7594900270
	protected override Void OnEnter() { }
	// RVA: 0x22e84f0 VA: 0x75949004f0
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x22e8370 VA: 0x7594900370
	private Void _LoadData() { }
	// RVA: 0x22e8418 VA: 0x7594900418
	private Void _UpdateData() { }
	// RVA: 0x22e82fc VA: 0x75949002fc
	private Void _InitView() { }
	// RVA: 0x22e8590 VA: 0x7594900590
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x22e86a4 VA: 0x75949006a4
	private Void _OnEquipItemClick(String msg) { }
	// RVA: 0x22e884c VA: 0x759490084c
	private Void _OnEquipCharPartClick(String msg) { }
	// RVA: 0x22e897c VA: 0x759490097c
	private Void _OnSortClick(Int32 msg) { }
	// RVA: 0x22e8a60 VA: 0x7594900a60
	private Void _OnTypeFilterClick() { }
	// RVA: 0x22e8ad0 VA: 0x7594900ad0
	public Void .ctor() { }
	// RVA: 0x22e8c2c VA: 0x7594900c2c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22e8c34 VA: 0x7594900c34
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
}
```