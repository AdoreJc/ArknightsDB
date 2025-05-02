# SixStarRuneSelectView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _textTotalGotPoint`

- `Text _textRewardTip`

- `GameObject _panelNextReward`

- `RectTransform _nextRewardCardContainer`

- `GameObject _panelMileStoneTrackPoint`

- `RectTransform _trackPointContainer`

- `SimpleLayoutContent _content`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `UIItemCard m_rewardCard`

- `UICompDialogFinder m_dialogFinder`


## Methods

- `Void EventOnConfirmBtnClicked()`

- `Void EventOnMilestoneBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarRuneSelectView : DataBinder`1, IHotfixable
{
	private const Single ITEM_CARD_SCALE; // 0x0
	private Text _textTotalGotPoint; // 0x20
	private Text _textRewardTip; // 0x28
	private GameObject _panelNextReward; // 0x30
	private RectTransform _nextRewardCardContainer; // 0x38
	private GameObject _panelMileStoneTrackPoint; // 0x40
	private RectTransform _trackPointContainer; // 0x48
	private SimpleLayoutContent _content; // 0x50
	private List`1 m_cachedRuneGroupModel; // 0x58
	private Boolean m_hasInited; // 0x60
	private Adapter m_adapter; // 0x68
	private UIItemCard m_rewardCard; // 0x70
	private UICompDialogFinder m_dialogFinder; // 0x78
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnConfirmBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnMilestoneBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f4ffc0 VA: 0x7595567fc0
	public override Void OnValueChanged(SixStarRuneSelectProperty property) { }
	// RVA: 0x2f50384 VA: 0x7595568384
	public Void EventOnConfirmBtnClicked() { }
	// RVA: 0x2f50428 VA: 0x7595568428
	public Void EventOnMilestoneBtnClicked() { }
	// RVA: 0x2f5010c VA: 0x759556810c
	private Void _InitIfNot() { }
	// RVA: 0x2f50560 VA: 0x7595568560
	public Void .ctor() { }
}
```