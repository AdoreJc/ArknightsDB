# RL03MainTransitionView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `CanvasGroup _panelMainTrans`

- `AudioClickPlayer _clickAudio`

- `Text _textName`

- `Text _textDesc`

- `UIAtlasImage _imgVisionBkg`

- `Image _imgVisionIcon`

- `Text _textVisionStatus`

- `Image _zoneIcon`

- `Image _zoneIconSmall`

- `Text _textChaosIncreaseNum`

- `Text _textChaosLevelBefore`

- `Text _textChaosLevelAfter`

- `UIAnimationLocation _animEnter`

- `UIAnimationLocation _chaosIncrease`

- `UIPageFinder m_pageFinder`

- `Tween m_enterTween`

- `Tween m_chaosTween`

- `TransitionParam m_cachedTransitionParam`

- `Boolean m_waitForNextClick`

- `Boolean m_isInited`

- `FadeSwitchTween m_mainTransSwitch`


## Methods

- `Void _InitIfNot()`

- `Void OnEnable()`

- `Void _RenderMainTrans(TransitionParam)`

- `IEnumerator _WaitForNextClick()`

- `Void EventOnMainPanelClicked()`

- `Boolean <TransCoroutine>b__35_0()`

- `Boolean <TransCoroutine>b__35_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03MainTransitionView : RoguelikeMainTransController
{
	private const Single HIDE_TWEEN_DURATION; // 0x0
	private const Single AUTO_MAIN_TRANS_DUR; // 0x0
	private const String CHAOS_LEVEL_FORMAT; // 0x0
	private CanvasGroup _panelMainTrans; // 0x20
	private AudioClickPlayer _clickAudio; // 0x28
	private Text _textName; // 0x30
	private Text _textDesc; // 0x38
	private UIAtlasImage _imgVisionBkg; // 0x40
	private Image _imgVisionIcon; // 0x48
	private Text _textVisionStatus; // 0x50
	private Image _zoneIcon; // 0x58
	private Image _zoneIconSmall; // 0x60
	private Text _textChaosIncreaseNum; // 0x68
	private Text _textChaosLevelBefore; // 0x70
	private Text _textChaosLevelAfter; // 0x78
	private ChaosItem[] _chaosItems; // 0x80
	private UIAnimationLocation _animEnter; // 0x88
	private UIAnimationLocation _chaosIncrease; // 0x98
	private UIAnimationLocation[] _chaosIncreaseAndLevelUp; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private Tween m_enterTween; // 0xc0
	private Tween m_chaosTween; // 0xc8
	private TransitionParam m_cachedTransitionParam; // 0xd0
	private Boolean m_waitForNextClick; // 0xd8
	private Boolean m_isInited; // 0xd9
	private FadeSwitchTween m_mainTransSwitch; // 0xe0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderMainTrans; // 0x18
	private static DelegateBridge __Hotfix0_TransCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge __Hotfix0__WaitForNextClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnMainPanelClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2bb0bf8 VA: 0x75951c8bf8
	private Void _InitIfNot() { }
	// RVA: 0x2bb0cd8 VA: 0x75951c8cd8
	private Void OnEnable() { }
	// RVA: 0x2bb0d68 VA: 0x75951c8d68
	public override Void Render(RoguelikeDungeonZoneViewProperty property) { }
	// RVA: 0x2bb10fc VA: 0x75951c90fc
	private Void _RenderMainTrans(TransitionParam transitionParam) { }
	// RVA: 0x2bb1668 VA: 0x75951c9668
	public override IEnumerator TransCoroutine() { }
	// RVA: 0x2bb173c VA: 0x75951c973c
	public override Void Reset() { }
	// RVA: 0x2bb17fc VA: 0x75951c97fc
	private IEnumerator _WaitForNextClick() { }
	// RVA: 0x2bb18d0 VA: 0x75951c98d0
	public Void EventOnMainPanelClicked() { }
	// RVA: 0x2bb1938 VA: 0x75951c9938
	public Void .ctor() { }
	// RVA: 0x2bb19a8 VA: 0x75951c99a8
	private Boolean <TransCoroutine>b__35_0() { }
	// RVA: 0x2bb19bc VA: 0x75951c99bc
	private Boolean <TransCoroutine>b__35_1() { }
}
```