# CrisisV2RuneSelectInfoGroupView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Single _spacing`

- `CanvasGroup _alphaHandler`

- `CanvasGroup _panelFocus`

- `SimpleLayoutContent _content`

- `VerticalLayoutGroup _layout`

- `Boolean m_hasInited`

- `String m_bagId`

- `Adapter m_adapter`

- `Tween m_focusTween`

- `FadeSwitchTween m_focusOuterGlowTween`

- `Boolean m_isFocusInited`

- `CrisisV2RunePackViewModel m_model`

- `UIStateFinder m_stateFinder`

- `Single FOCUS_BY_CLICK_SELF`


## Methods

- `Void _InitIfNot()`

- `Void _InitFocusStatusIfNot()`

- `Void _TweenFocusState(Single)`

- `Void _TweenUnFocusState()`

- `Void _ShowOuterGlow(Boolean)`

- `Void _ClearFocusTween()`

- `Void EventOnItemClick()`

- `Void <>xLuaBaseProxy_OnFocusStatusChanged(Boolean)`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RuneSelectInfoGroupView : CrisisV2RuneSelectInfoBaseView
{
	private Single _spacing; // 0x1c
	private CanvasGroup _alphaHandler; // 0x20
	private CanvasGroup _panelFocus; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private VerticalLayoutGroup _layout; // 0x38
	private Boolean m_hasInited; // 0x40
	private String m_bagId; // 0x48
	private Adapter m_adapter; // 0x50
	private Tween m_focusTween; // 0x58
	private FadeSwitchTween m_focusOuterGlowTween; // 0x60
	private Boolean m_isFocusInited; // 0x68
	private CrisisV2RunePackViewModel m_model; // 0x70
	private UIStateFinder m_stateFinder; // 0x78
	private Single FOCUS_BY_CLICK_SELF; // 0x88
	private static DelegateBridge __Hotfix0_get_preferredWidth; // 0x0
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x8
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x10
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x18
	private static DelegateBridge __Hotfix0_OnFocusStatusChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__InitFocusStatusIfNot; // 0x38
	private static DelegateBridge __Hotfix0__TweenFocusState; // 0x40
	private static DelegateBridge __Hotfix0__TweenUnFocusState; // 0x48
	private static DelegateBridge __Hotfix0__ShowOuterGlow; // 0x50
	private static DelegateBridge __Hotfix0__ClearFocusTween; // 0x58
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override Single preferredWidth { get; }
	public override Single preferredHeight { get; }
	public override CanvasGroup alphaHandler { get; }

	// RVA: 0x2c13a3c VA: 0x759522ba3c
	public override Single get_preferredWidth() { }
	// RVA: 0x2c13ad8 VA: 0x759522bad8
	public override Single get_preferredHeight() { }
	// RVA: 0x2c13cf4 VA: 0x759522bcf4
	public override CanvasGroup get_alphaHandler() { }
	// RVA: 0x2c13d5c VA: 0x759522bd5c
	protected override Void OnDataUpdated(CrisisV2RuneBaseViewModel viewModel) { }
	// RVA: 0x2c14058 VA: 0x759522c058
	protected override Void OnFocusStatusChanged(Boolean isFocused) { }
	// RVA: 0x2c1443c VA: 0x759522c43c
	protected override Void OnDestroy() { }
	// RVA: 0x2c13ea4 VA: 0x759522bea4
	private Void _InitIfNot() { }
	// RVA: 0x2c13f74 VA: 0x759522bf74
	private Void _InitFocusStatusIfNot() { }
	// RVA: 0x2c14104 VA: 0x759522c104
	private Void _TweenFocusState(Single focusStayDur) { }
	// RVA: 0x2c143b4 VA: 0x759522c3b4
	private Void _TweenUnFocusState() { }
	// RVA: 0x2c14604 VA: 0x759522c604
	private Void _ShowOuterGlow(Boolean show) { }
	// RVA: 0x2c14564 VA: 0x759522c564
	private Void _ClearFocusTween() { }
	// RVA: 0x2c146e4 VA: 0x759522c6e4
	public Void EventOnItemClick() { }
	// RVA: 0x2c147f0 VA: 0x759522c7f0
	public Void .ctor() { }
	// RVA: 0x2c14868 VA: 0x759522c868
	private Void <>xLuaBaseProxy_OnFocusStatusChanged(Boolean P0) { }
	// RVA: 0x2c14870 VA: 0x759522c870
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```