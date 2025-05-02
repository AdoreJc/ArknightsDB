# UIItemCard

**Namespace:** `Torappu.UI`


## Fields

- `Text _textMatNum`

- `Image _imageMatBkg`

- `Image _imageMatIcon`

- `GameObject _panelMatNum`

- `Image _imageFurniBkg`

- `Image _imageFurniIcon`

- `Image _imageCharAvatar`

- `Image _imageCharBkg`

- `GameObject _panelChar`

- `Graphic _cardRaycaster`

- `AudioClickPlayer _clickAudio`

- `Text _textItemName`

- `UILongPressButton _button`

- `Button _colorHandler`

- `GameObject _panelItemName`

- `Sprite _bkgMatR1`

- `Sprite _bkgMatR2`

- `Sprite _bkgMatR3`

- `Sprite _bkgMatR4`

- `Sprite _bkgMatR5`

- `Sprite _bkgMatR6`

- `Sprite _bkgFurniR1`

- `Sprite _bkgFurniR2`

- `Sprite _bkgCharR1`

- `Sprite _bkgCharR2`

- `Sprite _bkgCharR3`

- `Sprite _bkgCharR4`

- `Sprite _bkgCharR5`

- `Sprite _bkgCharR6`

- `GameObject _panelSkin`

- `Image _imageSkin`

- `GameObject _panelPlayerAvatar`

- `Image _imagePlayerAvatar`

- `Image _imageCharmBkg`

- `Image _imageCharmIcon`

- `Image _imageMedalBkg`

- `Image _imageMedalIcon`

- `GameObject _panelBackGround`

- `Image _imageBackGround`

- `Transform _countDownContainer`

- `UIItemTimeCountDown _countDownTimeItem`

- `UIItemTimeCountDown m_countDownItem`

- `Int32 m_itemIndexCache`

- `UIItemViewModel m_itemModelCache`

- `Boolean m_isInited`

- `Boolean m_showItemNumByOption`

- `Boolean m_showItemEmptyNum`

- `ViewCache m_viewCache`

- `Boolean m_showItemName`

- `Boolean m_showBackground`

- `Boolean m_enableValidTime`

- `Boolean m_isWatchingTime`


## Properties

- `UIItemViewModel model`

- `Color mainColor`

- `Boolean enableValidTime`

- `Boolean showItemNum`

- `Boolean showItemEmptyNum`

- `Boolean showItemName`

- `Boolean showBackground`

- `Boolean isCardClickable`

- `Boolean enableCardClickAudio`


## Methods

- `UIItemViewModel get_model()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void Render(Int32, UIItemViewModel)`

- `Void _InitIfNot()`

- `Void CloseBtnTransition()`

- `Color get_mainColor()`

- `Void set_mainColor(Color)`

- `Boolean get_enableValidTime()`

- `Void set_enableValidTime(Boolean)`

- `Boolean get_showItemNum()`

- `Void set_showItemNum(Boolean)`

- `Boolean get_showItemEmptyNum()`

- `Void set_showItemEmptyNum(Boolean)`

- `Boolean get_showItemName()`

- `Void set_showItemName(Boolean)`

- `Boolean get_showBackground()`

- `Void set_showBackground(Boolean)`

- `Boolean get_isCardClickable()`

- `Void set_isCardClickable(Boolean)`

- `Boolean get_enableCardClickAudio()`

- `Void set_enableCardClickAudio(Boolean)`

- `Void OnScaleChange(Single)`

- `Void EventOnReduceBtnClick()`

- `Void _OnItemClicked()`

- `Boolean _OnItemLongPressed()`

- `Void _OnValidTimeExcceeded()`

- `Sprite _GetMaterialBkgSprite(UIItemViewModel)`

- `Sprite _GetCharBkgSprite(UIItemViewModel)`

- `Sprite _GetFurnitureBkgSprite(UIItemViewModel)`

