# RL04MainTransitionView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `CanvasGroup _panelMainTrans`

- `AudioClickPlayer _clickAudio`

- `Text _textName`

- `Text _textDesc`

- `AnimationWrapper _animWrapper`

- `Image _imgBg`

- `Image _imgLevelLabel`

- `Tween m_enterTween`

- `MainTransParam m_cachedMainTransParam`

- `Boolean m_waitForNextClick`

- `Boolean m_waitForAnimEnd`

- `UIPageFinder m_pageFinder`

- `FadeSwitchTween m_mainTransSwitch`


## Properties

- `FadeSwitchTween mainTransSwitch`


## Methods

- `FadeSwitchTween get_mainTransSwitch()`

- `Void OnEnable()`

- `Void EventOnMainPanelClicked()`

- `Void _RenderMainTrans(MainTransParam)`

- `IEnumerator _WaitForNextClick()`

- `Boolean <TransCoroutine>b__22_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04MainTransitionView : RoguelikeMainTransController
{
	private const Single SHOW_TWEEN_DURATION; // 0x0
	private const Single HIDE_TWEEN_DURATION; // 0x0
	private const Single AUTO_MAIN_TRANS_DUR; // 0x0
	private const String ANIM_ENTER; // 0x0
	private const String SECRET_ID; // 0x0
	private CanvasGroup _panelMainTrans; // 0x20
	private AudioClickPlayer _clickAudio; // 0x28
	private Text _textName; // 0x30
	private Text _textDesc; // 0x38
	private AnimationWrapper _animWrapper; // 0x40
	private Image _imgBg; // 0x48
	private Image _imgLevelLabel; // 0x50
	private Tween m_enterTween; // 0x58
	private MainTransParam m_cachedMainTransParam; // 0x60
	private Boolean m_waitForNextClick; // 0x80
	private Boolean m_waitForAnimEnd; // 0x81
	private UIPageFinder m_pageFinder; // 0x88
	private FadeSwitchTween m_mainTransSwitch; // 0x98
	private static DelegateBridge __Hotfix0_get_mainTransSwitch; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_TransCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0_EventOnMainPanelClicked; // 0x28
	private static DelegateBridge __Hotfix0__RenderMainTrans; // 0x30
	private static DelegateBridge __Hotfix0__WaitForNextClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected FadeSwitchTween mainTransSwitch { get; }

	// RVA: 0x2b5600c VA: 0x759516e00c
	protected FadeSwitchTween get_mainTransSwitch() { }
	// RVA: 0x2b560e8 VA: 0x759516e0e8
	private Void OnEnable() { }
	// RVA: 0x2b56180 VA: 0x759516e180
	public override Void Render(RoguelikeDungeonZoneViewProperty property) { }
	// RVA: 0x2b564d4 VA: 0x759516e4d4
	public override IEnumerator TransCoroutine() { }
	// RVA: 0x2b565a8 VA: 0x759516e5a8
	public override Void Reset() { }
	// RVA: 0x2b56658 VA: 0x759516e658
	public Void EventOnMainPanelClicked() { }
	// RVA: 0x2b5624c VA: 0x759516e24c
	private Void _RenderMainTrans(MainTransParam zoneParam) { }
	// RVA: 0x2b566c0 VA: 0x759516e6c0
	private IEnumerator _WaitForNextClick() { }
	// RVA: 0x2b56794 VA: 0x759516e794
	public Void .ctor() { }
	// RVA: 0x2b56804 VA: 0x759516e804
	private Boolean <TransCoroutine>b__22_0() { }
}
```