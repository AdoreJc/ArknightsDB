# SiracusaMapPanelMapViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaMapNavigationViewModel navigationViewModel`

- `SiracusaMapViewModel m_mapViewModel`

- `SiracusaCharCardModel m_charCardModel`

- `String m_groupId`

- `String m_shopId`

- `Boolean m_isRetro`

- `Act21SideData m_actData`

- `SiracusaData m_siracusaData`

- `Int64 m_enterTimeStamp`

- `SiracusaMapFocusPolicy <focusPolicy>k__BackingField`


## Properties

- `String groupId`

- `Boolean isRetro`

- `SiracusaMapViewModel mapViewModel`

- `SiracusaCharCardModel charCardModel`

- `SiracusaMapFocusPolicy focusPolicy`

- `MapState mapState`

- `Boolean isInSmallMapState`


## Methods

- `String get_groupId()`

- `Boolean get_isRetro()`

- `SiracusaMapViewModel get_mapViewModel()`

- `SiracusaCharCardModel get_charCardModel()`

- `SiracusaMapFocusPolicy get_focusPolicy()`

- `Void set_focusPolicy(SiracusaMapFocusPolicy)`

- `MapState get_mapState()`

- `Boolean get_isInSmallMapState()`

- `Boolean NeedShowStagePreview()`

- `Boolean NeedShowStoryPreview()`

- `Boolean IsNavigationCharCard()`

- `Boolean IsNavigationNothing()`

- `Void InitData(Param)`

- `Boolean SelectPoint(String, Boolean)`

- `Void SelectNavi(NavigationType)`

- `Void SelectNavi(String)`

- `Void UnSelectNavi()`

- `Void UpdateCharCardModel()`

- `Void UpdateReviewCharModel(String)`

- `Void UpdateWhenBackToBigMap()`

- `Param GeneRecoverPageParamForStory(String, String)`

- `Param GeneRecoverPageParamForBattle(String)`

- `Void SelectTaskRing(Int32)`

- `String NaviTrySelectDetailStage(String)`

- `DataBundle GeneRecoverPageDataBundleForBattle(String)`

- `Boolean TryToFocusToNewUnlockArea(String)`

- `Void _UpdateData(PlayerSiracusaMap, String)`

- `Void _RebuildNodeViewModel()`

- `NavigationType _GetCurNaviType()`

- `String _GetCurNaviId()`

- `Void _AutoSelectPoint(Param)`

- `String _TryToUpdateNaviIdAndCalcStage(String, String, String)`

- `Boolean _IsNavigationStageLevel()`

- `Boolean _IsNavigationAvg()`

