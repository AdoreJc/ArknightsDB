# Act1BossRushMileStoneView

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `Act1BossRushMileStoneItemGridAdapter _adapter`

- `LoopHorizontalScrollRect _content`

- `GridLayoutGroup _layout`

- `TwoStateToggle _toggleReceiveAll`

- `Text _textLevelCurr`

- `Text _textPointProgress`

- `Slider _sliderPoint`

- `TwoStateToggle _toggleAllComplete`

- `Act1BossRushMileStoneRewardInfoPlugin _rewardInfoPlugin`

- `TweenWrapper m_focusTween`

- `Action <onGetAllClick>k__BackingField`


## Properties

- `Action onGetAllClick`


## Methods

- `Action get_onGetAllClick()`

- `Void set_onGetAllClick(Action)`

- `Void set_onItemClick(Action`1)`

- `Void OnGetAllClick()`

- `Void FocusOnIdx(Int32)`

- `Single <FocusOnIdx>b__23_0()`

- `Void <FocusOnIdx>b__23_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushMileStoneView : DataBinder`1, IHotfixable
{
	private const String FORMAT_POINT_PROGRESS; // 0x0
	private const Single FOCUS_DURATION; // 0x0
	private const Int32 SLIDE_MAX_LENGTH; // 0x0
	private Act1BossRushMileStoneItemGridAdapter _adapter; // 0x20
	private LoopHorizontalScrollRect _content; // 0x28
	private GridLayoutGroup _layout; // 0x30
	private TwoStateToggle _toggleReceiveAll; // 0x38
	private Text _textLevelCurr; // 0x40
	private Text _textPointProgress; // 0x48
	private Slider _sliderPoint; // 0x50
	private TwoStateToggle _toggleAllComplete; // 0x58
	private Act1BossRushMileStoneRewardInfoPlugin _rewardInfoPlugin; // 0x60
	private TweenWrapper m_focusTween; // 0x68
	private Action <onGetAllClick>k__BackingField; // 0x70
	private Action`1 <onItemClick>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onGetAllClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onGetAllClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnGetAllClick; // 0x28
	private static DelegateBridge __Hotfix0_FocusOnIdx; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action onGetAllClick { get; set; }
	private Action`1 onItemClick { get; set; }

	// RVA: 0x3194534 VA: 0x75957ac534
	private Action get_onGetAllClick() { }
	// RVA: 0x31931b0 VA: 0x75957ab1b0
	public Void set_onGetAllClick(Action value) { }
	// RVA: 0x319459c VA: 0x75957ac59c
	private Action`1 get_onItemClick() { }
	// RVA: 0x319312c VA: 0x75957ab12c
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x3194604 VA: 0x75957ac604
	public override Void OnValueChanged(Act1BossRushMileStoneProperty property) { }
	// RVA: 0x3194888 VA: 0x75957ac888
	public Void OnGetAllClick() { }
	// RVA: 0x3193774 VA: 0x75957ab774
	public Void FocusOnIdx(Int32 targetIndex) { }
	// RVA: 0x3194934 VA: 0x75957ac934
	public Void .ctor() { }
	// RVA: 0x31949c4 VA: 0x75957ac9c4
	private Single <FocusOnIdx>b__23_0() { }
	// RVA: 0x31949e0 VA: 0x75957ac9e0
	private Void <FocusOnIdx>b__23_1(Single value) { }
}
```