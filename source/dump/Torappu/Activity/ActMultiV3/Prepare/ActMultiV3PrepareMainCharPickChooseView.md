# ActMultiV3PrepareMainCharPickChooseView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `Text _pickCnt`

- `TwoStateFadeSwitcher _myTurnToggle`

- `SimpleLayoutContent _charList`

- `TwoStateToggle _skipTextToggle`

- `UIAnimationLocation _myTurnAnim`

- `UIAnimationLocation _pTurnAnim`

- `UIAnimationLocation _notiPlayerAnim`

- `Single _delayOnNotiPlayerAnim`

- `Adapter m_charListAdapter`

- `Boolean m_curMyTurn`

- `AnimationSwitchTween m_notiPlayerAnimSwitchTween`

- `Tween m_delayNotiTween`

- `Action <onSkip>k__BackingField`

- `Action <onMyTurn>k__BackingField`


## Properties

- `Action onSkip`

- `Action onMyTurn`


## Methods

- `Void set_onSelectChar(Action`1)`

- `Action get_onSkip()`

- `Void set_onSkip(Action)`

- `Action get_onMyTurn()`

- `Void set_onMyTurn(Action)`

- `Void _SetInvert(Boolean)`

- `Void _InitIfNot()`

- `Void _DelayPlayNotiPlayerAnim(Single)`

- `Void PlayNotiPlayerAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainCharPickChooseView : DataBinder`1
{
	private Text _pickCnt; // 0x20
	private TwoStateFadeSwitcher _myTurnToggle; // 0x28
	private SimpleLayoutContent _charList; // 0x30
	private PrefabMark[] _invertTips; // 0x38
	private TwoStateToggle _skipTextToggle; // 0x40
	private UIAnimationLocation _myTurnAnim; // 0x48
	private UIAnimationLocation _pTurnAnim; // 0x58
	private UIAnimationLocation _notiPlayerAnim; // 0x68
	private Single _delayOnNotiPlayerAnim; // 0x78
	private Adapter m_charListAdapter; // 0x80
	private Boolean m_curMyTurn; // 0x88
	private AnimationSwitchTween m_notiPlayerAnimSwitchTween; // 0x90
	private Tween m_delayNotiTween; // 0x98
	private Action`1 <onSelectChar>k__BackingField; // 0xa0
	private Action <onSkip>k__BackingField; // 0xa8
	private Action <onMyTurn>k__BackingField; // 0xb0
	private static DelegateBridge __Hotfix0_get_onSelectChar; // 0x0
	private static DelegateBridge __Hotfix0_set_onSelectChar; // 0x8
	private static DelegateBridge __Hotfix0_get_onSkip; // 0x10
	private static DelegateBridge __Hotfix0_set_onSkip; // 0x18
	private static DelegateBridge __Hotfix0_get_onMyTurn; // 0x20
	private static DelegateBridge __Hotfix0_set_onMyTurn; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0__SetInvert; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__DelayPlayNotiPlayerAnim; // 0x48
	private static DelegateBridge __Hotfix0_PlayNotiPlayerAnim; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Action`1 onSelectChar { get; set; }
	private Action onSkip { get; set; }
	private Action onMyTurn { get; set; }

	// RVA: 0x3169818 VA: 0x7595781818
	private Action`1 get_onSelectChar() { }
	// RVA: 0x3167458 VA: 0x759577f458
	public Void set_onSelectChar(Action`1 value) { }
	// RVA: 0x3169880 VA: 0x7595781880
	private Action get_onSkip() { }
	// RVA: 0x31674dc VA: 0x759577f4dc
	public Void set_onSkip(Action value) { }
	// RVA: 0x31698e8 VA: 0x75957818e8
	private Action get_onMyTurn() { }
	// RVA: 0x3167560 VA: 0x759577f560
	public Void set_onMyTurn(Action value) { }
	// RVA: 0x3169950 VA: 0x7595781950
	public override Void OnValueChanged(ActMultiV3PrepareMainCharPickPanelViewModelProperty property) { }
	// RVA: 0x3169e04 VA: 0x7595781e04
	private Void _SetInvert(Boolean invert) { }
	// RVA: 0x3169c8c VA: 0x7595781c8c
	private Void _InitIfNot() { }
	// RVA: 0x3169f30 VA: 0x7595781f30
	private Void _DelayPlayNotiPlayerAnim(Single delay) { }
	// RVA: 0x3168098 VA: 0x7595780098
	public Void PlayNotiPlayerAnim() { }
	// RVA: 0x316a094 VA: 0x7595782094
	public Void .ctor() { }
}
```