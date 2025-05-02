# CrisisV2MapState

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `RectTransform _topMenuContainer`

- `CrisisV2RuneDetailView _runeDetailViewPrefab`

- `RectTransform _runeDetailViewContainer`

- `CrisisV2SlotDetailMapView _slotDetailMapViewPrefab`

- `RectTransform _slotDetaiMapContainer`

- `CrisisV2BagDetailMapView _bagDetailMapViewPrefab`

- `RectTransform _bagDetailMapContainer`

- `CrisisV2MapButtonView _mapButtonView`

- `CrisisV2NodeTipsView _nodeTipsPrefab`

- `RectTransform _nodeTipsContainer`

- `CrisisV2MapAVGAdapter _avgAdapter`

- `GameObject _panelBtnStart`

- `CrisisV2MapNodePreviewView _previewViewPrefab`

- `RectTransform _previewViewContainer`

- `Boolean m_hasIntied`

- `CommonTopMenu m_topMenu`

- `CrisisV2RuneDetailView m_runeDetailView`

- `CrisisV2SlotDetailMapView m_slotDetailMapView`

- `CrisisV2BagDetailMapView m_bagDetailMapView`

- `CrisisV2NodeTipsView m_nodeTipsView`

- `CrisisV2MapNodePreviewView m_previewView`

- `CrisisV2MapStateBean m_stateBean`


## Methods

- `Void _UpdatePreviewIfNeed(CrisisV2MapModel)`

- `Void _InitIfNot()`

- `Void _TriggerTutorialAVG()`

- `Void _TryConsumeGuidebook(Story)`

- `Void _RegisterTutorialGo()`

- `Void _EventOnBack()`

