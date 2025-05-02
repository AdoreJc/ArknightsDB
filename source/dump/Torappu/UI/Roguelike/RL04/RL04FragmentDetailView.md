# RL04FragmentDetailView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `UIAnimationLocation _animPrevHide`

- `UIAnimationLocation _animPrevShow`

- `UIAnimationLocation _animNextHide`

- `UIAnimationLocation _animNextShow`

- `UIAnimationLocation _animEnter`

- `RL04FragmentDetailCard _prefabDetailCard`

- `RectTransform _cardContainer`

- `RL04FragmentDetailWeightView _weightView`

- `CanvasGroup _canvasGroupNextBtn`

- `CanvasGroup _canvasGroupPrevBtn`

- `CanvasGroup _canvasGroupUseBtn`

- `Action <onNextBtnClicked>k__BackingField`

- `Action <onPrevBtnClicked>k__BackingField`

- `Action <onUseBtnClicked>k__BackingField`

- `Action <onDropBtnClicked>k__BackingField`

- `ILoadAsset <loader>k__BackingField`

- `Boolean m_hasInited`

- `RL04FragmentDetailCard m_detailCard`

- `IRoguelikeFragmentItemModel m_cachedModel`

- `RL04FragmentDetailWeightViewModel m_cachedWeightModel`

- `Int32 m_cachedLastIndex`

- `FadeSwitchTween m_nextBtnSwitchTween`

- `FadeSwitchTween m_prevBtnSwitchTween`

- `FadeSwitchTween m_useBtnSwitchTween`

- `Tween m_switchAnim`

- `Tween m_enterAnim`


## Properties

- `Action onNextBtnClicked`

- `Action onPrevBtnClicked`

- `Action onUseBtnClicked`

- `Action onDropBtnClicked`

- `ILoadAsset loader`


## Methods

- `Action get_onNextBtnClicked()`

- `Void set_onNextBtnClicked(Action)`

- `Action get_onPrevBtnClicked()`

- `Void set_onPrevBtnClicked(Action)`

- `Action get_onUseBtnClicked()`

- `Void set_onUseBtnClicked(Action)`

- `Action get_onDropBtnClicked()`

- `Void set_onDropBtnClicked(Action)`

- `ILoadAsset get_loader()`

- `Void set_loader(ILoadAsset)`

- `Void EventOnNextBtnClicked()`

- `Void EventOnPrevBtnClicked()`

- `Void EventOnUseBtnClicked()`

- `Void EventOnDropBtnClicked()`

- `Void _InitIfNot()`

- `Void _GeneratePrevAnim()`

- `Void _GenerateNextAnim()`

- `Void _KillSwitchAnimIfNecessary()`

- `Void _GenerateEnterAnim()`

- `Void _KillEnterAnimIfNecessary()`

- `Void <_GeneratePrevAnim>b__49_0()`

