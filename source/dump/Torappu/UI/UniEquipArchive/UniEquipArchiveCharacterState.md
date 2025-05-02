# UniEquipArchiveCharacterState

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `UniEquipArchiveCharacterView _view`

- `RectTransform _filterContainer`

- `RectTransform _equipFilterContainer`

- `UniEquipArchiveFilterHolder _equipFilterPrefab`

- `Boolean m_isInited`

- `ProfessionFilterHandler m_profFilterHandler`

- `EquipFilterHandler m_equipFilterHandler`

- `UICharacterProfessionFilterHolder m_profFilterHolder`

- `UniEquipArchiveFilterHolder m_equipFilterHolder`

- `UniEquipArchiveCharacterStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnEquipClick(Int32)`

- `Void _OnCharClick(Int32)`

- `Void _OnSortClick(Int32)`

- `Void _OnStarMarkClick(Int32)`

- `Void _UpdateData()`

- `Void _InitView()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveCharacterState : PopupFadeState, IValueMsgReceiver
{
	private UniEquipArchiveCharacterView _view; // 0x70
	private RectTransform _filterContainer; // 0x78
	private RectTransform _equipFilterContainer; // 0x80
	private UniEquipArchiveFilterHolder _equipFilterPrefab; // 0x88
	private Boolean m_isInited; // 0x90
	private ProfessionFilterHandler m_profFilterHandler; // 0x98
	private EquipFilterHandler m_equipFilterHandler; // 0xa0
	private UICharacterProfessionFilterHolder m_profFilterHolder; // 0xa8
	private UniEquipArchiveFilterHolder m_equipFilterHolder; // 0xb0
	private HashSet`1 m_invalidSubProfs; // 0xb8
	private UniEquipArchiveCharacterStateBean m_stateBean; // 0xc0
	public const Int32 ON_EQUIP_CLICK; // 0x0
	public const Int32 ON_CHAR_CLICK; // 0x0
	public const Int32 ON_SORT_CLICK; // 0x0
	public const Int32 ON_STAR_MARK_CLICK; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OnEquipClick; // 0x20
	private static DelegateBridge __Hotfix0__OnCharClick; // 0x28
	private static DelegateBridge __Hotfix0__OnSortClick; // 0x30
	private static DelegateBridge __Hotfix0__OnStarMarkClick; // 0x38
	private static DelegateBridge __Hotfix0__UpdateData; // 0x40
	private static DelegateBridge __Hotfix0__InitView; // 0x48
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x22e5cf8 VA: 0x75948fdcf8
	private Void _InitIfNot() { }
	// RVA: 0x22e60f4 VA: 0x75948fe0f4
	protected override Void OnEnter() { }
	// RVA: 0x22e62fc VA: 0x75948fe2fc
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x22e639c VA: 0x75948fe39c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x22e6518 VA: 0x75948fe518
	private Void _OnEquipClick(Int32 chrInstId) { }
	// RVA: 0x22e6604 VA: 0x75948fe604
	private Void _OnCharClick(Int32 chrInstId) { }
	// RVA: 0x22e6764 VA: 0x75948fe764
	private Void _OnSortClick(Int32 msg) { }
	// RVA: 0x22e6844 VA: 0x75948fe844
	private Void _OnStarMarkClick(Int32 msg) { }
	// RVA: 0x22e61e8 VA: 0x75948fe1e8
	private Void _UpdateData() { }
	// RVA: 0x22e6178 VA: 0x75948fe178
	private Void _InitView() { }
	// RVA: 0x22e6a04 VA: 0x75948fea04
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22e6a6c VA: 0x75948fea6c
	public Void .ctor() { }
	// RVA: 0x22e6c18 VA: 0x75948fec18
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22e6c20 VA: 0x75948fec20
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
}
```