- `Void _EventOnTopMenuRouted(UIRouteTarget, Object, Action`2)`

- `Int32 _TutorialOnly_FocusToSlot(FocusSlotType)`

- `Int32 _TutorialOnly_SwitchMapType(MapType)`

- `Int32 _TutorialOnly_HidePreview()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnBtnDimensionClick()`

- `Void _EventOnOpenBagDetail(String)`

- `Void _EventOnOpenAchieve()`

- `Void _EventOnSkinPreview(String)`

- `Void _EventOnSwitchViewType()`

- `Void _EventOnClearAllNode()`

- `Void _EventOnBagClick(String)`

- `Void _EventOnNodeClick(String)`

- `Void _EventOnClosePreview()`

- `Void _EventOnPreviewSlotClick(Object)`

- `Void _OnNormalNodeClick(CrisisV2MapModel, CrisisV2MapNodeModel)`

- `Void _OnKeypointNodeClick(CrisisV2MapModel, CrisisV2MapNodeModel)`

- `Void _OnTreasureNodeClick(CrisisV2MapModel, CrisisV2MapNodeModel)`

- `Void _GainReward(CrisisV2MapModel, String, CrisisV2MissionType)`

- `Void _ShowGainItems(List`1, Action)`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void _EventRuneDetailSlotItemClickEvent(String)`

- `Void _EventRuneDetailPackItemClickEvent(String)`

- `Void _EventOnJumpComplete(Int32)`

- `Void _EventOnMapSwitchComplete()`

- `Void _EventOnHidePreviewComplete()`

- `Void _EventOnOpenMissionState()`

- `Void _EventOnOpenStageDetailState()`

- `Void EventOnStartBattleClick()`

- `Void _TryJumpToCrisisSquadPage()`

- `Void _DataToMissionState(IStateBean)`

- `Void _DataToStageDetailState(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapState : PopupFadeState, IValueMsgReceiver
{
	private const String GUIDE_BOOK_SUB_SIGNAL; // 0x0
	private RectTransform _topMenuContainer; // 0x70
	private CrisisV2RuneDetailView _runeDetailViewPrefab; // 0x78
	private RectTransform _runeDetailViewContainer; // 0x80
	private CrisisV2SlotDetailMapView _slotDetailMapViewPrefab; // 0x88
	private RectTransform _slotDetaiMapContainer; // 0x90
	private CrisisV2BagDetailMapView _bagDetailMapViewPrefab; // 0x98
	private RectTransform _bagDetailMapContainer; // 0xa0
	private CrisisV2MapButtonView _mapButtonView; // 0xa8
	private CrisisV2NodeTipsView _nodeTipsPrefab; // 0xb0
	private RectTransform _nodeTipsContainer; // 0xb8
	private CrisisV2MapAVGAdapter _avgAdapter; // 0xc0
	private GameObject _panelBtnStart; // 0xc8
	private CrisisV2MapNodePreviewView _previewViewPrefab; // 0xd0
	private RectTransform _previewViewContainer; // 0xd8
	public const Int32 MSG_NODE_CLICK; // 0x0
	public const Int32 MSG_CLEAR_ALL_NODE; // 0x0
	public const Int32 MSG_SWITCH_VIEW; // 0x0
	public const Int32 MSG_BAG_CLICK; // 0x0
	public const Int32 MSG_RUNE_DETAIL_SLOT_ITEM_CLICK; // 0x0
	public const Int32 MSG_RUNE_DETAIL_PACK_ITEM_CLICK; // 0x0
	public const Int32 MSG_ON_JUMP_COMPLETE; // 0x0
	public const Int32 MSG_ON_MAP_SWITCH_COMPLETE; // 0x0
	public const Int32 MSG_OPEN_MISSION_STATE; // 0x0
	public const Int32 MSG_OPEN_STAGE_DETAIL_STATE; // 0x0
	public const Int32 MSG_SKIN_PREVIEW; // 0x0
	public const Int32 MSG_OPEN_ACHIEVE; // 0x0
	public const Int32 MSG_OPEN_BAG_DETAIL; // 0x0
	public const Int32 MSG_CLOSE_PREVIEW; // 0x0
	public const Int32 MSG_PREVIEW_SLOT_CLICKED; // 0x0
	public const Int32 MSG_ON_HIDE_PREVIEW_COMPLETE; // 0x0
	public const Int32 MSG_DIMENSION_BTN_CLICK; // 0x0
	private Boolean m_hasIntied; // 0xe0
	private CommonTopMenu m_topMenu; // 0xe8
	private CrisisV2RuneDetailView m_runeDetailView; // 0xf0
	private CrisisV2SlotDetailMapView m_slotDetailMapView; // 0xf8
	private CrisisV2BagDetailMapView m_bagDetailMapView; // 0x100
	private CrisisV2NodeTipsView m_nodeTipsView; // 0x108
	private CrisisV2MapNodePreviewView m_previewView; // 0x110
	private CrisisV2MapStateBean m_stateBean; // 0x118
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__UpdatePreviewIfNeed; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__TriggerTutorialAVG; // 0x28
	private static DelegateBridge __Hotfix0__TryConsumeGuidebook; // 0x30
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x38
	private static DelegateBridge __Hotfix0__EventOnBack; // 0x40
	private static DelegateBridge __Hotfix0__EventOnTopMenuRouted; // 0x48
	private static DelegateBridge __Hotfix0__TutorialOnly_FocusToSlot; // 0x50
	private static DelegateBridge __Hotfix0__TutorialOnly_SwitchMapType; // 0x58
	private static DelegateBridge __Hotfix0__TutorialOnly_HidePreview; // 0x60
	private static DelegateBridge __Hotfix0_OnMessage; // 0x68
	private static DelegateBridge __Hotfix0__EventOnBtnDimensionClick; // 0x70
	private static DelegateBridge __Hotfix0__EventOnOpenBagDetail; // 0x78
	private static DelegateBridge __Hotfix0__EventOnOpenAchieve; // 0x80
	private static DelegateBridge __Hotfix0__EventOnSkinPreview; // 0x88
	private static DelegateBridge __Hotfix0__EventOnSwitchViewType; // 0x90
	private static DelegateBridge __Hotfix0__EventOnClearAllNode; // 0x98
	private static DelegateBridge __Hotfix0__EventOnBagClick; // 0xa0
	private static DelegateBridge __Hotfix0__EventOnNodeClick; // 0xa8
	private static DelegateBridge __Hotfix0__EventOnClosePreview; // 0xb0
	private static DelegateBridge __Hotfix0__EventOnPreviewSlotClick; // 0xb8
	private static DelegateBridge __Hotfix0__OnNormalNodeClick; // 0xc0
	private static DelegateBridge __Hotfix0__OnKeypointNodeClick; // 0xc8
	private static DelegateBridge __Hotfix0__OnTreasureNodeClick; // 0xd0
	private static DelegateBridge __Hotfix0__GainReward; // 0xd8
	private static DelegateBridge __Hotfix0__ShowGainItems; // 0xe0
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0xe8
	private static DelegateBridge __Hotfix0__EventRuneDetailSlotItemClickEvent; // 0xf0
	private static DelegateBridge __Hotfix0__EventRuneDetailPackItemClickEvent; // 0xf8
	private static DelegateBridge __Hotfix0__EventOnJumpComplete; // 0x100
	private static DelegateBridge __Hotfix0__EventOnMapSwitchComplete; // 0x108
	private static DelegateBridge __Hotfix0__EventOnHidePreviewComplete; // 0x110
	private static DelegateBridge __Hotfix0__EventOnOpenMissionState; // 0x118
	private static DelegateBridge __Hotfix0__EventOnOpenStageDetailState; // 0x120
	private static DelegateBridge __Hotfix0_EventOnStartBattleClick; // 0x128
	private static DelegateBridge __Hotfix0__TryJumpToCrisisSquadPage; // 0x130
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x138
	private static DelegateBridge __Hotfix0__DataToMissionState; // 0x140
	private static DelegateBridge __Hotfix0__DataToStageDetailState; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150


	// RVA: 0x2bdacdc VA: 0x75951f2cdc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2bdad44 VA: 0x75951f2d44
	protected override Void OnEnter() { }
	// RVA: 0x2bdb560 VA: 0x75951f3560
	protected override Void OnResume() { }
	// RVA: 0x2bdb8dc VA: 0x75951f38dc
	private Void _UpdatePreviewIfNeed(CrisisV2MapModel mapModel) { }
	// RVA: 0x2bdae3c VA: 0x75951f2e3c
	private Void _InitIfNot() { }
	// RVA: 0x2bdb36c VA: 0x75951f336c
	private Void _TriggerTutorialAVG() { }
	// RVA: 0x2bdb800 VA: 0x75951f3800
	private Void _TryConsumeGuidebook(Story story) { }
	// RVA: 0x2bdb680 VA: 0x75951f3680
	private Void _RegisterTutorialGo() { }
	// RVA: 0x2bdba60 VA: 0x75951f3a60
	private Void _EventOnBack() { }
	// RVA: 0x2bdbb60 VA: 0x75951f3b60
	private Void _EventOnTopMenuRouted(UIRouteTarget routeTarget, Object param, Action`2 baseHandler) { }
	// RVA: 0x2bdbc40 VA: 0x75951f3c40
	private Int32 _TutorialOnly_FocusToSlot(FocusSlotType slotType) { }
	// RVA: 0x2bdbdd0 VA: 0x75951f3dd0
	private Int32 _TutorialOnly_SwitchMapType(MapType mapType) { }
	// RVA: 0x2bdbedc VA: 0x75951f3edc
	private Int32 _TutorialOnly_HidePreview() { }
	// RVA: 0x2bdbfbc VA: 0x75951f3fbc
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2bdd864 VA: 0x75951f5864
	private Void _EventOnBtnDimensionClick() { }
	// RVA: 0x2bdd3e8 VA: 0x75951f53e8
	private Void _EventOnOpenBagDetail(String bagId) { }
	// RVA: 0x2bdd2c8 VA: 0x75951f52c8
	private Void _EventOnOpenAchieve() { }
	// RVA: 0x2bdd0c8 VA: 0x75951f50c8
	private Void _EventOnSkinPreview(String nodeId) { }
	// RVA: 0x2bdc454 VA: 0x75951f4454
	private Void _EventOnSwitchViewType() { }
	// RVA: 0x2bdc384 VA: 0x75951f4384
	private Void _EventOnClearAllNode() { }
	// RVA: 0x2bdc5bc VA: 0x75951f45bc
	private Void _EventOnBagClick(String bagId) { }
	// RVA: 0x2bdc21c VA: 0x75951f421c
	private Void _EventOnNodeClick(String nodeId) { }
	// RVA: 0x2bdd57c VA: 0x75951f557c
	private Void _EventOnClosePreview() { }
	// RVA: 0x2bdd6f8 VA: 0x75951f56f8
	private Void _EventOnPreviewSlotClick(Object msgObj) { }
	// RVA: 0x2bdd9e0 VA: 0x75951f59e0
	private Void _OnNormalNodeClick(CrisisV2MapModel mapModel, CrisisV2MapNodeModel nodeModel) { }
	// RVA: 0x2bddd7c VA: 0x75951f5d7c
	private Void _OnKeypointNodeClick(CrisisV2MapModel mapModel, CrisisV2MapNodeModel nodeModel) { }
	// RVA: 0x2bddf98 VA: 0x75951f5f98
	private Void _OnTreasureNodeClick(CrisisV2MapModel mapModel, CrisisV2MapNodeModel nodeModel) { }
	// RVA: 0x2bde1b4 VA: 0x75951f61b4
	private Void _GainReward(CrisisV2MapModel mapModel, String nodeId, CrisisV2MissionType missionType) { }
	// RVA: 0x2bde608 VA: 0x75951f6608
	private Void _ShowGainItems(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x2bde708 VA: 0x75951f6708
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x2bdc8c4 VA: 0x75951f48c4
	private Void _EventRuneDetailSlotItemClickEvent(String slotId) { }
	// RVA: 0x2bdc9dc VA: 0x75951f49dc
	private Void _EventRuneDetailPackItemClickEvent(String bagId) { }
	// RVA: 0x2bdcaf4 VA: 0x75951f4af4
	private Void _EventOnJumpComplete(Int32 seqNum) { }
	// RVA: 0x2bdcb80 VA: 0x75951f4b80
	private Void _EventOnMapSwitchComplete() { }
	// RVA: 0x2bdcc38 VA: 0x75951f4c38
	private Void _EventOnHidePreviewComplete() { }
	// RVA: 0x2bdccf0 VA: 0x75951f4cf0
	private Void _EventOnOpenMissionState() { }
	// RVA: 0x2bdcedc VA: 0x75951f4edc
	private Void _EventOnOpenStageDetailState() { }
	// RVA: 0x2bde808 VA: 0x75951f6808
	public Void EventOnStartBattleClick() { }
	// RVA: 0x2bde870 VA: 0x75951f6870
	private Void _TryJumpToCrisisSquadPage() { }
	// RVA: 0x2bdebe0 VA: 0x75951f6be0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2bdedd4 VA: 0x75951f6dd4
	private Void _DataToMissionState(IStateBean stateBean) { }
	// RVA: 0x2bdeebc VA: 0x75951f6ebc
	private Void _DataToStageDetailState(IStateBean stateBean) { }
	// RVA: 0x2bdefa4 VA: 0x75951f6fa4
	public Void .ctor() { }
	// RVA: 0x2bdf054 VA: 0x75951f7054
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2bdf05c VA: 0x75951f705c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2bdf064 VA: 0x75951f7064
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```