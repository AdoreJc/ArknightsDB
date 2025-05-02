# CampaignPage

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `CampaignWorldView _worldViewPrefab`

- `RectTransform _worldViewContainer`

- `CampaignWorldCameraController _cameraController`

- `Camera _cameraFront`

- `AnimationWrapper _animationWrapper`

- `UIFullScreenImage _panelRaycastBlock`

- `CanvasGroup _fadeFloatPanel`

- `CampaignWorldViewProperty m_worldProperty`

- `CampaignWorldHomeBriefViewProperty m_homeBriefProperty`

- `CampaignFeeViewProperty m_feeProperty`

- `CampaignWorldView m_worldView`

- `Boolean m_isPaused`

- `Tween m_fadeFloatTweener`

- `DataBundle m_savedInst`

- `Boolean <isToZonePage>k__BackingField`


## Properties

- `CampaignWorldViewProperty worldProperty`

- `CampaignWorldHomeBriefViewProperty homeBriefProperty`

- `CampaignFeeViewProperty feeProperty`

- `CampaignWorldViewModel worldModel`

- `Boolean isToZonePage`

- `String zoneIdOnOpen`

- `String stageIdOnOpen`


## Methods

- `CampaignWorldViewProperty get_worldProperty()`

- `CampaignWorldHomeBriefViewProperty get_homeBriefProperty()`

- `CampaignFeeViewProperty get_feeProperty()`

- `CampaignWorldViewModel get_worldModel()`

- `Boolean get_isToZonePage()`

- `Void set_isToZonePage(Boolean)`

- `String get_zoneIdOnOpen()`

- `String get_stageIdOnOpen()`

- `Void _EventOnWorldViewInited()`

- `Void _EventOnZoneClicked(CampaignWorldZoneViewModel)`

- `Void EnableMobileTouch(Boolean)`

- `Void CameraLock(LockSource, Boolean)`

- `Void CameraFocusStage(String, FocusParam)`

- `Void CameraFocusZone(String, FocusParam)`

- `Void CameraResetFocus(Action)`

- `Boolean IsShowResetFocus()`

