# HomeIllustrateViewState

**Namespace:** `Torappu.UI.HomeIllustrate`


## Fields

- `HomeIllustrateStateBean _stateBean`

- `UIAtlasImage _portrait`

- `Transform _illustContainer`

- `Text _name`

- `Text _nickName`

- `Image _evolveIcon`

- `UIColorGraphic _illustHotspot`

- `UICommonTrackPoint _backgroundTrackPoint`

- `UICommonTrackPoint _themeTrackPoint`

- `GameObject _themeEnableButton`

- `TrackPointViewProperty m_backgroundTrackProp`

- `TrackPointViewProperty m_themeTrackProp`


## Methods

- `Void OnEventToSelect()`

- `Void OnEventToView()`

- `Void OnEventEditPos()`

- `Void OnEventChangeBackground()`

- `Void OnEventChangeTheme()`

- `Void _BindTrackPoints()`

- `Void _UpdateTrackPoint()`

- `Void _Render()`

- `Void _GotoSecretarySkinChangeState()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HomeIllustrate
public class HomeIllustrateViewState : State
{
	private HomeIllustrateStateBean _stateBean; // 0x50
	private UIAtlasImage _portrait; // 0x58
	private Transform _illustContainer; // 0x60
	private Text _name; // 0x68
	private Text _nickName; // 0x70
	private Image _evolveIcon; // 0x78
	private UIColorGraphic _illustHotspot; // 0x80
	private UICommonTrackPoint _backgroundTrackPoint; // 0x88
	private UICommonTrackPoint _themeTrackPoint; // 0x90
	private GameObject _themeEnableButton; // 0x98
	private TrackPointViewProperty m_backgroundTrackProp; // 0xa0
	private TrackPointViewProperty m_themeTrackProp; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEventToSelect; // 0x8
	private static DelegateBridge __Hotfix0_OnEventToView; // 0x10
	private static DelegateBridge __Hotfix0_OnEventEditPos; // 0x18
	private static DelegateBridge __Hotfix0_OnEventChangeBackground; // 0x20
	private static DelegateBridge __Hotfix0_OnEventChangeTheme; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnResume; // 0x38
	private static DelegateBridge __Hotfix0__BindTrackPoints; // 0x40
	private static DelegateBridge __Hotfix0__UpdateTrackPoint; // 0x48
	private static DelegateBridge __Hotfix0__Render; // 0x50
	private static DelegateBridge __Hotfix0__GotoSecretarySkinChangeState; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x27d7190 VA: 0x7594def190
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27d71f8 VA: 0x7594def1f8
	public Void OnEventToSelect() { }
	// RVA: 0x27d7454 VA: 0x7594def454
	public Void OnEventToView() { }
	// RVA: 0x27d7540 VA: 0x7594def540
	public Void OnEventEditPos() { }
	// RVA: 0x27d7624 VA: 0x7594def624
	public Void OnEventChangeBackground() { }
	// RVA: 0x27d7708 VA: 0x7594def708
	public Void OnEventChangeTheme() { }
	// RVA: 0x27d77ec VA: 0x7594def7ec
	protected override Void OnEnter() { }
	// RVA: 0x27d7ce8 VA: 0x7594defce8
	protected override Void OnResume() { }
	// RVA: 0x27d7868 VA: 0x7594def868
	private Void _BindTrackPoints() { }
	// RVA: 0x27d7d5c VA: 0x7594defd5c
	private Void _UpdateTrackPoint() { }
	// RVA: 0x27d7908 VA: 0x7594def908
	private Void _Render() { }
	// RVA: 0x27d7278 VA: 0x7594def278
	private Void _GotoSecretarySkinChangeState() { }
	// RVA: 0x27d7e18 VA: 0x7594defe18
	public Void .ctor() { }
	// RVA: 0x27d7ef0 VA: 0x7594defef0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27d7ef8 VA: 0x7594defef8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```