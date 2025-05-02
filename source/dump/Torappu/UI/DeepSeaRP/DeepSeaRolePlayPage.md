# DeepSeaRolePlayPage

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `DeepSeaRPZoneMapContainer _mapContainer`

- `RectTransform _topMenuContainer`

- `RectTransform _mapBarContainer`

- `DeepSeaLandmarkNotify _landmarkNotify`

- `UIAnimationLocation _toolbarAnim`

- `CanvasGroup _mapSwitchCanvasGroup`

- `UIAnimationLocation _mapSwitchEnterAnim`

- `Single _mapUpdateDelay`

- `UICommonPageEffectHolder _zoneEffect`

- `Boolean m_hasInited`

- `DeepSeaRPProperty m_property`

- `AnimationSwitchTween m_toolbarSwitchTween`

- `DeepSeaRPZoneBarContainer m_bar`

- `Boolean m_showBattlePreview`


## Properties

- `Boolean isRetro`

- `Boolean isTechTreeNodesAllLock`

- `String selectedZoneId`

- `String selectedPlaceId`

- `String groupId`


## Methods

- `Boolean get_isRetro()`

- `Boolean get_isTechTreeNodesAllLock()`

- `String get_selectedZoneId()`

- `String get_selectedPlaceId()`

- `String get_groupId()`

- `Void StartAvgAndBackToDeepSea(StoryData, String, Boolean)`

- `Void _InitDeepSeaProp()`

- `Void _InitMapBar()`

- `IEnumerator _AddBattlePreviewState()`

- `Void _InitIfNot()`

- `CommonTopMenu _CreateCommonTopMenu(RectTransform, Action)`

- `Void _OnBackAction()`

- `Void _OnNodeClick(String, String)`

- `Void _OnPlaceDiscover(String)`

- `Void _OnShopClick()`

- `Void _OnArchiveClick()`

- `Void _OnTechDetailClick()`

- `Void _OnMissionAimClick(String)`

- `Void _OnZoneSwitchClick()`

- `Void UpdateDeepSeaStatus()`

- `Void FocusOnPlace(String)`

- `Void TryActivateNode(String, String, Action)`

- `Void TryReadEvent(String, String, String, Action)`