- `Sprite _GetCharmBkgSprite(UIItemViewModel)`

- `Void _UpdateNameShowState()`

- `Void _UpdateBackgroundShowState()`

- `Void _UpdateItemNumVisibleState()`

- `Boolean _CheckIfNoCountType(ItemType)`

- `Void _UpdateValidTimeSystem(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemCard : MonoBehaviour, IItemCard, IHotfixable
{
	private const Int32 FURNI_RARITY_LOW; // 0x0
	private static readonly Color COLOR_ZERO_COUNT; // 0x0
	private static ItemType[] NO_COUNT_TYPE_GROUP; // 0x10
	private const Int32 LARGE_ITEM_NUM; // 0x0
	private Text _textMatNum; // 0x18
	private Image _imageMatBkg; // 0x20
	private Image _imageMatIcon; // 0x28
	private GameObject _panelMatNum; // 0x30
	private Image _imageFurniBkg; // 0x38
	private Image _imageFurniIcon; // 0x40
	private Image _imageCharAvatar; // 0x48
	private Image _imageCharBkg; // 0x50
	private GameObject _panelChar; // 0x58
	private Graphic _cardRaycaster; // 0x60
	private AudioClickPlayer _clickAudio; // 0x68
	private Text _textItemName; // 0x70
	private UILongPressButton _button; // 0x78
	private Button _colorHandler; // 0x80
	private GameObject _panelItemName; // 0x88
	private Sprite _bkgMatR1; // 0x90
	private Sprite _bkgMatR2; // 0x98
	private Sprite _bkgMatR3; // 0xa0
	private Sprite _bkgMatR4; // 0xa8
	private Sprite _bkgMatR5; // 0xb0
	private Sprite _bkgMatR6; // 0xb8
	private Sprite _bkgFurniR1; // 0xc0
	private Sprite _bkgFurniR2; // 0xc8
	private Sprite _bkgCharR1; // 0xd0
	private Sprite _bkgCharR2; // 0xd8
	private Sprite _bkgCharR3; // 0xe0
	private Sprite _bkgCharR4; // 0xe8
	private Sprite _bkgCharR5; // 0xf0
	private Sprite _bkgCharR6; // 0xf8
	private GameObject _panelSkin; // 0x100
	private Image _imageSkin; // 0x108
	private GameObject _panelPlayerAvatar; // 0x110
	private Image _imagePlayerAvatar; // 0x118
	private Image _imageCharmBkg; // 0x120
	private Image _imageCharmIcon; // 0x128
	private Sprite[] _charmBkgs; // 0x130
	private Image _imageMedalBkg; // 0x138
	private Image _imageMedalIcon; // 0x140
	private GameObject _panelBackGround; // 0x148
	private Image _imageBackGround; // 0x150
	private Transform _countDownContainer; // 0x158
	private UIItemTimeCountDown _countDownTimeItem; // 0x160
	private UIItemTimeCountDown m_countDownItem; // 0x168
	private Int32 m_itemIndexCache; // 0x170
	private UIItemViewModel m_itemModelCache; // 0x178
	private Boolean m_isInited; // 0x180
	private Boolean m_showItemNumByOption; // 0x181
	private Boolean m_showItemEmptyNum; // 0x182
	private ViewCache m_viewCache; // 0x188
	private Boolean m_showItemName; // 0x1a0
	private Boolean m_showBackground; // 0x1a1
	private Boolean m_enableValidTime; // 0x1a2
	private Boolean m_isWatchingTime; // 0x1a3
	public Action`1 onItemClick; // 0x1a8
	public Func`2 onItemLongPressed; // 0x1b0
	public Action`1 onBtnReduceClick; // 0x1b8
	public Action`1 onItemTimeout; // 0x1c0
	private static DelegateBridge __Hotfix0_get_model; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_OnDisable; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_CloseBtnTransition; // 0x40
	private static DelegateBridge __Hotfix0_get_mainColor; // 0x48
	private static DelegateBridge __Hotfix0_set_mainColor; // 0x50
	private static DelegateBridge __Hotfix0_get_enableValidTime; // 0x58
	private static DelegateBridge __Hotfix0_set_enableValidTime; // 0x60
	private static DelegateBridge __Hotfix0_get_showItemNum; // 0x68
	private static DelegateBridge __Hotfix0_set_showItemNum; // 0x70
	private static DelegateBridge __Hotfix0_get_showItemEmptyNum; // 0x78
	private static DelegateBridge __Hotfix0_set_showItemEmptyNum; // 0x80
	private static DelegateBridge __Hotfix0_get_showItemName; // 0x88
	private static DelegateBridge __Hotfix0_set_showItemName; // 0x90
	private static DelegateBridge __Hotfix0_get_showBackground; // 0x98
	private static DelegateBridge __Hotfix0_set_showBackground; // 0xa0
	private static DelegateBridge __Hotfix0_get_isCardClickable; // 0xa8
	private static DelegateBridge __Hotfix0_set_isCardClickable; // 0xb0
	private static DelegateBridge __Hotfix0_get_enableCardClickAudio; // 0xb8
	private static DelegateBridge __Hotfix0_set_enableCardClickAudio; // 0xc0
	private static DelegateBridge __Hotfix0_OnScaleChange; // 0xc8
	private static DelegateBridge __Hotfix0_EventOnReduceBtnClick; // 0xd0
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0xd8
	private static DelegateBridge __Hotfix0__OnItemLongPressed; // 0xe0
	private static DelegateBridge __Hotfix0__OnValidTimeExcceeded; // 0xe8
	private static DelegateBridge __Hotfix0_ParseItemCount; // 0xf0
	private static DelegateBridge __Hotfix0__GetMaterialBkgSprite; // 0xf8
	private static DelegateBridge __Hotfix0__GetCharBkgSprite; // 0x100
	private static DelegateBridge __Hotfix0__GetFurnitureBkgSprite; // 0x108
	private static DelegateBridge __Hotfix0__GetCharmBkgSprite; // 0x110
	private static DelegateBridge __Hotfix0__UpdateNameShowState; // 0x118
	private static DelegateBridge __Hotfix0__UpdateBackgroundShowState; // 0x120
	private static DelegateBridge __Hotfix0__UpdateItemNumVisibleState; // 0x128
	private static DelegateBridge __Hotfix0__CheckIfNoCountType; // 0x130
	private static DelegateBridge __Hotfix0__UpdateValidTimeSystem; // 0x138
	private static DelegateBridge _c__Hotfix0_ctor; // 0x140

	public UIItemViewModel model { get; }
	public Color mainColor { get; set; }
	public Boolean enableValidTime { get; set; }
	public Boolean showItemNum { get; set; }
	public Boolean showItemEmptyNum { get; set; }
	public Boolean showItemName { get; set; }
	public Boolean showBackground { get; set; }
	public Boolean isCardClickable { get; set; }
	public Boolean enableCardClickAudio { get; set; }

	// RVA: 0x218a180 VA: 0x75947a2180
	public UIItemViewModel get_model() { }
	// RVA: 0x218a1f8 VA: 0x75947a21f8
	private Void OnEnable() { }
	// RVA: 0x218a430 VA: 0x75947a2430
	private Void OnDisable() { }
	// RVA: 0x2189170 VA: 0x75947a1170
	public Void Render(Int32 index, UIItemViewModel viewModel) { }
	// RVA: 0x218a4ac VA: 0x75947a24ac
	private Void _InitIfNot() { }
	// RVA: 0x218ae8c VA: 0x75947a2e8c
	public Void CloseBtnTransition() { }
	// RVA: 0x218af84 VA: 0x75947a2f84
	public Color get_mainColor() { }
	// RVA: 0x2188adc VA: 0x75947a0adc
	public Void set_mainColor(Color value) { }
	// RVA: 0x218b05c VA: 0x75947a305c
	public Boolean get_enableValidTime() { }
	// RVA: 0x218b0d4 VA: 0x75947a30d4
	public Void set_enableValidTime(Boolean value) { }
	// RVA: 0x218b178 VA: 0x75947a3178
	public Boolean get_showItemNum() { }
	// RVA: 0x2189c40 VA: 0x75947a1c40
	public Void set_showItemNum(Boolean value) { }
	// RVA: 0x218b1f0 VA: 0x75947a31f0
	public Boolean get_showItemEmptyNum() { }
	// RVA: 0x218b268 VA: 0x75947a3268
	public Void set_showItemEmptyNum(Boolean value) { }
	// RVA: 0x218b2f8 VA: 0x75947a32f8
	public Boolean get_showItemName() { }
	// RVA: 0x218b370 VA: 0x75947a3370
	public Void set_showItemName(Boolean value) { }
	// RVA: 0x218b404 VA: 0x75947a3404
	public Boolean get_showBackground() { }
	// RVA: 0x218b47c VA: 0x75947a347c
	public Void set_showBackground(Boolean value) { }
	// RVA: 0x218b598 VA: 0x75947a3598
	public Boolean get_isCardClickable() { }
	// RVA: 0x2189b9c VA: 0x75947a1b9c
	public Void set_isCardClickable(Boolean value) { }
	// RVA: 0x218b624 VA: 0x75947a3624
	public Boolean get_enableCardClickAudio() { }
	// RVA: 0x218b6a8 VA: 0x75947a36a8
	public Void set_enableCardClickAudio(Boolean value) { }
	// RVA: 0x218b744 VA: 0x75947a3744
	public Void OnScaleChange(Single scale) { }
	// RVA: 0x218b8d8 VA: 0x75947a38d8
	public Void EventOnReduceBtnClick() { }
	// RVA: 0x218b970 VA: 0x75947a3970
	private Void _OnItemClicked() { }
	// RVA: 0x218ba08 VA: 0x75947a3a08
	private Boolean _OnItemLongPressed() { }
	// RVA: 0x218baa4 VA: 0x75947a3aa4
	private Void _OnValidTimeExcceeded() { }
	// RVA: 0x218ab68 VA: 0x75947a2b68
	public static String ParseItemCount(Int64 count, Int64 maxCount) { }
	// RVA: 0x218aa24 VA: 0x75947a2a24
	private Sprite _GetMaterialBkgSprite(UIItemViewModel itemModel) { }
	// RVA: 0x218a750 VA: 0x75947a2750
	private Sprite _GetCharBkgSprite(UIItemViewModel itemModel) { }
	// RVA: 0x218a894 VA: 0x75947a2894
	private Sprite _GetFurnitureBkgSprite(UIItemViewModel itemModel) { }
	// RVA: 0x218a93c VA: 0x75947a293c
	private Sprite _GetCharmBkgSprite(UIItemViewModel itemModel) { }
	// RVA: 0x218ae0c VA: 0x75947a2e0c
	private Void _UpdateNameShowState() { }
	// RVA: 0x218b510 VA: 0x75947a3510
	private Void _UpdateBackgroundShowState() { }
	// RVA: 0x218accc VA: 0x75947a2ccc
	private Void _UpdateItemNumVisibleState() { }
	// RVA: 0x218bb3c VA: 0x75947a3b3c
	private Boolean _CheckIfNoCountType(ItemType itemType) { }
	// RVA: 0x218a274 VA: 0x75947a2274
	private Void _UpdateValidTimeSystem(Boolean isItemCardEnabled) { }
	// RVA: 0x218bea8 VA: 0x75947a3ea8
	public Void .ctor() { }
	// RVA: 0x218bf94 VA: 0x75947a3f94
	private static Void .cctor() { }
}
```