- `Boolean _IsNavigating(NavigationType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapPanelMapViewModel : IHotfixable
{
	public SiracusaMapNavigationViewModel navigationViewModel; // 0x10
	private SiracusaMapViewModel m_mapViewModel; // 0x18
	private SiracusaCharCardModel m_charCardModel; // 0x20
	private String m_groupId; // 0x28
	private String m_shopId; // 0x30
	private Boolean m_isRetro; // 0x38
	private Act21SideData m_actData; // 0x40
	private SiracusaData m_siracusaData; // 0x48
	private Int64 m_enterTimeStamp; // 0x50
	private SiracusaMapFocusPolicy <focusPolicy>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_groupId; // 0x0
	private static DelegateBridge __Hotfix0_get_isRetro; // 0x8
	private static DelegateBridge __Hotfix0_get_mapViewModel; // 0x10
	private static DelegateBridge __Hotfix0_get_charCardModel; // 0x18
	private static DelegateBridge __Hotfix0_get_focusPolicy; // 0x20
	private static DelegateBridge __Hotfix0_set_focusPolicy; // 0x28
	private static DelegateBridge __Hotfix0_get_mapState; // 0x30
	private static DelegateBridge __Hotfix0_get_isInSmallMapState; // 0x38
	private static DelegateBridge __Hotfix0_NeedShowStagePreview; // 0x40
	private static DelegateBridge __Hotfix0_NeedShowStoryPreview; // 0x48
	private static DelegateBridge __Hotfix0_IsNavigationCharCard; // 0x50
	private static DelegateBridge __Hotfix0_IsNavigationNothing; // 0x58
	private static DelegateBridge __Hotfix0_InitData; // 0x60
	private static DelegateBridge __Hotfix0_SelectPoint; // 0x68
	private static DelegateBridge __Hotfix0_SelectNavi; // 0x70
	private static DelegateBridge __Hotfix1_SelectNavi; // 0x78
	private static DelegateBridge __Hotfix0_UnSelectNavi; // 0x80
	private static DelegateBridge __Hotfix0_UpdateCharCardModel; // 0x88
	private static DelegateBridge __Hotfix0_UpdateReviewCharModel; // 0x90
	private static DelegateBridge __Hotfix0_UpdateWhenBackToBigMap; // 0x98
	private static DelegateBridge __Hotfix0_GeneRecoverPageParamForStory; // 0xa0
	private static DelegateBridge __Hotfix0_GeneRecoverPageParamForBattle; // 0xa8
	private static DelegateBridge __Hotfix0_SelectTaskRing; // 0xb0
	private static DelegateBridge __Hotfix0_NaviTrySelectDetailStage; // 0xb8
	private static DelegateBridge __Hotfix0_GeneRecoverPageDataBundleForBattle; // 0xc0
	private static DelegateBridge __Hotfix0_TryToFocusToNewUnlockArea; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateData; // 0xd0
	private static DelegateBridge __Hotfix0__RebuildNodeViewModel; // 0xd8
	private static DelegateBridge __Hotfix0__GetCurNaviType; // 0xe0
	private static DelegateBridge __Hotfix0__GetCurNaviId; // 0xe8
	private static DelegateBridge __Hotfix0__AutoSelectPoint; // 0xf0
	private static DelegateBridge __Hotfix0__TryToUpdateNaviIdAndCalcStage; // 0xf8
	private static DelegateBridge __Hotfix0__IsNavigationStageLevel; // 0x100
	private static DelegateBridge __Hotfix0__IsNavigationAvg; // 0x108
	private static DelegateBridge __Hotfix0__IsNavigating; // 0x110
	private static DelegateBridge __Hotfix0_GetGroupIdByZoneId; // 0x118
	private static DelegateBridge _c__Hotfix0_ctor; // 0x120

	public String groupId { get; }
	public Boolean isRetro { get; }
	public SiracusaMapViewModel mapViewModel { get; }
	public SiracusaCharCardModel charCardModel { get; }
	public SiracusaMapFocusPolicy focusPolicy { get; set; }
	public MapState mapState { get; }
	public Boolean isInSmallMapState { get; }

	// RVA: 0x24131ac VA: 0x7594a2b1ac
	public String get_groupId() { }
	// RVA: 0x2413144 VA: 0x7594a2b144
	public Boolean get_isRetro() { }
	// RVA: 0x2413064 VA: 0x7594a2b064
	public SiracusaMapViewModel get_mapViewModel() { }
	// RVA: 0x241767c VA: 0x7594a2f67c
	public SiracusaCharCardModel get_charCardModel() { }
	// RVA: 0x24176e4 VA: 0x7594a2f6e4
	public SiracusaMapFocusPolicy get_focusPolicy() { }
	// RVA: 0x2417784 VA: 0x7594a2f784
	private Void set_focusPolicy(SiracusaMapFocusPolicy value) { }
	// RVA: 0x24130cc VA: 0x7594a2b0cc
	public MapState get_mapState() { }
	// RVA: 0x24178c4 VA: 0x7594a2f8c4
	public Boolean get_isInSmallMapState() { }
	// RVA: 0x2417938 VA: 0x7594a2f938
	public Boolean NeedShowStagePreview() { }
	// RVA: 0x2417b90 VA: 0x7594a2fb90
	public Boolean NeedShowStoryPreview() { }
	// RVA: 0x2417cd4 VA: 0x7594a2fcd4
	public Boolean IsNavigationCharCard() { }
	// RVA: 0x2417de0 VA: 0x7594a2fde0
	public Boolean IsNavigationNothing() { }
	// RVA: 0x2417e60 VA: 0x7594a2fe60
	public Void InitData(Param pageParam) { }
	// RVA: 0x24185f4 VA: 0x7594a305f4
	public Boolean SelectPoint(String pointId, Boolean needChangeNodeShowSelected) { }
	// RVA: 0x24187e8 VA: 0x7594a307e8
	public Void SelectNavi(NavigationType type) { }
	// RVA: 0x241888c VA: 0x7594a3088c
	public Void SelectNavi(String entryId) { }
	// RVA: 0x2418be8 VA: 0x7594a30be8
	public Void UnSelectNavi() { }
	// RVA: 0x2418c70 VA: 0x7594a30c70
	public Void UpdateCharCardModel() { }
	// RVA: 0x2418d54 VA: 0x7594a30d54
	public Void UpdateReviewCharModel(String charCardId) { }
	// RVA: 0x2418e14 VA: 0x7594a30e14
	public Void UpdateWhenBackToBigMap() { }
	// RVA: 0x2418ed8 VA: 0x7594a30ed8
	public Param GeneRecoverPageParamForStory(String storyId, String pointId) { }
	// RVA: 0x2419068 VA: 0x7594a31068
	public Param GeneRecoverPageParamForBattle(String pointId) { }
	// RVA: 0x2419154 VA: 0x7594a31154
	public Void SelectTaskRing(Int32 index) { }
	// RVA: 0x2419254 VA: 0x7594a31254
	public String NaviTrySelectDetailStage(String keyId) { }
	// RVA: 0x241932c VA: 0x7594a3132c
	public DataBundle GeneRecoverPageDataBundleForBattle(String pointId) { }
	// RVA: 0x24193fc VA: 0x7594a313fc
	public Boolean TryToFocusToNewUnlockArea(String areaId) { }
	// RVA: 0x24183c0 VA: 0x7594a303c0
	private Void _UpdateData(PlayerSiracusaMap playerSiracusa, String initSelectingStageKey) { }
	// RVA: 0x24189c0 VA: 0x7594a309c0
	private Void _RebuildNodeViewModel() { }
	// RVA: 0x2417838 VA: 0x7594a2f838
	private NavigationType _GetCurNaviType() { }
	// RVA: 0x2418ff4 VA: 0x7594a30ff4
	private String _GetCurNaviId() { }
	// RVA: 0x2418480 VA: 0x7594a30480
	private Void _AutoSelectPoint(Param pageParam) { }
	// RVA: 0x24182ec VA: 0x7594a302ec
	private String _TryToUpdateNaviIdAndCalcStage(String naviId, String stageId, String storyId) { }
	// RVA: 0x2417b24 VA: 0x7594a2fb24
	private Boolean _IsNavigationStageLevel() { }
	// RVA: 0x2417c68 VA: 0x7594a2fc68
	private Boolean _IsNavigationAvg() { }
	// RVA: 0x2417d40 VA: 0x7594a2fd40
	private Boolean _IsNavigating(NavigationType type) { }
	// RVA: 0x2419aac VA: 0x7594a31aac
	public static String GetGroupIdByZoneId(String zoneId, Boolean isRetro) { }
	// RVA: 0x2419c70 VA: 0x7594a31c70
	public Void .ctor() { }
}
```