# Act1VAutoChessEntryTeamInfoSubFrontView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessTeamInfoAdapter _charTeamCardAdapter`

- `Act1VAutoChessTeamInfoAdapter _enemyTeamCardAdapter`

- `UIAnimationLocation _animSwitchToChar`

- `UIAnimationLocation _animSwitchToEnemy`

- `AnimationWrapper _animListRefresh`

- `RectTransform _topMenuContainer`

- `Boolean m_isInited`

- `Act1VAutoChessEntryTeamInfoViewModel m_cachedTeamInfoViewModel`

- `UIPageFinder m_pageFinder`

- `UIBiAnimClipSwitchTween m_switchTween`

- `Builder m_switchTweenBuilder`


## Methods

- `Void _InitIfNot()`

- `Void _PlaySwitchAnim()`

- `Void _EventOnClickReturnBtn()`

- `Void OnSwitchTeam()`

- `Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryTeamInfoSubFrontView : Act1VAutoChessBaseSubView
{
	private Act1VAutoChessTeamInfoAdapter _charTeamCardAdapter; // 0x18
	private Act1VAutoChessTeamInfoAdapter _enemyTeamCardAdapter; // 0x20
	private UIAnimationLocation _animSwitchToChar; // 0x28
	private UIAnimationLocation _animSwitchToEnemy; // 0x38
	private AnimationWrapper _animListRefresh; // 0x48
	private RectTransform _topMenuContainer; // 0x50
	private Boolean m_isInited; // 0x58
	private Act1VAutoChessEntryTeamInfoViewModel m_cachedTeamInfoViewModel; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private UIBiAnimClipSwitchTween m_switchTween; // 0x78
	private Builder m_switchTweenBuilder; // 0x80
	private const String ANIM_LIST_REFRESH; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__PlaySwitchAnim; // 0x10
	private static DelegateBridge __Hotfix0__EventOnClickReturnBtn; // 0x18
	private static DelegateBridge __Hotfix0_OnSwitchTeam; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x334dda4 VA: 0x7595965da4
	public override Void Render(Act1VAutoChessEntryBaseSubViewModel subViewModel) { }
	// RVA: 0x334e000 VA: 0x7595966000
	private Void _InitIfNot() { }
	// RVA: 0x334e1dc VA: 0x75959661dc
	private Void _PlaySwitchAnim() { }
	// RVA: 0x334e398 VA: 0x7595966398
	private Void _EventOnClickReturnBtn() { }
	// RVA: 0x334e44c VA: 0x759596644c
	public Void OnSwitchTeam() { }
	// RVA: 0x334e57c VA: 0x759596657c
	public Void .ctor() { }
	// RVA: 0x334e5ec VA: 0x75959665ec
	private Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel P0) { }
}
```