- `Void TryOpenTreasure(String, String, String, Action`1)`

- `Void TryUnlockTech(String, String, String, Action)`

- `Void TryReadStory(String, String, String, Action)`

- `Void TrySelectChoice(String, String, Int32, Action)`

- `DeepSeaRPNodeModel GetSelectedNodeModel()`

- `DeepSeaRPPlaceModel GetSelectedPlaceModel()`

- `EventData GetSelectedLockEventData()`

- `Void SetToolbarVisible(Boolean)`

- `Void SelectZone(String)`

- `IEnumerator _SwitchZoneWithAnim(String)`

- `Void HandlePushMsg(DeepSeaLandmarkPushMessage)`

- `IEnumerator <>n__0(Boolean)`

- `IEnumerator <>n__1()`

- `Void <_OnNodeClick>b__42_0()`

- `Void <_OnPlaceDiscover>b__43_0(DeepSeaDiscoverPlaceResponse)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`

- `Void <>xLuaBaseProxy_DisplayWholePage(Boolean)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRolePlayPage : StateEnginePage
{
	public const String KEY_PARAM_BUNDLE; // 0x0
	private DeepSeaRPZoneMapContainer _mapContainer; // 0xe8
	private RectTransform _topMenuContainer; // 0xf0
	private RectTransform _mapBarContainer; // 0xf8
	private DeepSeaLandmarkNotify _landmarkNotify; // 0x100
	private UIAnimationLocation _toolbarAnim; // 0x108
	private CanvasGroup _mapSwitchCanvasGroup; // 0x118
	private UIAnimationLocation _mapSwitchEnterAnim; // 0x120
	private Single _mapUpdateDelay; // 0x130
	private UICommonPageEffectHolder _zoneEffect; // 0x138
	private Boolean m_hasInited; // 0x140
	private DeepSeaRPProperty m_property; // 0x148
	private AnimationSwitchTween m_toolbarSwitchTween; // 0x150
	private DeepSeaRPZoneBarContainer m_bar; // 0x158
	private Boolean m_showBattlePreview; // 0x160
	private static DelegateBridge __Hotfix0_get_isRetro; // 0x0
	private static DelegateBridge __Hotfix0_get_isTechTreeNodesAllLock; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedZoneId; // 0x10
	private static DelegateBridge __Hotfix0_get_selectedPlaceId; // 0x18
	private static DelegateBridge __Hotfix0_get_groupId; // 0x20
	private static DelegateBridge __Hotfix0_get_zoneMapModelList; // 0x28
	private static DelegateBridge __Hotfix0_OnStart; // 0x30
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x38
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x40
	private static DelegateBridge __Hotfix0_DisplayWholePage; // 0x48
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x50
	private static DelegateBridge __Hotfix0_StartAvgAndBackToDeepSea; // 0x58
	private static DelegateBridge __Hotfix0__InitDeepSeaProp; // 0x60
	private static DelegateBridge __Hotfix0__InitMapBar; // 0x68
	private static DelegateBridge __Hotfix0__AddBattlePreviewState; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge __Hotfix0__CreateCommonTopMenu; // 0x80
	private static DelegateBridge __Hotfix0__OnBackAction; // 0x88
	private static DelegateBridge __Hotfix0_GenPageStackToJumpBack; // 0x90
	private static DelegateBridge __Hotfix0_SaveParamToBundle; // 0x98
	private static DelegateBridge __Hotfix0__OnNodeClick; // 0xa0
	private static DelegateBridge __Hotfix0__OnPlaceDiscover; // 0xa8
	private static DelegateBridge __Hotfix0__OnShopClick; // 0xb0
	private static DelegateBridge __Hotfix0__OnArchiveClick; // 0xb8
	private static DelegateBridge __Hotfix0__OnTechDetailClick; // 0xc0
	private static DelegateBridge __Hotfix0__OnMissionAimClick; // 0xc8
	private static DelegateBridge __Hotfix0__OnZoneSwitchClick; // 0xd0
	private static DelegateBridge __Hotfix0_UpdateDeepSeaStatus; // 0xd8
	private static DelegateBridge __Hotfix0_FocusOnPlace; // 0xe0
	private static DelegateBridge __Hotfix0_TryActivateNode; // 0xe8
	private static DelegateBridge __Hotfix0_TryReadEvent; // 0xf0
	private static DelegateBridge __Hotfix0_TryOpenTreasure; // 0xf8
	private static DelegateBridge __Hotfix0_TryUnlockTech; // 0x100
	private static DelegateBridge __Hotfix0_TryReadStory; // 0x108
	private static DelegateBridge __Hotfix0_TrySelectChoice; // 0x110
	private static DelegateBridge __Hotfix0_GetSelectedNodeModel; // 0x118
	private static DelegateBridge __Hotfix0_GetSelectedPlaceModel; // 0x120
	private static DelegateBridge __Hotfix0_GetSelectedLockEventData; // 0x128
	private static DelegateBridge __Hotfix0_SetToolbarVisible; // 0x130
	private static DelegateBridge __Hotfix0_SelectZone; // 0x138
	private static DelegateBridge __Hotfix0__SwitchZoneWithAnim; // 0x140
	private static DelegateBridge __Hotfix0_HandlePushMsg; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public Boolean isRetro { get; }
	public Boolean isTechTreeNodesAllLock { get; }
	public String selectedZoneId { get; }
	public String selectedPlaceId { get; }
	public String groupId { get; }
	public List`1 zoneMapModelList { get; }

	// RVA: 0x29c0ef0 VA: 0x7594fd8ef0
	public Boolean get_isRetro() { }
	// RVA: 0x29c10d8 VA: 0x7594fd90d8
	public Boolean get_isTechTreeNodesAllLock() { }
	// RVA: 0x29c0f84 VA: 0x7594fd8f84
	public String get_selectedZoneId() { }
	// RVA: 0x29c2434 VA: 0x7594fda434
	public String get_selectedPlaceId() { }
	// RVA: 0x29c0e5c VA: 0x7594fd8e5c
	public String get_groupId() { }
	// RVA: 0x29c24c8 VA: 0x7594fda4c8
	public List`1 get_zoneMapModelList() { }
	// RVA: 0x29c255c VA: 0x7594fda55c
	protected override Void OnStart() { }
	// RVA: 0x29c28ec VA: 0x7594fda8ec
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x29c29dc VA: 0x7594fda9dc
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x29c2a84 VA: 0x7594fdaa84
	public override Void DisplayWholePage(Boolean isShow) { }
	// RVA: 0x29c2b40 VA: 0x7594fdab40
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x29bfc9c VA: 0x7594fd7c9c
	public Void StartAvgAndBackToDeepSea(StoryData targetStory, String placeId, Boolean showNodeDetail) { }
	// RVA: 0x29c2f60 VA: 0x7594fdaf60
	private Void _InitDeepSeaProp() { }
	// RVA: 0x29c318c VA: 0x7594fdb18c
	private Void _InitMapBar() { }
	// RVA: 0x29c3598 VA: 0x7594fdb598
	private IEnumerator _AddBattlePreviewState() { }
	// RVA: 0x29c267c VA: 0x7594fda67c
	private Void _InitIfNot() { }
	// RVA: 0x29c366c VA: 0x7594fdb66c
	private CommonTopMenu _CreateCommonTopMenu(RectTransform container, Action onBackClick) { }
	// RVA: 0x29c37ec VA: 0x7594fdb7ec
	private Void _OnBackAction() { }
	// RVA: 0x29c2c14 VA: 0x7594fdac14
	public static List`1 GenPageStackToJumpBack(DataBundle stageBundle, Params param) { }
	// RVA: 0x29c1018 VA: 0x7594fd9018
	public static Void SaveParamToBundle(Params param, DataBundle targetBundle) { }
	// RVA: 0x29c38ec VA: 0x7594fdb8ec
	private Void _OnNodeClick(String placeId, String nodeId) { }
	// RVA: 0x29c3f44 VA: 0x7594fdbf44
	private Void _OnPlaceDiscover(String placeId) { }
	// RVA: 0x29c4240 VA: 0x7594fdc240
	private Void _OnShopClick() { }
	// RVA: 0x29c43a4 VA: 0x7594fdc3a4
	private Void _OnArchiveClick() { }
	// RVA: 0x29c4524 VA: 0x7594fdc524
	private Void _OnTechDetailClick() { }
	// RVA: 0x29c4640 VA: 0x7594fdc640
	private Void _OnMissionAimClick(String nodeId) { }
	// RVA: 0x29c4800 VA: 0x7594fdc800
	private Void _OnZoneSwitchClick() { }
	// RVA: 0x29c4890 VA: 0x7594fdc890
	public Void UpdateDeepSeaStatus() { }
	// RVA: 0x29c4774 VA: 0x7594fdc774
	public Void FocusOnPlace(String placeId) { }
	// RVA: 0x29bf6a0 VA: 0x7594fd76a0
	public Void TryActivateNode(String placeId, String nodeId, Action onComplete) { }
	// RVA: 0x29c3b98 VA: 0x7594fdbb98
	public Void TryReadEvent(String placeId, String nodeId, String eventId, Action onComplete) { }
	// RVA: 0x29c4c04 VA: 0x7594fdcc04
	public Void TryOpenTreasure(String placeId, String nodeId, String treasureId, Action`1 onComplete) { }
	// RVA: 0x29c4fb8 VA: 0x7594fdcfb8
	public Void TryUnlockTech(String placeId, String nodeId, String techTreeId, Action onComplete) { }
	// RVA: 0x29c5394 VA: 0x7594fdd394
	public Void TryReadStory(String placeId, String nodeId, String storyKey, Action onComplete) { }
	// RVA: 0x29c5748 VA: 0x7594fdd748
	public Void TrySelectChoice(String placeId, String nodeId, Int32 choiceIdx, Action onComplete) { }
	// RVA: 0x29bee28 VA: 0x7594fd6e28
	public DeepSeaRPNodeModel GetSelectedNodeModel() { }
	// RVA: 0x29c5b04 VA: 0x7594fddb04
	public DeepSeaRPPlaceModel GetSelectedPlaceModel() { }
	// RVA: 0x29c5b98 VA: 0x7594fddb98
	public EventData GetSelectedLockEventData() { }
	// RVA: 0x29c5c2c VA: 0x7594fddc2c
	public Void SetToolbarVisible(Boolean isVisible) { }
	// RVA: 0x29c5cc4 VA: 0x7594fddcc4
	public Void SelectZone(String zoneId) { }
	// RVA: 0x29c5d9c VA: 0x7594fddd9c
	private IEnumerator _SwitchZoneWithAnim(String zoneId) { }
	// RVA: 0x29c5e94 VA: 0x7594fdde94
	public Void HandlePushMsg(DeepSeaLandmarkPushMessage msg) { }
	// RVA: 0x29c5ff0 VA: 0x7594fddff0
	public Void .ctor() { }
	// RVA: 0x29c60ac VA: 0x7594fde0ac
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x29c60b8 VA: 0x7594fde0b8
	private IEnumerator <>n__1() { }
	// RVA: 0x29c60c0 VA: 0x7594fde0c0
	private Void <_OnNodeClick>b__42_0() { }
	// RVA: 0x29c6118 VA: 0x7594fde118
	private Void <_OnPlaceDiscover>b__43_0(DeepSeaDiscoverPlaceResponse response) { }
	// RVA: 0x29c611c VA: 0x7594fde11c
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x29c6124 VA: 0x7594fde124
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x29c6130 VA: 0x7594fde130
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
	// RVA: 0x29c613c VA: 0x7594fde13c
	private Void <>xLuaBaseProxy_DisplayWholePage(Boolean P0) { }
	// RVA: 0x29c6148 VA: 0x7594fde148
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```