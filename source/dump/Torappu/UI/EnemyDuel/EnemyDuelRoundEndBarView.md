# EnemyDuelRoundEndBarView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Text _title`

- `GameObject _remainPlayerPanel`

- `Text _remainPlayer`

- `Text _totalPlayer`

- `CanvasGroup _bottomBar`

- `Text _countDownNum`

- `Text _countDownText`

- `UIButton _btnQuit`

- `GameObject _btnQuitPanel`

- `CanvasGroup _windowQuit`

- `Text _windowText`

- `UIAnimationLocation _windowQuitAnim`

- `UIAnimationLocation _sandClockAnim`

- `Boolean m_isRoomMode`

- `Boolean m_isRoomOwner`

- `Boolean m_inited`

- `Int32 m_seconds`

- `AnimationSwitchTween m_windowTween`

- `CountDownTask m_countDownTask`

- `FadeSwitchTween m_fadeTween`

- `Tween m_sandClockTween`

- `Tween m_startDelayCall`

- `Tween m_endDelayCall`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(EnemyDuelRoundEndBarModel)`

- `Void OnEntryTweenComplete()`

- `Void OnStatePause()`

- `Void OnQuitBtnClicked()`

- `Void OnQuitWindowConfirmClicked()`

- `Void OnQuitWindowCancelClicked()`

- `Void _OnQuit()`

- `Void _InitIfNot()`

- `Void Update()`

- `Void <OnEntryTweenComplete>b__26_0()`

- `Void <_InitIfNot>b__32_0(TickValue)`

- `Void <_InitIfNot>b__32_1()`

- `Void <_InitIfNot>b__32_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndBarView : MonoBehaviour, IHotfixable
{
	private const Single BOTTOM_SHOW_DELAY; // 0x0
	private Text _title; // 0x18
	private GameObject _remainPlayerPanel; // 0x20
	private Text _remainPlayer; // 0x28
	private Text _totalPlayer; // 0x30
	private CanvasGroup _bottomBar; // 0x38
	private Text _countDownNum; // 0x40
	private Text _countDownText; // 0x48
	private UIButton _btnQuit; // 0x50
	private GameObject _btnQuitPanel; // 0x58
	private CanvasGroup _windowQuit; // 0x60
	private Text _windowText; // 0x68
	private UIAnimationLocation _windowQuitAnim; // 0x70
	private UIAnimationLocation _sandClockAnim; // 0x80
	private Boolean m_isRoomMode; // 0x90
	private Boolean m_isRoomOwner; // 0x91
	private Boolean m_inited; // 0x92
	private Int32 m_seconds; // 0x94
	private AnimationSwitchTween m_windowTween; // 0x98
	private CountDownTask m_countDownTask; // 0xa0
	private FadeSwitchTween m_fadeTween; // 0xa8
	private Tween m_sandClockTween; // 0xb0
	private Tween m_startDelayCall; // 0xb8
	private Tween m_endDelayCall; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnEntryTweenComplete; // 0x8
	private static DelegateBridge __Hotfix0_OnStatePause; // 0x10
	private static DelegateBridge __Hotfix0_OnQuitBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnQuitWindowConfirmClicked; // 0x20
	private static DelegateBridge __Hotfix0_OnQuitWindowCancelClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnQuit; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x298d55c VA: 0x7594fa555c
	public Void Render(EnemyDuelRoundEndBarModel model) { }
	// RVA: 0x298db80 VA: 0x7594fa5b80
	public Void OnEntryTweenComplete() { }
	// RVA: 0x298dd14 VA: 0x7594fa5d14
	public Void OnStatePause() { }
	// RVA: 0x298ddcc VA: 0x7594fa5dcc
	public Void OnQuitBtnClicked() { }
	// RVA: 0x298df48 VA: 0x7594fa5f48
	public Void OnQuitWindowConfirmClicked() { }
	// RVA: 0x298dfb0 VA: 0x7594fa5fb0
	public Void OnQuitWindowCancelClicked() { }
	// RVA: 0x298dea4 VA: 0x7594fa5ea4
	private Void _OnQuit() { }
	// RVA: 0x298d960 VA: 0x7594fa5960
	private Void _InitIfNot() { }
	// RVA: 0x298e03c VA: 0x7594fa603c
	private Void Update() { }
	// RVA: 0x298e0b8 VA: 0x7594fa60b8
	public Void .ctor() { }
	// RVA: 0x298e128 VA: 0x7594fa6128
	private Void <OnEntryTweenComplete>b__26_0() { }
	// RVA: 0x298e14c VA: 0x7594fa614c
	private Void <_InitIfNot>b__32_0(TickValue tickValue) { }
	// RVA: 0x298e194 VA: 0x7594fa6194
	private Void <_InitIfNot>b__32_1() { }
	// RVA: 0x298e22c VA: 0x7594fa622c
	private Void <_InitIfNot>b__32_2() { }
}
```