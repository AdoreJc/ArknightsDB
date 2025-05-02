# MiniActReviewBinderView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `MiniActReviewListAdapter _reviewListAdapter`

- `UICommonTrackPoint _newTrialTrackPoint`

- `UICommonTrackPoint _collectTrialTrackPoint`

- `GameObject _trialBtnPanelGo`

- `LoopScrollRect _loopScrollRect`

- `GridLayoutGroup _itemGridLayout`

- `Action m_onBtnTrial`

- `Action m_onBtnRule`


## Properties

- `UICommonTrackPoint newTrialTrackPoint`

- `UICommonTrackPoint collectTrialTrackPoint`

- `GameObject trialBtnPanelGo`

- `LoopScrollRect loopScrollRect`

- `GridLayoutGroup itemGridLayout`


## Methods

- `UICommonTrackPoint get_newTrialTrackPoint()`

- `UICommonTrackPoint get_collectTrialTrackPoint()`

- `GameObject get_trialBtnPanelGo()`

- `LoopScrollRect get_loopScrollRect()`

- `GridLayoutGroup get_itemGridLayout()`

- `Void SetCallbacks(Action`1, Action`1, Action, Action)`

- `Void OnBtnTrial()`

- `Void OnBtnRule()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActReviewBinderView : DataBinder`1
{
	private MiniActReviewListAdapter _reviewListAdapter; // 0x20
	private UICommonTrackPoint _newTrialTrackPoint; // 0x28
	private UICommonTrackPoint _collectTrialTrackPoint; // 0x30
	private GameObject _trialBtnPanelGo; // 0x38
	private LoopScrollRect _loopScrollRect; // 0x40
	private GridLayoutGroup _itemGridLayout; // 0x48
	private Action m_onBtnTrial; // 0x50
	private Action m_onBtnRule; // 0x58
	private static DelegateBridge __Hotfix0_get_newTrialTrackPoint; // 0x0
	private static DelegateBridge __Hotfix0_get_collectTrialTrackPoint; // 0x8
	private static DelegateBridge __Hotfix0_get_trialBtnPanelGo; // 0x10
	private static DelegateBridge __Hotfix0_get_loopScrollRect; // 0x18
	private static DelegateBridge __Hotfix0_get_itemGridLayout; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0_SetCallbacks; // 0x30
	private static DelegateBridge __Hotfix0_OnBtnTrial; // 0x38
	private static DelegateBridge __Hotfix0_OnBtnRule; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public UICommonTrackPoint newTrialTrackPoint { get; }
	public UICommonTrackPoint collectTrialTrackPoint { get; }
	public GameObject trialBtnPanelGo { get; }
	public LoopScrollRect loopScrollRect { get; }
	public GridLayoutGroup itemGridLayout { get; }

	// RVA: 0x27480c4 VA: 0x7594d600c4
	public UICommonTrackPoint get_newTrialTrackPoint() { }
	// RVA: 0x274812c VA: 0x7594d6012c
	public UICommonTrackPoint get_collectTrialTrackPoint() { }
	// RVA: 0x2748194 VA: 0x7594d60194
	public GameObject get_trialBtnPanelGo() { }
	// RVA: 0x27481fc VA: 0x7594d601fc
	public LoopScrollRect get_loopScrollRect() { }
	// RVA: 0x2748264 VA: 0x7594d60264
	public GridLayoutGroup get_itemGridLayout() { }
	// RVA: 0x27482cc VA: 0x7594d602cc
	public override Void OnValueChanged(StoryReviewProperty property) { }
	// RVA: 0x2748394 VA: 0x7594d60394
	public Void SetCallbacks(Action`1 onReviewChapterClicked, Action`1 onChapterRewardsGain, Action onBtnTrial, Action onBtnRule) { }
	// RVA: 0x2748578 VA: 0x7594d60578
	public Void OnBtnTrial() { }
	// RVA: 0x27485fc VA: 0x7594d605fc
	public Void OnBtnRule() { }
	// RVA: 0x2748680 VA: 0x7594d60680
	public Void .ctor() { }
}
```