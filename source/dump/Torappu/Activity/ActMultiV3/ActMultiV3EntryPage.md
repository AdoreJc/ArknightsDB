# ActMultiV3EntryPage

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `CanvasGroup _canvasMask`

- `UIAtlasImage _imgMask`

- `Camera _worldCamera`

- `CanvasGroup _canvasUI`

- `Single _showDelay`

- `Single _hideDelay`

- `RectTransform _dialogContainer`

- `Boolean m_inited`

- `FadeSwitchTween m_maskTween`

- `Tween m_delayTween`

- `Int32 m_cameraInactiveFlag`

- `Boolean m_infoUpdated`

- `DataBundle m_savedInst`

- `Params m_param`

- `Coroutine m_processDelayedAlertsCoroutine`

- `UICompDialogMgr <dialogMgr>k__BackingField`


## Properties

- `UICompDialogMgr dialogMgr`

- `Boolean isStable`

- `String actId`

- `ActMultiV3RouteTarget routeTarget`


## Methods

- `UICompDialogMgr get_dialogMgr()`

- `Void set_dialogMgr(UICompDialogMgr)`

- `Boolean get_isStable()`

- `String get_actId()`

- `ActMultiV3RouteTarget get_routeTarget()`

- `Void _InitIfNot()`

- `Void _ResetEntryStateShowStatus(ShowStatus)`

- `Void _OnGetInfoResponseBack()`

- `Void _OnGetInfoResponseForward()`

- `Void _SetCameraActive(Boolean, CameraActiveSrc)`

- `Void _DisplayPage(Boolean)`

- `Boolean _TryTriggerAVG()`

- `Void _TriggerBGM()`

- `Void _SendGetInfoRequest(Action)`

- `Void SetCameraActiveByStateTransition(Boolean)`

- `Void _ProcessDelayedAlerts()`

- `Void _ClearProcessDelayedAlertsCoroutine()`

- `Void _StartProcessDelayedAlertsCoroutine()`

- `IEnumerator _ProcessDelayedAlertsCoroutine()`

- `Void <_TryTriggerAVG>b__36_0(Story)`

- `Boolean <EffectsOnShow>b__38_0()`

- `Boolean <EffectsOnHide>b__39_0()`

