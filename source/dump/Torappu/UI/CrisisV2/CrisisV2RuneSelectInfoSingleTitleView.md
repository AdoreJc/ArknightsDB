# CrisisV2RuneSelectInfoSingleTitleView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CanvasGroup _alphaHandler`

- `Text _textTitleNormal`

- `Text _textTitleHighLight`

- `Single _paddingHeight`

- `CanvasGroup _panelFocus`

- `UIAtlasImage _imgDimensionNormal`

- `UIAtlasImage _imgDimensionHighlight`

- `UIAtlasObject _dimensionAtlas`

- `CanvasGroup _titleNormal`

- `CanvasGroup _titleHighlight`

- `TextGenerator m_textGenerator`

- `Single m_titleHeight`

- `Boolean m_isFocusInited`

- `Tween m_focusTween`

- `FadeSwitchTween m_focusOuterGlowTween`

- `FadeSwitchTween m_titleNormalTween`

- `FadeSwitchTween m_titleHighLightTween`

- `String m_cachedGlobalId`


## Methods

- `Void _InitFocusStatusIfNot()`

- `Void _TweenFocusState()`

- `Void _TweenUnFocusState()`

- `Void _ShowOuterGlow(Boolean)`

- `Void _ShowTitleHightLight(Boolean)`

- `Void _ClearFocusTween()`

- `Single _CalcTextHeight(String)`

- `Void <>xLuaBaseProxy_OnFocusStatusChanged(Boolean)`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RuneSelectInfoSingleTitleView : CrisisV2RuneSelectInfoBaseView
{
	private CanvasGroup _alphaHandler; // 0x20
	private Text _textTitleNormal; // 0x28
	private Text _textTitleHighLight; // 0x30
	private Single _paddingHeight; // 0x38
	private CanvasGroup _panelFocus; // 0x40
	private UIAtlasImage _imgDimensionNormal; // 0x48
	private UIAtlasImage _imgDimensionHighlight; // 0x50
	private UIAtlasObject _dimensionAtlas; // 0x58
	private CanvasGroup _titleNormal; // 0x60
	private CanvasGroup _titleHighlight; // 0x68
	private TextGenerator m_textGenerator; // 0x70
	private Single m_titleHeight; // 0x78
	private Boolean m_isFocusInited; // 0x7c
	private Tween m_focusTween; // 0x80
	private FadeSwitchTween m_focusOuterGlowTween; // 0x88
	private FadeSwitchTween m_titleNormalTween; // 0x90
	private FadeSwitchTween m_titleHighLightTween; // 0x98
	private String m_cachedGlobalId; // 0xa0
	private static DelegateBridge __Hotfix0_get_preferredWidth; // 0x0
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x8
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x10
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x18
	private static DelegateBridge __Hotfix0_OnFocusStatusChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__InitFocusStatusIfNot; // 0x30
	private static DelegateBridge __Hotfix0__TweenFocusState; // 0x38
	private static DelegateBridge __Hotfix0__TweenUnFocusState; // 0x40
	private static DelegateBridge __Hotfix0__ShowOuterGlow; // 0x48
	private static DelegateBridge __Hotfix0__ShowTitleHightLight; // 0x50
	private static DelegateBridge __Hotfix0__ClearFocusTween; // 0x58
	private static DelegateBridge __Hotfix0__CalcTextHeight; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override Single preferredWidth { get; }
	public override Single preferredHeight { get; }
	public override CanvasGroup alphaHandler { get; }

	// RVA: 0x2c1600c VA: 0x759522e00c
	public override Single get_preferredWidth() { }
	// RVA: 0x2c160a8 VA: 0x759522e0a8
	public override Single get_preferredHeight() { }
	// RVA: 0x2c16118 VA: 0x759522e118
	public override CanvasGroup get_alphaHandler() { }
	// RVA: 0x2c16180 VA: 0x759522e180
	protected override Void OnDataUpdated(CrisisV2RuneBaseViewModel viewModel) { }
	// RVA: 0x2c166f4 VA: 0x759522e6f4
	protected override Void OnFocusStatusChanged(Boolean isFocused) { }
	// RVA: 0x2c16ad0 VA: 0x759522ead0
	protected override Void OnDestroy() { }
	// RVA: 0x2c163cc VA: 0x759522e3cc
	private Void _InitFocusStatusIfNot() { }
	// RVA: 0x2c16798 VA: 0x759522e798
	private Void _TweenFocusState() { }
	// RVA: 0x2c16a3c VA: 0x759522ea3c
	private Void _TweenUnFocusState() { }
	// RVA: 0x2c16c4c VA: 0x759522ec4c
	private Void _ShowOuterGlow(Boolean show) { }
	// RVA: 0x2c16574 VA: 0x759522e574
	private Void _ShowTitleHightLight(Boolean hightLight) { }
	// RVA: 0x2c16bac VA: 0x759522ebac
	private Void _ClearFocusTween() { }
	// RVA: 0x2c16648 VA: 0x759522e648
	private Single _CalcTextHeight(String desc) { }
	// RVA: 0x2c16d2c VA: 0x759522ed2c
	public Void .ctor() { }
	// RVA: 0x2c16dd0 VA: 0x759522edd0
	private Void <>xLuaBaseProxy_OnFocusStatusChanged(Boolean P0) { }
	// RVA: 0x2c16dd8 VA: 0x759522edd8
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```