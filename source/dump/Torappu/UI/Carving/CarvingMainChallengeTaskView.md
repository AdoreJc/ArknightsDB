# CarvingMainChallengeTaskView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `UIAnimationLocation _animPanelSwitchLocation`

- `UIAnimationLocation _animTaskShowLocation`

- `UIAnimationLocation _animTaskRefreshLocation`

- `UIAnimationLocation _animTaskCompleteLocation`

- `UIAnimationLocation _animTaskHideLocation`

- `Text _goldCntText`

- `Text _extraGoldText`

- `Image _materialIcon`

- `Text _descText`

- `GameObject _missionGroup`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `GameState m_cachedState`

- `String m_cachedIconId`

- `Boolean m_cachedActiveTask`

- `Int32 m_cachedMaterialNum`

- `Int32 m_cachedLoadSeqNum`

- `AnimationSwitchTween m_panelSwitchTween`

- `Tween m_taskTween`


## Methods

- `Void _InitIfNot()`

- `Void _Render(CarvingMainChallengeTaskViewModel, Boolean)`

- `Void _PlayAnim(CarvingMainViewModel, Boolean)`

- `Void _PlayChangeStateAnim(GameState, Boolean, Boolean)`

- `Void _PlayTaskAnim(CarvingMainChallengeTaskViewModel)`

- `Void _PlayTaskShowHideAnim(CarvingMainChallengeTaskViewModel)`

- `Void _PlayTaskRefreshAnim(CarvingMainChallengeTaskViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainChallengeTaskView : DataBinder`1
{
	private const String ADD_COIN_TEXT_FORMAT; // 0x0
	private UIAnimationLocation _animPanelSwitchLocation; // 0x20
	private UIAnimationLocation _animTaskShowLocation; // 0x30
	private UIAnimationLocation _animTaskRefreshLocation; // 0x40
	private UIAnimationLocation _animTaskCompleteLocation; // 0x50
	private UIAnimationLocation _animTaskHideLocation; // 0x60
	private Text _goldCntText; // 0x70
	private Text _extraGoldText; // 0x78
	private Image _materialIcon; // 0x80
	private Text _descText; // 0x88
	private GameObject _missionGroup; // 0x90
	private Boolean m_isInited; // 0x98
	private UIPageFinder m_pageFinder; // 0xa0
	private GameState m_cachedState; // 0xb0
	private String m_cachedIconId; // 0xb8
	private Boolean m_cachedActiveTask; // 0xc0
	private Int32 m_cachedMaterialNum; // 0xc4
	private Int32 m_cachedLoadSeqNum; // 0xc8
	private AnimationSwitchTween m_panelSwitchTween; // 0xd0
	private Tween m_taskTween; // 0xd8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x18
	private static DelegateBridge __Hotfix0__PlayChangeStateAnim; // 0x20
	private static DelegateBridge __Hotfix0__PlayTaskAnim; // 0x28
	private static DelegateBridge __Hotfix0__PlayTaskShowHideAnim; // 0x30
	private static DelegateBridge __Hotfix0__PlayTaskRefreshAnim; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2dadff0 VA: 0x75953c5ff0
	public override Void OnValueChanged(CarvingMainProperty property) { }
	// RVA: 0x2dae0ec VA: 0x75953c60ec
	private Void _InitIfNot() { }
	// RVA: 0x2dae1c4 VA: 0x75953c61c4
	private Void _Render(CarvingMainChallengeTaskViewModel model, Boolean isFirstUpdate) { }
	// RVA: 0x2dae448 VA: 0x75953c6448
	private Void _PlayAnim(CarvingMainViewModel model, Boolean isFirstUpdate) { }
	// RVA: 0x2dae7c8 VA: 0x75953c67c8
	private Void _PlayChangeStateAnim(GameState curState, Boolean isProcessing, Boolean firstUpdate) { }
	// RVA: 0x2dae8dc VA: 0x75953c68dc
	private Void _PlayTaskAnim(CarvingMainChallengeTaskViewModel taskModel) { }
	// RVA: 0x2dae9b8 VA: 0x75953c69b8
	private Void _PlayTaskShowHideAnim(CarvingMainChallengeTaskViewModel taskModel) { }
	// RVA: 0x2daed3c VA: 0x75953c6d3c
	private Void _PlayTaskRefreshAnim(CarvingMainChallengeTaskViewModel taskModel) { }
	// RVA: 0x2daef60 VA: 0x75953c6f60
	public Void .ctor() { }
}
```