- `Boolean <EffectsOnHide>b__39_1()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnPageRouted()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EntryPage : StateEnginePage
{
	private CanvasGroup _canvasMask; // 0xe8
	private UIAtlasImage _imgMask; // 0xf0
	private Camera _worldCamera; // 0xf8
	private CanvasGroup _canvasUI; // 0x100
	private Single _showDelay; // 0x108
	private Single _hideDelay; // 0x10c
	private RectTransform _dialogContainer; // 0x110
	private Boolean m_inited; // 0x118
	private FadeSwitchTween m_maskTween; // 0x120
	private Tween m_delayTween; // 0x128
	private Int32 m_cameraInactiveFlag; // 0x130
	private Boolean m_infoUpdated; // 0x134
	private DataBundle m_savedInst; // 0x138
	private Params m_param; // 0x140
	private Coroutine m_processDelayedAlertsCoroutine; // 0x148
	private UICompDialogMgr <dialogMgr>k__BackingField; // 0x150
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x0
	private static DelegateBridge __Hotfix0_set_dialogMgr; // 0x8
	private static DelegateBridge __Hotfix0_get_isStable; // 0x10
	private static DelegateBridge __Hotfix0_get_actId; // 0x18
	private static DelegateBridge __Hotfix0_get_routeTarget; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_OnCreate; // 0x30
	private static DelegateBridge __Hotfix0_OnStart; // 0x38
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x40
	private static DelegateBridge __Hotfix0__ResetEntryStateShowStatus; // 0x48
	private static DelegateBridge __Hotfix0__OnGetInfoResponseBack; // 0x50
	private static DelegateBridge __Hotfix0__OnGetInfoResponseForward; // 0x58
	private static DelegateBridge __Hotfix0__SetCameraActive; // 0x60
	private static DelegateBridge __Hotfix0__DisplayPage; // 0x68
	private static DelegateBridge __Hotfix0__TryTriggerAVG; // 0x70
	private static DelegateBridge __Hotfix0__TriggerBGM; // 0x78
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x80
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x88
	private static DelegateBridge __Hotfix0__SendGetInfoRequest; // 0x90
	private static DelegateBridge __Hotfix0_SetCameraActiveByStateTransition; // 0x98
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xa0
	private static DelegateBridge __Hotfix0__ProcessDelayedAlerts; // 0xa8
	private static DelegateBridge __Hotfix0__ClearProcessDelayedAlertsCoroutine; // 0xb0
	private static DelegateBridge __Hotfix0__StartProcessDelayedAlertsCoroutine; // 0xb8
	private static DelegateBridge __Hotfix0__ProcessDelayedAlertsCoroutine; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public UICompDialogMgr dialogMgr { get; set; }
	public Boolean isStable { get; }
	public String actId { get; }
	private ActMultiV3RouteTarget routeTarget { get; }

	// RVA: 0x30e7a18 VA: 0x75956ffa18
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x30e7a80 VA: 0x75956ffa80
	private Void set_dialogMgr(UICompDialogMgr value) { }
	// RVA: 0x30e7b04 VA: 0x75956ffb04
	public Boolean get_isStable() { }
	// RVA: 0x30e7b90 VA: 0x75956ffb90
	public String get_actId() { }
	// RVA: 0x30e7c64 VA: 0x75956ffc64
	private ActMultiV3RouteTarget get_routeTarget() { }
	// RVA: 0x30e7cfc VA: 0x75956ffcfc
	private Void _InitIfNot() { }
	// RVA: 0x30e7de0 VA: 0x75956ffde0
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x30e7ee4 VA: 0x75956ffee4
	protected override Void OnStart() { }
	// RVA: 0x30e85f0 VA: 0x75957005f0
	protected override Void OnPageRouted() { }
	// RVA: 0x30e80dc VA: 0x75957000dc
	private Void _ResetEntryStateShowStatus(ShowStatus showStatus) { }
	// RVA: 0x30e8a4c VA: 0x7595700a4c
	private Void _OnGetInfoResponseBack() { }
	// RVA: 0x30e8b70 VA: 0x7595700b70
	private Void _OnGetInfoResponseForward() { }
	// RVA: 0x30e9040 VA: 0x7595701040
	private Void _SetCameraActive(Boolean active, CameraActiveSrc src) { }
	// RVA: 0x30e9104 VA: 0x7595701104
	private Void _DisplayPage(Boolean isShow) { }
	// RVA: 0x30e8218 VA: 0x7595700218
	private Boolean _TryTriggerAVG() { }
	// RVA: 0x30e84dc VA: 0x75957004dc
	private Void _TriggerBGM() { }
	// RVA: 0x30e91c0 VA: 0x75957011c0
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x30e92b0 VA: 0x75957012b0
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x30e8810 VA: 0x7595700810
	private Void _SendGetInfoRequest(Action onProceed) { }
	// RVA: 0x30e93a0 VA: 0x75957013a0
	public Void SetCameraActiveByStateTransition(Boolean active) { }
	// RVA: 0x30e9424 VA: 0x7595701424
	protected override Void OnDestroy() { }
	// RVA: 0x30e952c VA: 0x759570152c
	private Void _ProcessDelayedAlerts() { }
	// RVA: 0x30e9498 VA: 0x7595701498
	private Void _ClearProcessDelayedAlertsCoroutine() { }
	// RVA: 0x30e844c VA: 0x759570044c
	private Void _StartProcessDelayedAlertsCoroutine() { }
	// RVA: 0x30e967c VA: 0x759570167c
	private IEnumerator _ProcessDelayedAlertsCoroutine() { }
	// RVA: 0x30e9728 VA: 0x7595701728
	public Void .ctor() { }
	// RVA: 0x30e9798 VA: 0x7595701798
	private Void <_TryTriggerAVG>b__36_0(Story story) { }
	// RVA: 0x30e97f4 VA: 0x75957017f4
	private Boolean <EffectsOnShow>b__38_0() { }
	// RVA: 0x30e9810 VA: 0x7595701810
	private Boolean <EffectsOnHide>b__39_0() { }
	// RVA: 0x30e982c VA: 0x759570182c
	private Boolean <EffectsOnHide>b__39_1() { }
	// RVA: 0x30e9848 VA: 0x7595701848
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x30e9850 VA: 0x7595701850
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x30e9858 VA: 0x7595701858
	private Void <>xLuaBaseProxy_OnPageRouted() { }
	// RVA: 0x30e9860 VA: 0x7595701860
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x30e986c VA: 0x759570186c
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
	// RVA: 0x30e9878 VA: 0x7595701878
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```