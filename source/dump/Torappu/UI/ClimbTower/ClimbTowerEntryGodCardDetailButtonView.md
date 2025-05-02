# ClimbTowerEntryGodCardDetailButtonView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Image _cardIcon`

- `GameObject _divideLine`

- `UIAnimationLocation _animLocation`

- `GameObject _panelTrackPoint`

- `String m_cachedCardId`

- `AnimationSwitchTween m_switchTween`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void set_onClicked(Action`1)`

- `Void Render(ClimbTowerEntryGodCardModel, String, Boolean)`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryGodCardDetailButtonView : MonoBehaviour, IHotfixable
{
	private Image _cardIcon; // 0x18
	private GameObject _divideLine; // 0x20
	private UIAnimationLocation _animLocation; // 0x28
	private GameObject _panelTrackPoint; // 0x38
	private String m_cachedCardId; // 0x40
	private AnimationSwitchTween m_switchTween; // 0x48
	private Boolean m_hasInited; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private Action`1 <onClicked>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onClicked { get; set; }

	// RVA: 0x2c659f8 VA: 0x759527d9f8
	private Action`1 get_onClicked() { }
	// RVA: 0x2c65808 VA: 0x759527d808
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x2c6588c VA: 0x759527d88c
	public Void Render(ClimbTowerEntryGodCardModel viewModel, String selectedCardId, Boolean showDivideLine) { }
	// RVA: 0x2c65b88 VA: 0x759527db88
	public Void OnClick() { }
	// RVA: 0x2c65a60 VA: 0x759527da60
	private Void _InitIfNot() { }
	// RVA: 0x2c65c38 VA: 0x759527dc38
	public Void .ctor() { }
}
```