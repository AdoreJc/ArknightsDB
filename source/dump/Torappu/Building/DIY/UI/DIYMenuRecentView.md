# DIYMenuRecentView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYMenuRecentItemView _recentThemeView`

- `DIYMenuRecentItemView _recentSingleView`

- `CanvasGroup _oldView`

- `Text _presetCount`

- `GameObject _tabTrackpoint`

- `Tween m_switchingTween`


## Methods

- `Void <PlayShowTween>b__10_0()`

- `Void <>xLuaBaseProxy_ShowImmediately()`

- `Void <>xLuaBaseProxy_HideImmediately()`

- `Tween <>xLuaBaseProxy_PlayShowTween()`

- `Tween <>xLuaBaseProxy_PlayHideTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYMenuRecentView : DIYBottomMenuTabStateView
{
	private const Single OLD_VIEW_FADE_OUT_DURATION; // 0x0
	private const Single OLD_VIEW_FADE_OUT_DELAY; // 0x0
	private DIYMenuRecentItemView _recentThemeView; // 0x20
	private DIYMenuRecentItemView _recentSingleView; // 0x28
	private CanvasGroup _oldView; // 0x30
	private Text _presetCount; // 0x38
	private GameObject _tabTrackpoint; // 0x40
	private Tween m_switchingTween; // 0x48
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x0
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x8
	private static DelegateBridge __Hotfix0_PlayShowTween; // 0x10
	private static DelegateBridge __Hotfix0_PlayHideTween; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3822c48 VA: 0x7595e3ac48
	public override Void ShowImmediately() { }
	// RVA: 0x3822d08 VA: 0x7595e3ad08
	public override Void HideImmediately() { }
	// RVA: 0x3822dc8 VA: 0x7595e3adc8
	public override Tween PlayShowTween() { }
	// RVA: 0x3823004 VA: 0x7595e3b004
	public override Tween PlayHideTween() { }
	// RVA: 0x38231ec VA: 0x7595e3b1ec
	public override Void OnValueChanged(DIYMenuProperty property) { }
	// RVA: 0x3823458 VA: 0x7595e3b458
	public Void .ctor() { }
	// RVA: 0x38234c8 VA: 0x7595e3b4c8
	private Void <PlayShowTween>b__10_0() { }
	// RVA: 0x38234f0 VA: 0x7595e3b4f0
	private Void <>xLuaBaseProxy_ShowImmediately() { }
	// RVA: 0x38234f8 VA: 0x7595e3b4f8
	private Void <>xLuaBaseProxy_HideImmediately() { }
	// RVA: 0x3823500 VA: 0x7595e3b500
	private Tween <>xLuaBaseProxy_PlayShowTween() { }
	// RVA: 0x3823508 VA: 0x7595e3b508
	private Tween <>xLuaBaseProxy_PlayHideTween() { }
}
```