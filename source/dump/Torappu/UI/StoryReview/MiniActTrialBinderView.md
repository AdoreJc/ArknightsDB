# MiniActTrialBinderView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `MiniActTrialListAdapter _trialListAdapter`

- `UICommonTrackPoint _reviewRewardTrackPoint`

- `LoopScrollRect _loopScrollRect`

- `Action m_onBtnReview`

- `Action m_onBtnRule`


## Properties

- `UICommonTrackPoint reviewRewardTrackPoint`

- `LoopScrollRect loopScrollRect`


## Methods

- `UICommonTrackPoint get_reviewRewardTrackPoint()`

- `LoopScrollRect get_loopScrollRect()`

- `Void SetCallbacks(Action`1, Action`2, Action, Action)`

- `Void OnBtnReview()`

- `Void OnBtnRule()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActTrialBinderView : DataBinder`1
{
	private MiniActTrialListAdapter _trialListAdapter; // 0x20
	private UICommonTrackPoint _reviewRewardTrackPoint; // 0x28
	private LoopScrollRect _loopScrollRect; // 0x30
	private Action m_onBtnReview; // 0x38
	private Action m_onBtnRule; // 0x40
	private static DelegateBridge __Hotfix0_get_reviewRewardTrackPoint; // 0x0
	private static DelegateBridge __Hotfix0_get_loopScrollRect; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnReview; // 0x20
	private static DelegateBridge __Hotfix0_OnBtnRule; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public UICommonTrackPoint reviewRewardTrackPoint { get; }
	public LoopScrollRect loopScrollRect { get; }

	// RVA: 0x2748b00 VA: 0x7594d60b00
	public UICommonTrackPoint get_reviewRewardTrackPoint() { }
	// RVA: 0x2748b68 VA: 0x7594d60b68
	public LoopScrollRect get_loopScrollRect() { }
	// RVA: 0x2748bd0 VA: 0x7594d60bd0
	public override Void OnValueChanged(MiniActTrialProperty property) { }
	// RVA: 0x2748d20 VA: 0x7594d60d20
	public Void SetCallbacks(Action`1 onChapterClicked, Action`2 onTrialCollect, Action onBtnReview, Action onBtnRule) { }
	// RVA: 0x2748f04 VA: 0x7594d60f04
	public Void OnBtnReview() { }
	// RVA: 0x2748f88 VA: 0x7594d60f88
	public Void OnBtnRule() { }
	// RVA: 0x274900c VA: 0x7594d6100c
	public Void .ctor() { }
}
```