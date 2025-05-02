# CrisisV2RuneSelectInfoSingleItemView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CanvasGroup _alphaHandler`

- `Single _paddingHeight`

- `CanvasGroup _panelFocus`

- `CrisisV2RuneSelectInfoItemView _itemView`

- `UIAtlasImage _imgBg`

- `Color _colBgDark`

- `Color _colBgGray`

- `String m_nodeId`

- `Boolean m_isFocusInited`

- `Tween m_focusTween`

- `FadeSwitchTween m_focusOuterGlowTween`

- `UIStateFinder m_stateFinder`

- `String m_cacheId`

- `SingleViewInfoBgType m_cachedBgType`

- `Single FOCUS_BY_CLICK_SELF`


## Methods

- `Void _InitFocusStatusIfNot()`

- `Void _RenderBg(SingleViewInfoBgType)`

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
public class CrisisV2RuneSelectInfoSingleItemView : CrisisV2RuneSelectInfoBaseView
{
	private CanvasGroup _alphaHandler; // 0x20
	private Single _paddingHeight; // 0x28
	private CanvasGroup _panelFocus; // 0x30
	private CrisisV2RuneSelectInfoItemView _itemView; // 0x38
	private UIAtlasImage _imgBg; // 0x40
	private Color _colBgDark; // 0x48
	private Color _colBgGray; // 0x58
	private String m_nodeId; // 0x68
	private Boolean m_isFocusInited; // 0x70
	private Tween m_focusTween; // 0x78
	private FadeSwitchTween m_focusOuterGlowTween; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private String m_cacheId; // 0x98
	private SingleViewInfoBgType m_cachedBgType; // 0xa0
	private Single FOCUS_BY_CLICK_SELF; // 0xa4
	private static DelegateBridge __Hotfix0_get_preferredWidth; // 0x0
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x8
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x10
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x18
	private static DelegateBridge __Hotfix0_OnFocusStatusChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__InitFocusStatusIfNot; // 0x30
	private static DelegateBridge __Hotfix0__RenderBg; // 0x38
	private static DelegateBridge __Hotfix0__TweenFocusState; // 0x40
	private static DelegateBridge __Hotfix0__TweenUnFocusState; // 0x48
	private static DelegateBridge __Hotfix0__ShowOuterGlow; // 0x50
	private static DelegateBridge __Hotfix0__ClearFocusTween; // 0x58
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override Single preferredWidth { get; }
	public override Single preferredHeight { get; }
	public override CanvasGroup alphaHandler { get; }

	// RVA: 0x2c15304 VA: 0x759522d304
	public override Single get_preferredWidth() { }
	// RVA: 0x2c153a0 VA: 0x759522d3a0
	public override Single get_preferredHeight() { }
	// RVA: 0x2c1541c VA: 0x759522d41c
	public override CanvasGroup get_alphaHandler() { }
	// RVA: 0x2c15484 VA: 0x759522d484
	protected override Void OnDataUpdated(CrisisV2RuneBaseViewModel viewModel) { }
	// RVA: 0x2c157dc VA: 0x759522d7dc
	protected override Void OnFocusStatusChanged(Boolean isFocused) { }
	// RVA: 0x2c15be4 VA: 0x759522dbe4
	protected override Void OnDestroy() { }
	// RVA: 0x2c155fc VA: 0x759522d5fc
	private Void _InitFocusStatusIfNot() { }
	// RVA: 0x2c156f4 VA: 0x759522d6f4
	private Void _RenderBg(SingleViewInfoBgType itemBgType) { }
	// RVA: 0x2c15888 VA: 0x759522d888
	private Void _TweenFocusState(Single focusStayDur) { }
	// RVA: 0x2c15b48 VA: 0x759522db48
	private Void _TweenUnFocusState() { }
	// RVA: 0x2c15d18 VA: 0x759522dd18
	private Void _ShowOuterGlow(Boolean show) { }
	// RVA: 0x2c15c78 VA: 0x759522dc78
	private Void _ClearFocusTween() { }
	// RVA: 0x2c15df8 VA: 0x759522ddf8
	public Void EventOnItemClick() { }
	// RVA: 0x2c15f04 VA: 0x759522df04
	public Void .ctor() { }
	// RVA: 0x2c15f7c VA: 0x759522df7c
	private Void <>xLuaBaseProxy_OnFocusStatusChanged(Boolean P0) { }
	// RVA: 0x2c15f84 VA: 0x759522df84
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```