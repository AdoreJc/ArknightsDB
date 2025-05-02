# RoguelikeTopicMonthTaskItemView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `UIAtlasImage _imgBg`

- `Text _textTaskName`

- `Text _textTaskDesc`

- `Text _textProgress`

- `Slider _sliderProgress`

- `Text _textRewardCount`

- `Text _textRewardName`

- `Image _imgRewardIcon`

- `UIAnimationLocation _refreshAnim`

- `GameObject _activeContentGo`

- `Button _btnRefresh`

- `AudioClickPlayer _btnAudioPlayer`

- `Selectable _rewardColor`

- `GameObject _completeNode`

- `GameObject _refreshBtnNode`

- `UIAtlasObject _atlas`

- `UIPageFinder m_pageFinder`

- `RoguelikeTopicMonthTaskModel m_taskModel`

- `RoguelikeTopicMonthTaskListModel m_taskListModel`

- `RoguelikeTopicMonthTaskStyle m_taskStyle`

- `Tween m_prgTween`

- `CompleteType <completeType>k__BackingField`


## Properties

- `CompleteType completeType`


## Methods

- `Void set_onTaskRefreshAction(Action`1)`

- `Void Render(RoguelikeTopicMonthTaskListModel, RoguelikeTopicMonthTaskModel)`

- `Void TweenPrgTo(RoguelikeTopicMonthTaskListModel, RoguelikeTopicMonthTaskModel, Single)`

- `Void _DoneTween()`

- `Single _GetPrg()`

- `Void _SetPrg(Single)`

- `Void PlayRefreshAnim()`

- `Void SetRefreshBtnVisible(Boolean)`

- `CompleteType get_completeType()`

- `Void set_completeType(CompleteType)`

- `Void _RefreshTask()`

- `Void OnBtnRefreshClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthTaskItemView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imgBg; // 0x18
	private Text _textTaskName; // 0x20
	private Text _textTaskDesc; // 0x28
	private Text _textProgress; // 0x30
	private Slider _sliderProgress; // 0x38
	private Text _textRewardCount; // 0x40
	private Text _textRewardName; // 0x48
	private Image _imgRewardIcon; // 0x50
	private UIAnimationLocation _refreshAnim; // 0x58
	private GameObject _activeContentGo; // 0x68
	private Button _btnRefresh; // 0x70
	private AudioClickPlayer _btnAudioPlayer; // 0x78
	private Selectable _rewardColor; // 0x80
	private GameObject _completeNode; // 0x88
	private GameObject _refreshBtnNode; // 0x90
	private UIAtlasObject _atlas; // 0x98
	private UIPageFinder m_pageFinder; // 0xa0
	private const String TASK_BG_END; // 0x0
	private RoguelikeTopicMonthTaskModel m_taskModel; // 0xb0
	private RoguelikeTopicMonthTaskListModel m_taskListModel; // 0xb8
	private RoguelikeTopicMonthTaskStyle m_taskStyle; // 0xc0
	private Tween m_prgTween; // 0xc8
	private Action`1 <onTaskRefreshAction>k__BackingField; // 0xd0
	private CompleteType <completeType>k__BackingField; // 0xd8
	private static DelegateBridge __Hotfix0_get_onTaskRefreshAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onTaskRefreshAction; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_TweenPrgTo; // 0x18
	private static DelegateBridge __Hotfix0__DoneTween; // 0x20
	private static DelegateBridge __Hotfix0__GetPrg; // 0x28
	private static DelegateBridge __Hotfix0__SetPrg; // 0x30
	private static DelegateBridge __Hotfix0_PlayRefreshAnim; // 0x38
	private static DelegateBridge __Hotfix0_SetRefreshBtnVisible; // 0x40
	private static DelegateBridge __Hotfix0_get_completeType; // 0x48
	private static DelegateBridge __Hotfix0_set_completeType; // 0x50
	private static DelegateBridge __Hotfix0__RefreshTask; // 0x58
	private static DelegateBridge __Hotfix0_OnBtnRefreshClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private Action`1 onTaskRefreshAction { get; set; }
	public CompleteType completeType { get; set; }

	// RVA: 0x26572a0 VA: 0x7594c6f2a0
	private Action`1 get_onTaskRefreshAction() { }
	// RVA: 0x2657308 VA: 0x7594c6f308
	public Void set_onTaskRefreshAction(Action`1 value) { }
	// RVA: 0x265738c VA: 0x7594c6f38c
	public Void Render(RoguelikeTopicMonthTaskListModel taskListModel, RoguelikeTopicMonthTaskModel taskModel) { }
	// RVA: 0x265795c VA: 0x7594c6f95c
	public Void TweenPrgTo(RoguelikeTopicMonthTaskListModel taskListModel, RoguelikeTopicMonthTaskModel taskModel, Single dur) { }
	// RVA: 0x2657ce8 VA: 0x7594c6fce8
	private Void _DoneTween() { }
	// RVA: 0x2657d54 VA: 0x7594c6fd54
	private Single _GetPrg() { }
	// RVA: 0x2657dd0 VA: 0x7594c6fdd0
	private Void _SetPrg(Single v) { }
	// RVA: 0x2657fec VA: 0x7594c6ffec
	public Void PlayRefreshAnim() { }
	// RVA: 0x265807c VA: 0x7594c7007c
	public Void SetRefreshBtnVisible(Boolean v) { }
	// RVA: 0x26578f4 VA: 0x7594c6f8f4
	public CompleteType get_completeType() { }
	// RVA: 0x2658100 VA: 0x7594c70100
	public Void set_completeType(CompleteType value) { }
	// RVA: 0x265817c VA: 0x7594c7017c
	private Void _RefreshTask() { }
	// RVA: 0x2658224 VA: 0x7594c70224
	public Void OnBtnRefreshClick() { }
	// RVA: 0x26584cc VA: 0x7594c704cc
	public Void .ctor() { }
}
```