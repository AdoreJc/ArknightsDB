# MiniActTrialItemView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `GameObject _closePartGo`

- `Image _imgStoryBg`

- `GameObject _commingPartGo`

- `Text _textCountDown`

- `GameObject _lockedPartGo`

- `GameObject _openPartGo`

- `Image _imgTrialTitle`

- `GameObject _rewardCollectGo`

- `GameObject _rewardCompleteGo`

- `Image _imgRewardCollectBg`

- `Text _textCollectReward`

- `Text _textTotalReward`

- `Text _textUnlockStory`

- `Text _textTotalStory`

- `GameObject _btnCollectAllGo`

- `GameObject _btnNavStoryGo`

- `GameObject _storyUnlockStatusGo`

- `Text _textNavCaption`

- `SimpleLayoutContent _rewardListContent`

- `GameObject _newTrackPointGo`

- `UIWrappedScrollRect _rewardScroll`

- `Boolean m_hasInited`

- `MiniActTrialItemModel m_itemModel`

- `RewardListAdpater m_rewardListAdapter`


## Methods

- `Void set_onChapterClick(Action`1)`

- `Void set_onTrialCollect(Action`2)`

- `Void BindNestedScroll(IDragHandler)`

- `Void Render(MiniActTrialItemModel)`

- `Void _InitIfNot()`

- `Void _RenderCloseView(MiniActTrialItemModel)`

- `Void _RenderCommingView(MiniActTrialItemModel)`

- `Void _RenderOpenView(MiniActTrialItemModel)`

- `Void OnBtnNavToStory()`

- `Void OnBtnCollectAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActTrialItemView : MonoBehaviour, IHotfixable
{
	private GameObject _closePartGo; // 0x18
	private Image _imgStoryBg; // 0x20
	private GameObject _commingPartGo; // 0x28
	private Text _textCountDown; // 0x30
	private GameObject _lockedPartGo; // 0x38
	private GameObject _openPartGo; // 0x40
	private Image _imgTrialTitle; // 0x48
	private GameObject _rewardCollectGo; // 0x50
	private GameObject _rewardCompleteGo; // 0x58
	private Image _imgRewardCollectBg; // 0x60
	private Text _textCollectReward; // 0x68
	private Text _textTotalReward; // 0x70
	private Text _textUnlockStory; // 0x78
	private Text _textTotalStory; // 0x80
	private GameObject _btnCollectAllGo; // 0x88
	private GameObject _btnNavStoryGo; // 0x90
	private GameObject _storyUnlockStatusGo; // 0x98
	private Text _textNavCaption; // 0xa0
	private SimpleLayoutContent _rewardListContent; // 0xa8
	private GameObject _newTrackPointGo; // 0xb0
	private UIWrappedScrollRect _rewardScroll; // 0xb8
	private Boolean m_hasInited; // 0xc0
	private MiniActTrialItemModel m_itemModel; // 0xc8
	private RewardListAdpater m_rewardListAdapter; // 0xd0
	private Action`1 <onChapterClick>k__BackingField; // 0xd8
	private Action`2 <onTrialCollect>k__BackingField; // 0xe0
	private static DelegateBridge __Hotfix0_get_onChapterClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onChapterClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onTrialCollect; // 0x10
	private static DelegateBridge __Hotfix0_set_onTrialCollect; // 0x18
	private static DelegateBridge __Hotfix0_BindNestedScroll; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__RenderCloseView; // 0x38
	private static DelegateBridge __Hotfix0__RenderCommingView; // 0x40
	private static DelegateBridge __Hotfix0__RenderOpenView; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnNavToStory; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnCollectAll; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Action`1 onChapterClick { get; set; }
	private Action`2 onTrialCollect { get; set; }

	// RVA: 0x274909c VA: 0x7594d6109c
	private Action`1 get_onChapterClick() { }
	// RVA: 0x2749104 VA: 0x7594d61104
	public Void set_onChapterClick(Action`1 value) { }
	// RVA: 0x2749188 VA: 0x7594d61188
	private Action`2 get_onTrialCollect() { }
	// RVA: 0x27491f0 VA: 0x7594d611f0
	public Void set_onTrialCollect(Action`2 value) { }
	// RVA: 0x2749274 VA: 0x7594d61274
	public Void BindNestedScroll(IDragHandler scroll) { }
	// RVA: 0x2749300 VA: 0x7594d61300
	public Void Render(MiniActTrialItemModel itemModel) { }
	// RVA: 0x274948c VA: 0x7594d6148c
	private Void _InitIfNot() { }
	// RVA: 0x27495e0 VA: 0x7594d615e0
	private Void _RenderCloseView(MiniActTrialItemModel itemModel) { }
	// RVA: 0x27496e4 VA: 0x7594d616e4
	private Void _RenderCommingView(MiniActTrialItemModel itemModel) { }
	// RVA: 0x2749800 VA: 0x7594d61800
	private Void _RenderOpenView(MiniActTrialItemModel itemModel) { }
	// RVA: 0x274a540 VA: 0x7594d62540
	public Void OnBtnNavToStory() { }
	// RVA: 0x274a5f0 VA: 0x7594d625f0
	public Void OnBtnCollectAll() { }
	// RVA: 0x274a870 VA: 0x7594d62870
	public Void .ctor() { }
}
```