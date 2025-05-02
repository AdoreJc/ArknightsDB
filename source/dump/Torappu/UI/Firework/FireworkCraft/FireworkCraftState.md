# FireworkCraftState

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `RectTransform _topMenuHolder`

- `FireworkCraftView _view`

- `Boolean m_inited`

- `FireworkCraftProperty m_property`

- `Int32 m_cachedAddPieceSeqNum`

- `Int32 m_cachedRemovePieceSeqNum`


## Methods

- `Void _InitIfNot()`

- `Void _OnJumpToAnimalSelectState(IStateBean)`

- `Void _EventOnBackBtnClicked()`

- `Void _TryTriggerTutorialAVG()`

- `Boolean TutorialOnly_IsStable()`

- `Void TutorialOnly_RegisterTutorialGo()`

- `Boolean _IsUIStable()`

- `Void _OnViewStateChanged(Int32)`

- `Void _OnStageClicked(String)`

- `Void _OnZoneClicked(String)`

- `Void _OnPlateListItemClicked(String)`

- `Void _OnPlateListSubItemClicked(PlateSlotData)`

- `Void _OnPlateListFilledItemClicked(PlateSlotData)`

- `Void _OnPnlSubListRaycastClicked()`

- `Void _OnClearAllBtnClicked()`

- `Void _OnAnimalSwitchClicked()`

- `Void _OnBtnSaveClicked()`

- `Void _OnBtnSaveResponse(FireworkSavePlateSlotResponse)`

- `Void _OpenGuideBook(Story)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftState : FireworkBaseState
{
	private const String GUIDE_SUB_SIGNAL; // 0x0
	public const Int32 ON_VIEW_STATE_CHANGED; // 0x0
	public const Int32 ON_STAGE_CLICKED; // 0x0
	public const Int32 ON_ZONE_CLICKED; // 0x0
	public const Int32 ON_ANIMAL_SWITCH_CLICKED; // 0x0
	public const Int32 ON_BTN_SAVE_CLICKED; // 0x0
	private RectTransform _topMenuHolder; // 0x70
	private FireworkCraftView _view; // 0x78
	private Boolean m_inited; // 0x80
	private FireworkCraftProperty m_property; // 0x88
	private List`1 m_cacheSlotList; // 0x90
	private Int32 m_cachedAddPieceSeqNum; // 0x98
	private Int32 m_cachedRemovePieceSeqNum; // 0x9c
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToAnimalSelectState; // 0x28
	private static DelegateBridge __Hotfix0__EventOnBackBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__TryTriggerTutorialAVG; // 0x38
	private static DelegateBridge __Hotfix0_TutorialOnly_IsStable; // 0x40
	private static DelegateBridge __Hotfix0_TutorialOnly_RegisterTutorialGo; // 0x48
	private static DelegateBridge __Hotfix0_OnMessage; // 0x50
	private static DelegateBridge __Hotfix0__IsUIStable; // 0x58
	private static DelegateBridge __Hotfix0__OnViewStateChanged; // 0x60
	private static DelegateBridge __Hotfix0__OnStageClicked; // 0x68
	private static DelegateBridge __Hotfix0__OnZoneClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnPlateListItemClicked; // 0x78
	private static DelegateBridge __Hotfix0__OnPlateListSubItemClicked; // 0x80
	private static DelegateBridge __Hotfix0__OnPlateListFilledItemClicked; // 0x88
	private static DelegateBridge __Hotfix0__OnPnlSubListRaycastClicked; // 0x90
	private static DelegateBridge __Hotfix0__OnClearAllBtnClicked; // 0x98
	private static DelegateBridge __Hotfix0__OnAnimalSwitchClicked; // 0xa0
	private static DelegateBridge __Hotfix0__OnBtnSaveClicked; // 0xa8
	private static DelegateBridge __Hotfix0__OnBtnSaveResponse; // 0xb0
	private static DelegateBridge __Hotfix0__OpenGuideBook; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0


	// RVA: 0x2905eb8 VA: 0x7594f1deb8
	private Void _InitIfNot() { }
	// RVA: 0x2905fb8 VA: 0x7594f1dfb8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x290601c VA: 0x7594f1e01c
	protected override Void OnEnter() { }
	// RVA: 0x2906368 VA: 0x7594f1e368
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x2906454 VA: 0x7594f1e454
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x29065cc VA: 0x7594f1e5cc
	private Void _OnJumpToAnimalSelectState(IStateBean stateBean) { }
	// RVA: 0x29066d4 VA: 0x7594f1e6d4
	private Void _EventOnBackBtnClicked() { }
	// RVA: 0x290621c VA: 0x7594f1e21c
	private Void _TryTriggerTutorialAVG() { }
	// RVA: 0x29038b4 VA: 0x7594f1b8b4
	public Boolean TutorialOnly_IsStable() { }
	// RVA: 0x29039f8 VA: 0x7594f1b9f8
	public Void TutorialOnly_RegisterTutorialGo() { }
	// RVA: 0x2906d0c VA: 0x7594f1ed0c
	public override Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2907c70 VA: 0x7594f1fc70
	private Boolean _IsUIStable() { }
	// RVA: 0x2906f8c VA: 0x7594f1ef8c
	private Void _OnViewStateChanged(Int32 status) { }
	// RVA: 0x2907088 VA: 0x7594f1f088
	private Void _OnStageClicked(String stageId) { }
	// RVA: 0x290718c VA: 0x7594f1f18c
	private Void _OnZoneClicked(String zoneId) { }
	// RVA: 0x29072ec VA: 0x7594f1f2ec
	private Void _OnPlateListItemClicked(String groupId) { }
	// RVA: 0x29073f0 VA: 0x7594f1f3f0
	private Void _OnPlateListSubItemClicked(PlateSlotData slotData) { }
	// RVA: 0x29074f4 VA: 0x7594f1f4f4
	private Void _OnPlateListFilledItemClicked(PlateSlotData slotData) { }
	// RVA: 0x29075f8 VA: 0x7594f1f5f8
	private Void _OnPnlSubListRaycastClicked() { }
	// RVA: 0x29076e0 VA: 0x7594f1f6e0
	private Void _OnClearAllBtnClicked() { }
	// RVA: 0x29077c8 VA: 0x7594f1f7c8
	private Void _OnAnimalSwitchClicked() { }
	// RVA: 0x2907954 VA: 0x7594f1f954
	private Void _OnBtnSaveClicked() { }
	// RVA: 0x2907d4c VA: 0x7594f1fd4c
	private Void _OnBtnSaveResponse(FireworkSavePlateSlotResponse response) { }
	// RVA: 0x2907e80 VA: 0x7594f1fe80
	private Void _OpenGuideBook(Story story) { }
	// RVA: 0x2907f1c VA: 0x7594f1ff1c
	public Void .ctor() { }
	// RVA: 0x2908018 VA: 0x7594f20018
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2908020 VA: 0x7594f20020
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x290802c VA: 0x7594f2002c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```