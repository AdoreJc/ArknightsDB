# RL01MainTransitionView

**Namespace:** `Torappu.UI.Roguelike.RL01`


## Fields

- `CanvasGroup _panelMainTrans`

- `AudioClickPlayer _clickAudio`

- `Text _textName`

- `Text _textDesc`

- `GameObject _labelAutoTransition`

- `GameObject _labelManualTransition`

- `RL01TransitionClockView _clockView`

- `SimpleLayoutContent _tagLayoutContent`

- `AnimationWrapper _animWrapper`

- `Tween m_animTween`

- `Tween m_clockTween`

- `Boolean m_isInited`

- `TagAdapter m_tagAdapter`

- `MainTransParam m_cachedMainTransParam`

- `Boolean m_waitForNextClick`

- `Boolean m_waitForAnimEnd`

- `FadeSwitchTween m_mainTransSwitch`


## Properties

- `FadeSwitchTween mainTransSwitch`


## Methods

- `FadeSwitchTween get_mainTransSwitch()`

- `Void OnEnable()`

- `Void _InitIfNot()`

- `Void EventOnMainPanelClicked()`

- `Void _RenderMainTrans(MainTransParam)`

- `IEnumerator _WaitForNextClick()`

- `Boolean <TransCoroutine>b__27_0()`

- `Boolean <TransCoroutine>b__27_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL01
public class RL01MainTransitionView : RoguelikeMainTransController
{
	private const String VARI_ANIM_PARAM; // 0x0
	private const Single SHOW_TWEEN_DURATION; // 0x0
	private const Single HIDE_TWEEN_DURATION; // 0x0
	private const Single AUTO_MAIN_TRANS_DUR; // 0x0
	private CanvasGroup _panelMainTrans; // 0x20
	private AudioClickPlayer _clickAudio; // 0x28
	private Text _textName; // 0x30
	private Text _textDesc; // 0x38
	private GameObject _labelAutoTransition; // 0x40
	private GameObject _labelManualTransition; // 0x48
	private RL01TransitionClockView _clockView; // 0x50
	private SimpleLayoutContent _tagLayoutContent; // 0x58
	private AnimationWrapper _animWrapper; // 0x60
	private Tween m_animTween; // 0x68
	private Tween m_clockTween; // 0x70
	private Boolean m_isInited; // 0x78
	private TagAdapter m_tagAdapter; // 0x80
	private MainTransParam m_cachedMainTransParam; // 0x88
	private Boolean m_waitForNextClick; // 0xa8
	private Boolean m_waitForAnimEnd; // 0xa9
	private FadeSwitchTween m_mainTransSwitch; // 0xb0
	private static DelegateBridge __Hotfix0_get_mainTransSwitch; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0_TransCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_EventOnMainPanelClicked; // 0x30
	private static DelegateBridge __Hotfix0__RenderMainTrans; // 0x38
	private static DelegateBridge __Hotfix0__WaitForNextClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected FadeSwitchTween mainTransSwitch { get; }

	// RVA: 0x2b7b30c VA: 0x759519330c
	protected FadeSwitchTween get_mainTransSwitch() { }
	// RVA: 0x2b7b3e8 VA: 0x75951933e8
	private Void OnEnable() { }
	// RVA: 0x2b7b480 VA: 0x7595193480
	public override Void Render(RoguelikeDungeonZoneViewProperty property) { }
	// RVA: 0x2b7b800 VA: 0x7595193800
	public override Void Reset() { }
	// RVA: 0x2b7b8c4 VA: 0x75951938c4
	public override IEnumerator TransCoroutine() { }
	// RVA: 0x2b7b558 VA: 0x7595193558
	private Void _InitIfNot() { }
	// RVA: 0x2b7b998 VA: 0x7595193998
	public Void EventOnMainPanelClicked() { }
	// RVA: 0x2b7b5ec VA: 0x75951935ec
	private Void _RenderMainTrans(MainTransParam zoneParam) { }
	// RVA: 0x2b7bb18 VA: 0x7595193b18
	private IEnumerator _WaitForNextClick() { }
	// RVA: 0x2b7bbec VA: 0x7595193bec
	public Void .ctor() { }
	// RVA: 0x2b7bd08 VA: 0x7595193d08
	private Boolean <TransCoroutine>b__27_0() { }
	// RVA: 0x2b7bd1c VA: 0x7595193d1c
	private Boolean <TransCoroutine>b__27_1() { }
}
```