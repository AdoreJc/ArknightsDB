# RL03TotemBuffBottomView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RL03TotemBuffBottomDescView _locationTotemDescView`

- `RL03TotemBuffBottomDescView _effectTotemDescView`

- `Text _emptyDesc`

- `UIAtlasImage _imgLocation`

- `UIAtlasImage _imgEffect`

- `UIAtlasImage _imgResonance`

- `GameObject _panelResonance`

- `Image _imgTotemBkg`

- `RL03TotemBuffBottomConfirmView _confirmView`

- `UIAnimationLocation _resonanceAnimLocation`

- `Action <onConfirmClick>k__BackingField`

- `RL03TotemBuffBottomViewModel m_viewModel`

- `CacheTotemInfoStruct m_cachedTotemInfoStruct`

- `UIPageFinder m_pageFinder`

- `Tween m_resonanceTween`


## Properties

- `Action onConfirmClick`


## Methods

- `Action get_onConfirmClick()`

- `Void set_onConfirmClick(Action)`

- `Void _PlayResonanceAnim(Boolean)`

- `Boolean _NeedResetResonanceAnim(CacheTotemInfoStruct, CacheTotemInfoStruct)`

- `Void EventOnConfirmBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffBottomView : DataBinder`1
{
	private static Dictionary`2 NONE_RESONANCE_COLOR_DICT; // 0x0
	private RL03TotemBuffBottomDescView _locationTotemDescView; // 0x20
	private RL03TotemBuffBottomDescView _effectTotemDescView; // 0x28
	private Text _emptyDesc; // 0x30
	private UIAtlasImage _imgLocation; // 0x38
	private UIAtlasImage _imgEffect; // 0x40
	private UIAtlasImage _imgResonance; // 0x48
	private GameObject _panelResonance; // 0x50
	private Image _imgTotemBkg; // 0x58
	private RL03TotemBuffBottomConfirmView _confirmView; // 0x60
	private UIAnimationLocation _resonanceAnimLocation; // 0x68
	private Action <onConfirmClick>k__BackingField; // 0x78
	private RL03TotemBuffBottomViewModel m_viewModel; // 0x80
	private CacheTotemInfoStruct m_cachedTotemInfoStruct; // 0x88
	private UIPageFinder m_pageFinder; // 0xa8
	private Tween m_resonanceTween; // 0xb8
	private static DelegateBridge __Hotfix0_get_onConfirmClick; // 0x8
	private static DelegateBridge __Hotfix0_set_onConfirmClick; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__PlayResonanceAnim; // 0x20
	private static DelegateBridge __Hotfix0__NeedResetResonanceAnim; // 0x28
	private static DelegateBridge __Hotfix0_EventOnConfirmBtnClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action onConfirmClick { get; set; }

	// RVA: 0x2ba68bc VA: 0x75951be8bc
	private Action get_onConfirmClick() { }
	// RVA: 0x2ba6934 VA: 0x75951be934
	public Void set_onConfirmClick(Action value) { }
	// RVA: 0x2ba69c8 VA: 0x75951be9c8
	public override Void OnValueChanged(RL03TotemBottomViewProperty property) { }
	// RVA: 0x2ba72b0 VA: 0x75951bf2b0
	private Void _PlayResonanceAnim(Boolean isTotemResonance) { }
	// RVA: 0x2ba6ff8 VA: 0x75951beff8
	private Boolean _NeedResetResonanceAnim(CacheTotemInfoStruct prevTotemInfoStruct, CacheTotemInfoStruct newTotemInfoStruct) { }
	// RVA: 0x2ba74a4 VA: 0x75951bf4a4
	public Void EventOnConfirmBtnClick() { }
	// RVA: 0x2ba7560 VA: 0x75951bf560
	public Void .ctor() { }
	// RVA: 0x2ba7600 VA: 0x75951bf600
	private static Void .cctor() { }
}
```