- `Void <_GenerateNextAnim>b__50_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentDetailView : DataBinder`1, IHotfixable
{
	private UIAnimationLocation _animPrevHide; // 0x20
	private UIAnimationLocation _animPrevShow; // 0x30
	private UIAnimationLocation _animNextHide; // 0x40
	private UIAnimationLocation _animNextShow; // 0x50
	private UIAnimationLocation _animEnter; // 0x60
	private RL04FragmentDetailCard _prefabDetailCard; // 0x70
	private RectTransform _cardContainer; // 0x78
	private RL04FragmentDetailWeightView _weightView; // 0x80
	private GameObject[] _panelCanUse; // 0x88
	private GameObject[] _panelCheckOnly; // 0x90
	private CanvasGroup _canvasGroupNextBtn; // 0x98
	private CanvasGroup _canvasGroupPrevBtn; // 0xa0
	private CanvasGroup _canvasGroupUseBtn; // 0xa8
	private Action <onNextBtnClicked>k__BackingField; // 0xb0
	private Action <onPrevBtnClicked>k__BackingField; // 0xb8
	private Action <onUseBtnClicked>k__BackingField; // 0xc0
	private Action <onDropBtnClicked>k__BackingField; // 0xc8
	private ILoadAsset <loader>k__BackingField; // 0xd0
	private Boolean m_hasInited; // 0xd8
	private RL04FragmentDetailCard m_detailCard; // 0xe0
	private IRoguelikeFragmentItemModel m_cachedModel; // 0xe8
	private RL04FragmentDetailWeightViewModel m_cachedWeightModel; // 0xf0
	private Int32 m_cachedLastIndex; // 0xf8
	private FadeSwitchTween m_nextBtnSwitchTween; // 0x100
	private FadeSwitchTween m_prevBtnSwitchTween; // 0x108
	private FadeSwitchTween m_useBtnSwitchTween; // 0x110
	private Tween m_switchAnim; // 0x118
	private Tween m_enterAnim; // 0x120
	private static DelegateBridge __Hotfix0_get_onNextBtnClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onNextBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onPrevBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onPrevBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onUseBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onUseBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0_get_onDropBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0_set_onDropBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0_get_loader; // 0x40
	private static DelegateBridge __Hotfix0_set_loader; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0_EventOnNextBtnClicked; // 0x58
	private static DelegateBridge __Hotfix0_EventOnPrevBtnClicked; // 0x60
	private static DelegateBridge __Hotfix0_EventOnUseBtnClicked; // 0x68
	private static DelegateBridge __Hotfix0_EventOnDropBtnClicked; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge __Hotfix0__GeneratePrevAnim; // 0x80
	private static DelegateBridge __Hotfix0__GenerateNextAnim; // 0x88
	private static DelegateBridge __Hotfix0__KillSwitchAnimIfNecessary; // 0x90
	private static DelegateBridge __Hotfix0__GenerateEnterAnim; // 0x98
	private static DelegateBridge __Hotfix0__KillEnterAnimIfNecessary; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	private Action onNextBtnClicked { get; set; }
	private Action onPrevBtnClicked { get; set; }
	private Action onUseBtnClicked { get; set; }
	private Action onDropBtnClicked { get; set; }
	private ILoadAsset loader { get; set; }

	// RVA: 0x2b213d8 VA: 0x75951393d8
	private Action get_onNextBtnClicked() { }
	// RVA: 0x2b2003c VA: 0x759513803c
	public Void set_onNextBtnClicked(Action value) { }
	// RVA: 0x2b21440 VA: 0x7595139440
	private Action get_onPrevBtnClicked() { }
	// RVA: 0x2b200c0 VA: 0x75951380c0
	public Void set_onPrevBtnClicked(Action value) { }
	// RVA: 0x2b214a8 VA: 0x75951394a8
	private Action get_onUseBtnClicked() { }
	// RVA: 0x2b20144 VA: 0x7595138144
	public Void set_onUseBtnClicked(Action value) { }
	// RVA: 0x2b21510 VA: 0x7595139510
	private Action get_onDropBtnClicked() { }
	// RVA: 0x2b201c8 VA: 0x75951381c8
	public Void set_onDropBtnClicked(Action value) { }
	// RVA: 0x2b21578 VA: 0x7595139578
	private ILoadAsset get_loader() { }
	// RVA: 0x2b2024c VA: 0x759513824c
	public Void set_loader(ILoadAsset value) { }
	// RVA: 0x2b215e0 VA: 0x75951395e0
	public override Void OnValueChanged(RL04FragmentDetailProperty property) { }
	// RVA: 0x2b22274 VA: 0x759513a274
	public Void EventOnNextBtnClicked() { }
	// RVA: 0x2b22310 VA: 0x759513a310
	public Void EventOnPrevBtnClicked() { }
	// RVA: 0x2b223ac VA: 0x759513a3ac
	public Void EventOnUseBtnClicked() { }
	// RVA: 0x2b22448 VA: 0x759513a448
	public Void EventOnDropBtnClicked() { }
	// RVA: 0x2b21950 VA: 0x7595139950
	private Void _InitIfNot() { }
	// RVA: 0x2b21f6c VA: 0x7595139f6c
	private Void _GeneratePrevAnim() { }
	// RVA: 0x2b220f0 VA: 0x759513a0f0
	private Void _GenerateNextAnim() { }
	// RVA: 0x2b224e4 VA: 0x759513a4e4
	private Void _KillSwitchAnimIfNecessary() { }
	// RVA: 0x2b21b30 VA: 0x7595139b30
	private Void _GenerateEnterAnim() { }
	// RVA: 0x2b22574 VA: 0x759513a574
	private Void _KillEnterAnimIfNecessary() { }
	// RVA: 0x2b22604 VA: 0x759513a604
	public Void .ctor() { }
	// RVA: 0x2b22694 VA: 0x759513a694
	private Void <_GeneratePrevAnim>b__49_0() { }
	// RVA: 0x2b226c4 VA: 0x759513a6c4
	private Void <_GenerateNextAnim>b__50_0() { }
}
```