- `Void UpdateZoneArrow(List`1, RectTransform)`

- `Void PlayRegionFogDisappear()`

- `Void JumpToZonePageOnZoneClicked(String)`

- `Void JumpToZonePageFromMission(String, Boolean)`

- `Void SetShowFadeFloatPanel(Boolean, Single)`

- `Void SetPageRaycastBlock(Boolean)`

- `Void RegisterZoneButtonForAVG(String)`

- `Void UpdateCachedRotateStageId()`

- `Void UpdateCachedBriefId()`

- `IEnumerator _RouteToHomeCoroutine(Boolean)`

- `IEnumerator _RouteToZonePageCoroutine()`

- `IEnumerator _JumpToZonePageCoroutine(String, String, Boolean, Boolean)`

- `Boolean _IsStageInCameraBounds(String)`

- `Boolean _IsZoneInCameraBounds(String)`

- `Vector3 _GetZoneWorldPosition(String)`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnStop()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignPage : StateEnginePage, IMobileTouchPage, IHotfixable
{
	private const String ANIM_WORLD_ENTER; // 0x0
	private const String ANIM_WORLD_FORWARD_TO_ZONE; // 0x0
	private const String ANIM_WORLD_BACK_FROM_ZONE; // 0x0
	private const Single ANIM_WORLD_ENTER_TIME; // 0x0
	private const Single ANIM_FORWARD_TO_TIME; // 0x0
	private const Single ANIM_BACK_FROM_TIME; // 0x0
	private CampaignWorldView _worldViewPrefab; // 0xe8
	private RectTransform _worldViewContainer; // 0xf0
	private CampaignWorldCameraController _cameraController; // 0xf8
	private Camera _cameraFront; // 0x100
	private AnimationWrapper _animationWrapper; // 0x108
	private UIFullScreenImage _panelRaycastBlock; // 0x110
	private CanvasGroup _fadeFloatPanel; // 0x118
	private CampaignWorldViewProperty m_worldProperty; // 0x120
	private CampaignWorldHomeBriefViewProperty m_homeBriefProperty; // 0x128
	private CampaignFeeViewProperty m_feeProperty; // 0x130
	private CampaignWorldView m_worldView; // 0x138
	private Boolean m_isPaused; // 0x140
	private Tween m_fadeFloatTweener; // 0x148
	private DataBundle m_savedInst; // 0x150
	private Boolean <isToZonePage>k__BackingField; // 0x158
	private static DelegateBridge __Hotfix0_get_worldProperty; // 0x0
	private static DelegateBridge __Hotfix0_get_homeBriefProperty; // 0x8
	private static DelegateBridge __Hotfix0_get_feeProperty; // 0x10
	private static DelegateBridge __Hotfix0_get_worldModel; // 0x18
	private static DelegateBridge __Hotfix0_get_isToZonePage; // 0x20
	private static DelegateBridge __Hotfix0_set_isToZonePage; // 0x28
	private static DelegateBridge __Hotfix0_get_zoneIdOnOpen; // 0x30
	private static DelegateBridge __Hotfix0_get_stageIdOnOpen; // 0x38
	private static DelegateBridge __Hotfix0_OnCreate; // 0x40
	private static DelegateBridge __Hotfix0_OnStart; // 0x48
	private static DelegateBridge __Hotfix0_OnStop; // 0x50
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x58
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x60
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x68
	private static DelegateBridge __Hotfix0__EventOnWorldViewInited; // 0x70
	private static DelegateBridge __Hotfix0__EventOnZoneClicked; // 0x78
	private static DelegateBridge __Hotfix0_EnableMobileTouch; // 0x80
	private static DelegateBridge __Hotfix0_CameraLock; // 0x88
	private static DelegateBridge __Hotfix0_CameraFocusStage; // 0x90
	private static DelegateBridge __Hotfix0_CameraFocusZone; // 0x98
	private static DelegateBridge __Hotfix0_CameraResetFocus; // 0xa0
	private static DelegateBridge __Hotfix0_IsShowResetFocus; // 0xa8
	private static DelegateBridge __Hotfix0_UpdateZoneArrow; // 0xb0
	private static DelegateBridge __Hotfix0_PlayRegionFogDisappear; // 0xb8
	private static DelegateBridge __Hotfix0_JumpToZonePageOnZoneClicked; // 0xc0
	private static DelegateBridge __Hotfix0_JumpToZonePageFromMission; // 0xc8
	private static DelegateBridge __Hotfix0_SetShowFadeFloatPanel; // 0xd0
	private static DelegateBridge __Hotfix0_SetPageRaycastBlock; // 0xd8
	private static DelegateBridge __Hotfix0_RegisterZoneButtonForAVG; // 0xe0
	private static DelegateBridge __Hotfix0_UpdateCachedRotateStageId; // 0xe8
	private static DelegateBridge __Hotfix0_UpdateCachedBriefId; // 0xf0
	private static DelegateBridge __Hotfix0__RouteToHomeCoroutine; // 0xf8
	private static DelegateBridge __Hotfix0__RouteToZonePageCoroutine; // 0x100
	private static DelegateBridge __Hotfix0__JumpToZonePageCoroutine; // 0x108
	private static DelegateBridge __Hotfix0__IsStageInCameraBounds; // 0x110
	private static DelegateBridge __Hotfix0__IsZoneInCameraBounds; // 0x118
	private static DelegateBridge __Hotfix0__GetZoneWorldPosition; // 0x120
	private static DelegateBridge __Hotfix0_DataBundleToCampaignZone; // 0x128
	private static DelegateBridge __Hotfix0_SceneParamToCampaign; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138

	public CampaignWorldViewProperty worldProperty { get; }
	public CampaignWorldHomeBriefViewProperty homeBriefProperty { get; }
	public CampaignFeeViewProperty feeProperty { get; }
	public CampaignWorldViewModel worldModel { get; }
	public Boolean isToZonePage { get; set; }
	private String zoneIdOnOpen { get; }
	private String stageIdOnOpen { get; }

	// RVA: 0x2dc8254 VA: 0x75953e0254
	public CampaignWorldViewProperty get_worldProperty() { }
	// RVA: 0x2dc82bc VA: 0x75953e02bc
	public CampaignWorldHomeBriefViewProperty get_homeBriefProperty() { }
	// RVA: 0x2dc8324 VA: 0x75953e0324
	public CampaignFeeViewProperty get_feeProperty() { }
	// RVA: 0x2dc838c VA: 0x75953e038c
	public CampaignWorldViewModel get_worldModel() { }
	// RVA: 0x2dc840c VA: 0x75953e040c
	public Boolean get_isToZonePage() { }
	// RVA: 0x2dc8474 VA: 0x75953e0474
	private Void set_isToZonePage(Boolean value) { }
	// RVA: 0x2dc84f4 VA: 0x75953e04f4
	private String get_zoneIdOnOpen() { }
	// RVA: 0x2dc85d8 VA: 0x75953e05d8
	private String get_stageIdOnOpen() { }
	// RVA: 0x2dc86bc VA: 0x75953e06bc
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2dc898c VA: 0x75953e098c
	protected override Void OnStart() { }
	// RVA: 0x2dc8d00 VA: 0x75953e0d00
	protected override Void OnStop() { }
	// RVA: 0x2dc8d78 VA: 0x75953e0d78
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2dc8e4c VA: 0x75953e0e4c
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x2dc8f3c VA: 0x75953e0f3c
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x2dc902c VA: 0x75953e102c
	private Void _EventOnWorldViewInited() { }
	// RVA: 0x2dc9118 VA: 0x75953e1118
	private Void _EventOnZoneClicked(CampaignWorldZoneViewModel zoneModel) { }
	// RVA: 0x2dc92b0 VA: 0x75953e12b0
	public Void EnableMobileTouch(Boolean enable) { }
	// RVA: 0x2dc88f4 VA: 0x75953e08f4
	public Void CameraLock(LockSource lockSource, Boolean isLock) { }
	// RVA: 0x2dc8b14 VA: 0x75953e0b14
	public Void CameraFocusStage(String stageId, FocusParam param) { }
	// RVA: 0x2dc7680 VA: 0x75953df680
	public Void CameraFocusZone(String zoneId, FocusParam param) { }
	// RVA: 0x2dc9338 VA: 0x75953e1338
	public Void CameraResetFocus(Action onFinished) { }
	// RVA: 0x2dc9428 VA: 0x75953e1428
	public Boolean IsShowResetFocus() { }
	// RVA: 0x2dc9778 VA: 0x75953e1778
	public Void UpdateZoneArrow(List`1 arrows, RectTransform arrowContainer) { }
	// RVA: 0x2dca92c VA: 0x75953e292c
	public Void PlayRegionFogDisappear() { }
	// RVA: 0x2dc9214 VA: 0x75953e1214
	public Void JumpToZonePageOnZoneClicked(String zoneId) { }
	// RVA: 0x2dcab58 VA: 0x75953e2b58
	public Void JumpToZonePageFromMission(String stageId, Boolean isToBreakingDetail) { }
	// RVA: 0x2dcac08 VA: 0x75953e2c08
	public Void SetShowFadeFloatPanel(Boolean isShow, Single duration) { }
	// RVA: 0x2dc75ec VA: 0x75953df5ec
	public Void SetPageRaycastBlock(Boolean flag) { }
	// RVA: 0x2dc7a20 VA: 0x75953dfa20
	public Void RegisterZoneButtonForAVG(String zoneId) { }
	// RVA: 0x2dcae1c VA: 0x75953e2e1c
	public Void UpdateCachedRotateStageId() { }
	// RVA: 0x2dcaf70 VA: 0x75953e2f70
	public Void UpdateCachedBriefId() { }
	// RVA: 0x2dcb0c4 VA: 0x75953e30c4
	private IEnumerator _RouteToHomeCoroutine(Boolean fastMode) { }
	// RVA: 0x2dcb1b4 VA: 0x75953e31b4
	private IEnumerator _RouteToZonePageCoroutine() { }
	// RVA: 0x2dcaa44 VA: 0x75953e2a44
	private IEnumerator _JumpToZonePageCoroutine(String zoneId, String stageId, Boolean isToBreakingDetail, Boolean fastMode) { }
	// RVA: 0x2dc94cc VA: 0x75953e14cc
	private Boolean _IsStageInCameraBounds(String stageId) { }
	// RVA: 0x2dca0a4 VA: 0x75953e20a4
	private Boolean _IsZoneInCameraBounds(String zoneId) { }
	// RVA: 0x2dca648 VA: 0x75953e2648
	private Vector3 _GetZoneWorldPosition(String zoneId) { }
	// RVA: 0x2dcb39c VA: 0x75953e339c
	public static DataBundle DataBundleToCampaignZone(String zoneId, String stageId) { }
	// RVA: 0x2dcb498 VA: 0x75953e3498
	public static UIPageControllerParam SceneParamToCampaign(DataBundle bundleToJumpBack) { }
	// RVA: 0x2dcb834 VA: 0x75953e3834
	public Void .ctor() { }
	// RVA: 0x2dcb95c VA: 0x75953e395c
	private IEnumerator <>n__0() { }
	// RVA: 0x2dcb964 VA: 0x75953e3964
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2dcb96c VA: 0x75953e396c
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x2dcb974 VA: 0x75953e3974
	private Void <>xLuaBaseProxy_OnStop() { }
	// RVA: 0x2dcb97c VA: 0x75953e397c
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2dcb984 VA: 0x75953e3984
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x2dcb990 VA: 0x75953e3990
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```