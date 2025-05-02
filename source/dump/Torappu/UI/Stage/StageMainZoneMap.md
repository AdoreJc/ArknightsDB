# StageMainZoneMap

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean _canMapDrag`

- `Boolean _needDrawLines`

- `Boolean _stageBindToBackground`

- `BoundType _boundType`

- `Single _bindBackgroundWidth`

- `StageButtonOnMap _stageButtonProto`

- `Image _backgroundImagePrimary`

- `Image _backgroundImageSecondary`

- `Image _backgroundImageBindToStage`

- `Single _stagePanelMoveSpeed`

- `Single _backgroundMoveSpeed`

- `RectTransform _stagePanel`

- `Single _backgroundFadeDuration`

- `Single _positionValueLimitMinOffset`

- `Single _positionValueLimitMaxOffset`

- `UIImageLine _linePrefab`

- `RectTransform _lineContainer`

- `Boolean _useLockedStagesAsBound`

- `IStageMainZoneMapController m_currentController`

- `Single m_lastPositionValue`

- `Single m_lastImageRefValue`

- `BackgroundSegment m_currentSegment`

- `Tween m_currentTween`

- `Single m_primaryBaseLine`

- `Single m_secondaryBaseLine`

- `Single m_bindBgBaseLine`

- `Single m_positionLimitMin`

- `Single m_positionLimitMax`

- `Boolean m_forceUpdateImageSegment`

- `MapPosInfo m_mapInfo`

- `UIPage m_registeredPage`

- `ZoneViewModel m_cachedZoneviewModel`

- `Boolean m_isInited`

- `StageDiffGroup m_cacheDiffGroup`

- `UICanvasScalerHelper m_scaler`


## Properties

- `Single positionValue`

- `Single imageRefValue`

- `Single positionLimitMin`

- `Single positionLimitMax`

- `Boolean canMapDrag`

- `UICanvasScalerHelper scaler`


## Methods

- `Void _InitPluginsIfNot(Single)`

- `Void NotifyPluginsMapPositionChanged(Single)`

- `Void set_onStageClick(Action`1)`

- `Void set_onFogClick(Action`1)`

- `Void set_onSpecialStageRewardClick(Action`1)`

- `Single get_positionValue()`

- `Single get_imageRefValue()`

- `Single get_positionLimitMin()`

- `Single get_positionLimitMax()`

- `Boolean get_canMapDrag()`

- `Void _OnStageButtonPressed(String)`

- `Void _OnStageFogPressed(String)`

- `Void _OnSpecialStageRewardPressed(String)`

- `Boolean TryAchieveStageButtonTransform(String, out)`

- `Void Setup(ZoneViewModel, IStageMainZoneMapController)`

- `Void _GenerateStageFog(StageFogOnMapBase, String)`

- `String _GetFogUnlockDesc(FogType)`

- `Boolean _StageFogPrevStagePassed(StageFogInfo)`

- `Boolean _StageFogPrevStageUnlocked(StageFogInfo)`

- `Boolean _StagePrevFogUnlocked(StageFogInfo)`

- `Void _OnFogUnlockStageNotPass(String)`

- `Void _OnFogUnlockItemNotEnough(String)`

- `Void _InitButtons(ZoneViewModel, IStageMainZoneMapController, List`1)`

- `Void _UpdateStagePanel(Single)`

- `Boolean _GetPositionValueFromTransform(Transform, out)`

- `Single GetPositionValueFromStageId(String)`

- `Void _UpdateBackgroundImage(Single)`

- `Void _UpdateBackgroundPosition(Single)`

- `Void Update()`

- `Void _RenderLines(List`1)`

- `Void _BindRenderToRegisterToPage(UIPage)`

- `Void _UnbindRenderToUnregisterFromPage()`

- `Void _TraceForAVG(ZoneViewModel)`

- `MainStageButtonOnMapHolder _GenerateEmptyButtonHolder()`

- `BoundType _DeriveBoundType()`

- `Boolean _UseStageButtonAsBound()`

- `Boolean _UseLockedStagesDuringCalcBound()`

- `UICanvasScalerHelper get_scaler()`

- `Void _AdjustBkgBoundOnScalerChanged(CanvasScaler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMainZoneMap : MonoBehaviour, IHotfixable
{
	private Boolean _canMapDrag; // 0x18
	private Boolean _needDrawLines; // 0x19
	private Boolean _stageBindToBackground; // 0x1a
	private BoundType _boundType; // 0x1c
	private Single _bindBackgroundWidth; // 0x20
	private MainStageButtonOnMapHolder[] _stageButtonContainers; // 0x28
	private StageButtonOnMap _stageButtonProto; // 0x30
	private Canvas[] _canvasToBind; // 0x38
	private Image _backgroundImagePrimary; // 0x40
	private Image _backgroundImageSecondary; // 0x48
	private Image _backgroundImageBindToStage; // 0x50
	private BackgroundSegment[] _backgroundSegments; // 0x58
	private Single _stagePanelMoveSpeed; // 0x60
	private Single _backgroundMoveSpeed; // 0x64
	private RectTransform _stagePanel; // 0x68
	private Single _backgroundFadeDuration; // 0x70
	private Single _positionValueLimitMinOffset; // 0x74
	private Single _positionValueLimitMaxOffset; // 0x78
	private UIImageLine _linePrefab; // 0x80
	private RectTransform _lineContainer; // 0x88
	private List`1 _mapLines; // 0x90
	private List`1 _manualLines; // 0x98
	private StageFogOnMapHolder[] _stageFogContainers; // 0xa0
	private List`1 m_plugins; // 0xa8
	private Boolean _useLockedStagesAsBound; // 0xb0
	private Action`1 m_onFogClick; // 0xb8
	private IStageMainZoneMapController m_currentController; // 0xc0
	private Single m_lastPositionValue; // 0xc8
	private Single m_lastImageRefValue; // 0xcc
	private BackgroundSegment m_currentSegment; // 0xd0
	private Tween m_currentTween; // 0xd8
	private Single m_primaryBaseLine; // 0xe0
	private Single m_secondaryBaseLine; // 0xe4
	private Single m_bindBgBaseLine; // 0xe8
	private Action`1 m_onStageClick; // 0xf0
	private Single m_positionLimitMin; // 0xf8
	private Single m_positionLimitMax; // 0xfc
	private Boolean m_forceUpdateImageSegment; // 0x100
	private Dictionary`2 m_fogStatus; // 0x108
	private Action`1 m_onSpecialStageRewardClick; // 0x110
	private MapPosInfo m_mapInfo; // 0x118
	private UIPage m_registeredPage; // 0x128
	private List`1 m_validSegments; // 0x130
	private List`1 m_stageButtonPatches; // 0x138
	private List`1 m_buttonHolders; // 0x140
	private ZoneViewModel m_cachedZoneviewModel; // 0x148
	private Boolean m_isInited; // 0x150
	private StageDiffGroup m_cacheDiffGroup; // 0x154
	private UICanvasScalerHelper m_scaler; // 0x158
	private static DelegateBridge __Hotfix0__InitPluginsIfNot; // 0x0
	private static DelegateBridge __Hotfix0_NotifyPluginsMapPositionChanged; // 0x8
	private static DelegateBridge __Hotfix0_set_onStageClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onFogClick; // 0x18
	private static DelegateBridge __Hotfix0_set_onSpecialStageRewardClick; // 0x20
	private static DelegateBridge __Hotfix0_get_positionValue; // 0x28
	private static DelegateBridge __Hotfix0_get_imageRefValue; // 0x30
	private static DelegateBridge __Hotfix0_get_positionLimitMin; // 0x38
	private static DelegateBridge __Hotfix0_get_positionLimitMax; // 0x40
	private static DelegateBridge __Hotfix0_get_canMapDrag; // 0x48
	private static DelegateBridge __Hotfix0__OnStageButtonPressed; // 0x50
	private static DelegateBridge __Hotfix0__OnStageFogPressed; // 0x58
	private static DelegateBridge __Hotfix0__OnSpecialStageRewardPressed; // 0x60
	private static DelegateBridge __Hotfix0_TryAchieveStageButtonTransform; // 0x68
	private static DelegateBridge __Hotfix0_Setup; // 0x70
	private static DelegateBridge __Hotfix0__GenerateStageFog; // 0x78
	private static DelegateBridge __Hotfix0__GetFogUnlockDesc; // 0x80
	private static DelegateBridge __Hotfix0__StageFogPrevStagePassed; // 0x88
	private static DelegateBridge __Hotfix0__StageFogPrevStageUnlocked; // 0x90
	private static DelegateBridge __Hotfix0__StagePrevFogUnlocked; // 0x98
	private static DelegateBridge __Hotfix0__OnFogUnlockStageNotPass; // 0xa0
	private static DelegateBridge __Hotfix0__OnFogUnlockItemNotEnough; // 0xa8
	private static DelegateBridge __Hotfix0__InitButtons; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateStagePanel; // 0xb8
	private static DelegateBridge __Hotfix0__GetPositionValueFromTransform; // 0xc0
	private static DelegateBridge __Hotfix0_GetPositionValueFromStageId; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateBackgroundImage; // 0xd0
	private static DelegateBridge __Hotfix0__UpdateBackgroundPosition; // 0xd8
	private static DelegateBridge __Hotfix0_Update; // 0xe0
	private static DelegateBridge __Hotfix0__RenderLines; // 0xe8
	private static DelegateBridge __Hotfix0__LoadStageButtonPatches; // 0xf0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xf8
	private static DelegateBridge __Hotfix0__BindRenderToRegisterToPage; // 0x100
	private static DelegateBridge __Hotfix0__UnbindRenderToUnregisterFromPage; // 0x108
	private static DelegateBridge __Hotfix0__FindCanvasToRegisterToPage; // 0x110
	private static DelegateBridge __Hotfix0__TraceForAVG; // 0x118
	private static DelegateBridge __Hotfix0__GenerateEmptyButtonHolder; // 0x120
	private static DelegateBridge __Hotfix0__DeriveBoundType; // 0x128
	private static DelegateBridge __Hotfix0__UseStageButtonAsBound; // 0x130
	private static DelegateBridge __Hotfix0__UseLockedStagesDuringCalcBound; // 0x138
	private static DelegateBridge __Hotfix0_get_scaler; // 0x140
	private static DelegateBridge __Hotfix0__AdjustBkgBoundOnScalerChanged; // 0x148
	private static DelegateBridge __Hotfix0_ZoneMapOnlyRenderStage; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158

	public Action`1 onStageClick { set; }
	public Action`1 onFogClick { set; }
	public Action`1 onSpecialStageRewardClick { set; }
	private Single positionValue { get; }
	private Single imageRefValue { get; }
	public Single positionLimitMin { get; }
	public Single positionLimitMax { get; }
	public Boolean canMapDrag { get; }
	private UICanvasScalerHelper scaler { get; }

	// RVA: 0x2f91550 VA: 0x75955a9550
	private Void _InitPluginsIfNot(Single posValue) { }
	// RVA: 0x2f91780 VA: 0x75955a9780
	protected Void NotifyPluginsMapPositionChanged(Single posValue) { }
	// RVA: 0x2f91950 VA: 0x75955a9950
	public Void set_onStageClick(Action`1 value) { }
	// RVA: 0x2f919d4 VA: 0x75955a99d4
	public Void set_onFogClick(Action`1 value) { }
	// RVA: 0x2f91a58 VA: 0x75955a9a58
	public Void set_onSpecialStageRewardClick(Action`1 value) { }
	// RVA: 0x2f91adc VA: 0x75955a9adc
	private Single get_positionValue() { }
	// RVA: 0x2f91bc0 VA: 0x75955a9bc0
	private Single get_imageRefValue() { }
	// RVA: 0x2f91ca8 VA: 0x75955a9ca8
	public Single get_positionLimitMin() { }
	// RVA: 0x2f91d10 VA: 0x75955a9d10
	public Single get_positionLimitMax() { }
	// RVA: 0x2f91d78 VA: 0x75955a9d78
	public Boolean get_canMapDrag() { }
	// RVA: 0x2f91de0 VA: 0x75955a9de0
	private Void _OnStageButtonPressed(String stageId) { }
	// RVA: 0x2f91e80 VA: 0x75955a9e80
	private Void _OnStageFogPressed(String stageId) { }
	// RVA: 0x2f91f20 VA: 0x75955a9f20
	private Void _OnSpecialStageRewardPressed(String stageId) { }
	// RVA: 0x2f91fc0 VA: 0x75955a9fc0
	public Boolean TryAchieveStageButtonTransform(String stageId, out RectTransform buttonTrans) { }
	// RVA: 0x2f9219c VA: 0x75955aa19c
	public Void Setup(ZoneViewModel zoneModel, IStageMainZoneMapController controller) { }
	// RVA: 0x2f9366c VA: 0x75955ab66c
	private Void _GenerateStageFog(StageFogOnMapBase fog, String fogId) { }
	// RVA: 0x2f94530 VA: 0x75955ac530
	private String _GetFogUnlockDesc(FogType fogType) { }
	// RVA: 0x2f943b0 VA: 0x75955ac3b0
	private Boolean _StageFogPrevStagePassed(StageFogInfo fogInfo) { }
	// RVA: 0x2f94430 VA: 0x75955ac430
	private Boolean _StageFogPrevStageUnlocked(StageFogInfo fogInfo) { }
	// RVA: 0x2f944b0 VA: 0x75955ac4b0
	private Boolean _StagePrevFogUnlocked(StageFogInfo fogInfo) { }
	// RVA: 0x2f945e4 VA: 0x75955ac5e4
	private Void _OnFogUnlockStageNotPass(String stageId) { }
	// RVA: 0x2f94758 VA: 0x75955ac758
	private Void _OnFogUnlockItemNotEnough(String stageId) { }
	// RVA: 0x2f92ac4 VA: 0x75955aaac4
	private Void _InitButtons(ZoneViewModel zoneModel, IStageMainZoneMapController controller, List`1 stageButtonPatches) { }
	// RVA: 0x2f94a60 VA: 0x75955aca60
	private Void _UpdateStagePanel(Single positionValue) { }
	// RVA: 0x2f9355c VA: 0x75955ab55c
	private Boolean _GetPositionValueFromTransform(Transform trans, out Single result) { }
	// RVA: 0x2f94af4 VA: 0x75955acaf4
	public Single GetPositionValueFromStageId(String stageId) { }
	// RVA: 0x2f94c2c VA: 0x75955acc2c
	private Void _UpdateBackgroundImage(Single imageRefValue) { }
	// RVA: 0x2f95288 VA: 0x75955ad288
	private Void _UpdateBackgroundPosition(Single positionValue) { }
	// RVA: 0x2f95384 VA: 0x75955ad384
	private Void Update() { }
	// RVA: 0x2f93c9c VA: 0x75955abc9c
	private Void _RenderLines(List`1 stageButtonPatches) { }
	// RVA: 0x2f927d8 VA: 0x75955aa7d8
	private List`1 _LoadStageButtonPatches(ZoneViewModel zoneModel) { }
	// RVA: 0x2f95508 VA: 0x75955ad508
	protected virtual Void OnDestroy() { }
	// RVA: 0x2f930b8 VA: 0x75955ab0b8
	private Void _BindRenderToRegisterToPage(UIPage page) { }
	// RVA: 0x2f95624 VA: 0x75955ad624
	private Void _UnbindRenderToUnregisterFromPage() { }
	// RVA: 0x2f95818 VA: 0x75955ad818
	private List`1 _FindCanvasToRegisterToPage() { }
	// RVA: 0x2f94224 VA: 0x75955ac224
	private Void _TraceForAVG(ZoneViewModel zoneModel) { }
	// RVA: 0x2f94898 VA: 0x75955ac898
	private MainStageButtonOnMapHolder _GenerateEmptyButtonHolder() { }
	// RVA: 0x2f95c14 VA: 0x75955adc14
	private BoundType _DeriveBoundType() { }
	// RVA: 0x2f93328 VA: 0x75955ab328
	private Boolean _UseStageButtonAsBound() { }
	// RVA: 0x2f933a4 VA: 0x75955ab3a4
	private Boolean _UseLockedStagesDuringCalcBound() { }
	// RVA: 0x2f93b20 VA: 0x75955abb20
	private UICanvasScalerHelper get_scaler() { }
	// RVA: 0x2f95d00 VA: 0x75955add00
	private Void _AdjustBkgBoundOnScalerChanged(CanvasScaler canvasScaler) { }
	// RVA: 0x2f93418 VA: 0x75955ab418
	public static Void ZoneMapOnlyRenderStage(StageButtonOnMap button, StageButtonOnMapHolder holder, StageViewModel stageModel, ZoneViewModel zoneModel, Boolean isSelected) { }
	// RVA: 0x2f96188 VA: 0x75955ae188
	public Void .ctor() { }
}
```