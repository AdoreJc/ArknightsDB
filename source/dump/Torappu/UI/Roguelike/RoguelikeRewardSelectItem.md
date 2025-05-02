# RoguelikeRewardSelectItem

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _itemTitle`

- `Image _recruitIcon`

- `Text _description`

- `Text _shortDesc`

- `Text _titleText`

- `GameObject _extraInfoObj`

- `Text _extraInfoText`

- `Image _imgButton`

- `Image _imgTextBg`

- `Image _itemBg`

- `GameObject _objBtn`

- `GameObject _objBtnHideTips`

- `Image _imgHideBg`

- `Text _btnHideTxt`

- `Button _btn`

- `UIIntEvent onClickEvent`

- `RoguelikeRewardStyle <uiStyle>k__BackingField`

- `RoguelikeSortItemViewStruct m_cacheViewStruct`

- `UIPageFinder m_pageFinder`


## Properties

- `RoguelikeRewardStyle uiStyle`


## Methods

- `RoguelikeRewardStyle get_uiStyle()`

- `Void set_uiStyle(RoguelikeRewardStyle)`

- `Void OnClick()`

- `Void RenderCard(RoguelikeSortItemViewStruct)`

- `Void _SetCommonItemInfo(RoguelikeRewardShowType, RoguelikeTopicItemModel)`

- `Void _SetClickable(Boolean)`

- `Void _SetStyle(RoguelikeGameItemType, RoguelikeRewardShowType)`

- `Void _SetInfo(RoguelikeSortItemViewStruct)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardSelectItem : MonoBehaviour, IHotfixable
{
	private Text _itemTitle; // 0x18
	private Image _recruitIcon; // 0x20
	private Text _description; // 0x28
	private Text _shortDesc; // 0x30
	private Text _titleText; // 0x38
	private GameObject _extraInfoObj; // 0x40
	private Text _extraInfoText; // 0x48
	private Image _imgButton; // 0x50
	private Image _imgTextBg; // 0x58
	private Image _itemBg; // 0x60
	private GameObject _objBtn; // 0x68
	private GameObject _objBtnHideTips; // 0x70
	private Image _imgHideBg; // 0x78
	private Text _btnHideTxt; // 0x80
	private Button _btn; // 0x88
	private ItemIconConfig[] _itemIconConfigs; // 0x90
	public UIIntEvent onClickEvent; // 0x98
	private RoguelikeRewardStyle <uiStyle>k__BackingField; // 0xa0
	private RoguelikeSortItemViewStruct m_cacheViewStruct; // 0xa8
	private UIPageFinder m_pageFinder; // 0x150
	private static DelegateBridge __Hotfix0_get_uiStyle; // 0x0
	private static DelegateBridge __Hotfix0_set_uiStyle; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_RenderCard; // 0x18
	private static DelegateBridge __Hotfix0__SetCommonItemInfo; // 0x20
	private static DelegateBridge __Hotfix0__SetClickable; // 0x28
	private static DelegateBridge __Hotfix0__SetStyle; // 0x30
	private static DelegateBridge __Hotfix0__SetInfo; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public RoguelikeRewardStyle uiStyle { get; set; }

	// RVA: 0x2aa099c VA: 0x75950b899c
	public RoguelikeRewardStyle get_uiStyle() { }
	// RVA: 0x2aa0a04 VA: 0x75950b8a04
	public Void set_uiStyle(RoguelikeRewardStyle value) { }
	// RVA: 0x2aa0a88 VA: 0x75950b8a88
	public Void OnClick() { }
	// RVA: 0x2aa0b2c VA: 0x75950b8b2c
	public Void RenderCard(RoguelikeSortItemViewStruct viewStruct) { }
	// RVA: 0x2aa0f30 VA: 0x75950b8f30
	private Void _SetCommonItemInfo(RoguelikeRewardShowType rewardShowType, RoguelikeTopicItemModel itemData) { }
	// RVA: 0x2aa0c64 VA: 0x75950b8c64
	private Void _SetClickable(Boolean canClick) { }
	// RVA: 0x2aa0d3c VA: 0x75950b8d3c
	private Void _SetStyle(RoguelikeGameItemType type, RoguelikeRewardShowType showType) { }
	// RVA: 0x2aa1170 VA: 0x75950b9170
	private Void _SetInfo(RoguelikeSortItemViewStruct viewStruct) { }
	// RVA: 0x2aa1508 VA: 0x75950b9508
	public Void .ctor() { }
}
```