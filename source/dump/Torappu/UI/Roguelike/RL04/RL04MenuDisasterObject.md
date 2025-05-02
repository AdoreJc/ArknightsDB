# RL04MenuDisasterObject

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GameObject _panelContent`

- `Text _txtZoneName`

- `GameObject _panelNonDisasterBkg`

- `GameObject _panelDisasterBkg`

- `GameObject _panelDisaster`

- `Image _imgZoneIcon`

- `Image _imgDisaster`

- `RectTransform _levelContainer`

- `GameObject _prefabLevel`

- `Text _txtStep`

- `Button _btnDisaster`

- `UIAnimationLocation _disasterFadeinLocation`

- `UIAnimationLocation _disasterFadeoutLocation`

- `UIPageFinder m_pageFinder`

- `RL04MenuDisasterViewModel m_cachedModel`

- `Boolean m_cachedStateShow`

- `Builder m_switchTweenBuilder`

- `UIBiAnimClipSwitchTween m_switchTween`


## Methods

- `Void _Render(Boolean, Boolean)`

- `Void _UpdateRenderers()`

- `Void _RenderShowStatus(Boolean, Boolean)`

- `Void _RenderZone(String, Boolean)`

- `Void _RenderDisaster(DisasterParam, Boolean)`

- `Void _RenderDisasterPart(RL04MenuDisasterViewModel, ILoadAsset)`

- `Boolean <Init>b__26_0()`

- `String <Init>b__26_1()`

- `DisasterParam <Init>b__26_2()`

- `Void <>xLuaBaseProxy_Init(RoguelikeMenuBar)`

- `Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04MenuDisasterObject : RoguelikeMenuObject`1
{
	private static readonly Type[] STATES_NOT_SHOW; // 0x0
	private GameObject _panelContent; // 0x28
	private Text _txtZoneName; // 0x30
	private GameObject _panelNonDisasterBkg; // 0x38
	private GameObject _panelDisasterBkg; // 0x40
	private GameObject _panelDisaster; // 0x48
	private Image _imgZoneIcon; // 0x50
	private Image _imgDisaster; // 0x58
	private RectTransform _levelContainer; // 0x60
	private GameObject _prefabLevel; // 0x68
	private Text _txtStep; // 0x70
	private Button _btnDisaster; // 0x78
	private UIAnimationLocation _disasterFadeinLocation; // 0x80
	private UIAnimationLocation _disasterFadeoutLocation; // 0x90
	private UIPageFinder m_pageFinder; // 0xa0
	private RoguelikeMenuViewRenderer`1 m_showRenderer; // 0xb0
	private RoguelikeMenuViewRenderer`1 m_zoneRenderer; // 0xb8
	private RoguelikeMenuViewRenderer`1 m_disasterRenderer; // 0xc0
	private RL04MenuDisasterViewModel m_cachedModel; // 0xc8
	private Boolean m_cachedStateShow; // 0xd0
	private List`1 m_levelObjs; // 0xd8
	private Builder m_switchTweenBuilder; // 0xe0
	private UIBiAnimClipSwitchTween m_switchTween; // 0x118
	private static DelegateBridge __Hotfix0_get_menuType; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnMenuAdapterChanged; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__Render; // 0x28
	private static DelegateBridge __Hotfix0__UpdateRenderers; // 0x30
	private static DelegateBridge __Hotfix0__RenderShowStatus; // 0x38
	private static DelegateBridge __Hotfix0__RenderZone; // 0x40
	private static DelegateBridge __Hotfix0__RenderDisaster; // 0x48
	private static DelegateBridge __Hotfix0__RenderDisasterPart; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2b296b0 VA: 0x75951416b0
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2b29728 VA: 0x7595141728
	public override Void Init(RoguelikeMenuBar menu) { }
	// RVA: 0x2b29b04 VA: 0x7595141b04
	public override Void OnMenuAdapterChanged(RoguelikeMenuAdapter adapter, Boolean fastMode) { }
	// RVA: 0x2b29e34 VA: 0x7595141e34
	public override Void Render(RL04MenuDisasterViewModel viewModel) { }
	// RVA: 0x2b29cfc VA: 0x7595141cfc
	private Void _Render(Boolean fastMode, Boolean isFromAdapterChange) { }
	// RVA: 0x2b29c1c VA: 0x7595141c1c
	private Void _UpdateRenderers() { }
	// RVA: 0x2b29ef4 VA: 0x7595141ef4
	private Void _RenderShowStatus(Boolean show, Boolean fastMode) { }
	// RVA: 0x2b29f90 VA: 0x7595141f90
	private Void _RenderZone(String zoneId, Boolean fastMode) { }
	// RVA: 0x2b2a0a4 VA: 0x75951420a4
	private Void _RenderDisaster(DisasterParam disasterParam, Boolean fastMode) { }
	// RVA: 0x2b2a31c VA: 0x759514231c
	private Void _RenderDisasterPart(RL04MenuDisasterViewModel viewModel, ILoadAsset loader) { }
	// RVA: 0x2b2a718 VA: 0x7595142718
	public Void .ctor() { }
	// RVA: 0x2b2a80c VA: 0x759514280c
	private static Void .cctor() { }
	// RVA: 0x2b2a97c VA: 0x759514297c
	private Boolean <Init>b__26_0() { }
	// RVA: 0x2b2a9bc VA: 0x75951429bc
	private String <Init>b__26_1() { }
	// RVA: 0x2b2a9d8 VA: 0x75951429d8
	private DisasterParam <Init>b__26_2() { }
	// RVA: 0x2b2aa90 VA: 0x7595142a90
	private Void <>xLuaBaseProxy_Init(RoguelikeMenuBar P0) { }
	// RVA: 0x2b2aa98 VA: 0x7595142a98
	private Void <>xLuaBaseProxy_OnMenuAdapterChanged(RoguelikeMenuAdapter P0, Boolean P1) { }
}
```