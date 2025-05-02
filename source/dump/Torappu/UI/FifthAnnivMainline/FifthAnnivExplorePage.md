# FifthAnnivExplorePage

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreMapController _mapController`

- `GameObject _cameraHolder`

- `CanvasGroup _canvasUI`

- `CanvasGroup _canvasMask`

- `RectTransform _dialogContainer`

- `RectTransform _backBtnRect`

- `UICompDialogMgr m_dialogMgr`

- `UISwitchTween m_maskShowTween`

- `Boolean m_isInited`


## Properties

- `UICompDialogMgr dialogMgr`


## Methods

- `UICompDialogMgr get_dialogMgr()`

- `IEnumerator _RouteToMapState()`

- `IEnumerator _RouteToGroupChooseState()`

- `IEnumerator _RouteToCheckpointResultState()`

- `Void _InitIfNot()`

- `Void _DisplayMap(Boolean)`

- `Void _ReloadMap(Boolean)`

- `Void OpenMissionDialog()`

- `IEnumerator <>n__0()`

- `Boolean <EffectsOnShow>b__19_0()`

- `Boolean <EffectsOnHide>b__20_0()`

- `Boolean <EffectsOnHide>b__20_1()`

- `String <>xLuaBaseProxy_get_musicSubSignal()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExplorePage : StateEnginePage
{
	private FifthAnnivExploreMapController _mapController; // 0xe8
	private GameObject _cameraHolder; // 0xf0
	private CanvasGroup _canvasUI; // 0xf8
	private CanvasGroup _canvasMask; // 0x100
	private RectTransform _dialogContainer; // 0x108
	private RectTransform _backBtnRect; // 0x110
	private UICompDialogMgr m_dialogMgr; // 0x118
	private UISwitchTween m_maskShowTween; // 0x120
	private Boolean m_isInited; // 0x128
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x0
	private static DelegateBridge __Hotfix0_get_musicSubSignal; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_OnStart; // 0x18
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x20
	private static DelegateBridge __Hotfix0__RouteToMapState; // 0x28
	private static DelegateBridge __Hotfix0__RouteToGroupChooseState; // 0x30
	private static DelegateBridge __Hotfix0__RouteToCheckpointResultState; // 0x38
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x40
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__DisplayMap; // 0x58
	private static DelegateBridge __Hotfix0__ReloadMap; // 0x60
	private static DelegateBridge __Hotfix0_OpenMissionDialog; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public UICompDialogMgr dialogMgr { get; }
	public override String musicSubSignal { get; }

	// RVA: 0x2916f30 VA: 0x7594f2ef30
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x2916f98 VA: 0x7594f2ef98
	public override String get_musicSubSignal() { }
	// RVA: 0x2917004 VA: 0x7594f2f004
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x29172c0 VA: 0x7594f2f2c0
	protected override Void OnStart() { }
	// RVA: 0x2917410 VA: 0x7594f2f410
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x29174e4 VA: 0x7594f2f4e4
	private IEnumerator _RouteToMapState() { }
	// RVA: 0x29175b8 VA: 0x7594f2f5b8
	private IEnumerator _RouteToGroupChooseState() { }
	// RVA: 0x291768c VA: 0x7594f2f68c
	private IEnumerator _RouteToCheckpointResultState() { }
	// RVA: 0x2917760 VA: 0x7594f2f760
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x2917850 VA: 0x7594f2f850
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x29171f0 VA: 0x7594f2f1f0
	private Void _InitIfNot() { }
	// RVA: 0x2917940 VA: 0x7594f2f940
	private Void _DisplayMap(Boolean isShow) { }
	// RVA: 0x2917380 VA: 0x7594f2f380
	private Void _ReloadMap(Boolean isFromStack) { }
	// RVA: 0x2917af0 VA: 0x7594f2faf0
	public Void OpenMissionDialog() { }
	// RVA: 0x2917bf4 VA: 0x7594f2fbf4
	public Void .ctor() { }
	// RVA: 0x2917c64 VA: 0x7594f2fc64
	private IEnumerator <>n__0() { }
	// RVA: 0x2917c6c VA: 0x7594f2fc6c
	private Boolean <EffectsOnShow>b__19_0() { }
	// RVA: 0x2917c88 VA: 0x7594f2fc88
	private Boolean <EffectsOnHide>b__20_0() { }
	// RVA: 0x2917ca4 VA: 0x7594f2fca4
	private Boolean <EffectsOnHide>b__20_1() { }
	// RVA: 0x2917cc0 VA: 0x7594f2fcc0
	private String <>xLuaBaseProxy_get_musicSubSignal() { }
	// RVA: 0x2917cc8 VA: 0x7594f2fcc8
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2917cd0 VA: 0x7594f2fcd0
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x2917cd8 VA: 0x7594f2fcd8
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2917ce0 VA: 0x7594f2fce0
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x2917cec VA: 0x7594f2fcec
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```