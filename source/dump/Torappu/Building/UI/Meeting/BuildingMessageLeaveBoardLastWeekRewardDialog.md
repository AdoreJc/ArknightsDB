# BuildingMessageLeaveBoardLastWeekRewardDialog

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `CanvasGroup _canvasGroup`

- `Text _textRecord`

- `Text _rewardTip`

- `RectTransform _itemCardContainer`

- `UIAnimationLocation _animEntry`

- `UIFullScreenImage _fullScreenImage`

- `GameObject _panelLastWeekReward`

- `ItemBundle m_rewardSocialPointItem`

- `Boolean m_canClick`

- `Tween m_inOutTween`

- `UIItemViewModel m_itemViewModel`

- `Int32 m_lastWeekReward`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`


## Methods

- `Void _InitIfNot()`

- `Void _SetRewardItemModel(Int32)`

- `IEnumerator _PlayEntryAnim()`

- `IEnumerator _PlayLeaveAnim()`

- `Void _RenderRewardItem(BuildingMessageLeaveBoardModel)`

- `String _GetLastWeekTime()`

- `Void EventOnBgClicked()`

- `Boolean <_PlayEntryAnim>b__19_0()`

- `Boolean <_PlayLeaveAnim>b__20_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMessageLeaveBoardLastWeekRewardDialog : UICompDialog`1, IHotfixable
{
	private const Single FADE_DURATION; // 0x0
	private CanvasGroup _canvasGroup; // 0x48
	private Text _textRecord; // 0x50
	private Text _rewardTip; // 0x58
	private RectTransform _itemCardContainer; // 0x60
	private UIAnimationLocation _animEntry; // 0x68
	private UIFullScreenImage _fullScreenImage; // 0x78
	private GameObject _panelLastWeekReward; // 0x80
	private ItemBundle m_rewardSocialPointItem; // 0x88
	private Boolean m_canClick; // 0x90
	private Tween m_inOutTween; // 0x98
	private UIItemViewModel m_itemViewModel; // 0xa0
	private Int32 m_lastWeekReward; // 0xa8
	private Boolean m_isInited; // 0xac
	private UIItemCard m_itemCard; // 0xb0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__SetRewardItemModel; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x18
	private static DelegateBridge __Hotfix0__PlayLeaveAnim; // 0x20
	private static DelegateBridge __Hotfix0__RenderRewardItem; // 0x28
	private static DelegateBridge __Hotfix0__GetLastWeekTime; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBgClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3dc4fac VA: 0x75963dcfac
	private Void _InitIfNot() { }
	// RVA: 0x3dc51c0 VA: 0x75963dd1c0
	private Void _SetRewardItemModel(Int32 rewardNum) { }
	// RVA: 0x3dc52b8 VA: 0x75963dd2b8
	protected override Void OnRender(Input input) { }
	// RVA: 0x3dc5984 VA: 0x75963dd984
	private IEnumerator _PlayEntryAnim() { }
	// RVA: 0x3dc5a58 VA: 0x75963dda58
	private IEnumerator _PlayLeaveAnim() { }
	// RVA: 0x3dc55ec VA: 0x75963dd5ec
	private Void _RenderRewardItem(BuildingMessageLeaveBoardModel msgBoardModel) { }
	// RVA: 0x3dc5710 VA: 0x75963dd710
	private String _GetLastWeekTime() { }
	// RVA: 0x3dc5b2c VA: 0x75963ddb2c
	public Void EventOnBgClicked() { }
	// RVA: 0x3dc5bec VA: 0x75963ddbec
	public Void .ctor() { }
	// RVA: 0x3dc5cf8 VA: 0x75963ddcf8
	private Boolean <_PlayEntryAnim>b__19_0() { }
	// RVA: 0x3dc5d0c VA: 0x75963ddd0c
	private Boolean <_PlayLeaveAnim>b__20_0() { }
}
```