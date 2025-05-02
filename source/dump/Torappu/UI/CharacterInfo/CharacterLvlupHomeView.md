# CharacterLvlupHomeView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Image _imgCampLogo`

- `CharacterLvlupAttrAndExpInfoView _attrAndExpInfoView`

- `CharacterLvlupItemCollectionView _itemCollectionView`

- `GameObject _panelLackExp`

- `GameObject _panelLackGold`

- `Text _txtLackExp`

- `Text _txtLackGold`

- `CharacterLvlupWheelPickerView _wheelPickerView`

- `GameObject _panelScrollTips`

- `GameObject _panelScrollLevelNormal`

- `GameObject _panelScrollLevelCounting`

- `RectTransform _rectTransformScrollTargetTag`

- `CharacterLvlupExpCircleView _expCircleView`

- `CanvasGroup _canvasGroupScrollReset`

- `CanvasGroup _canvasGroupScrollBtn`

- `RectTransform _rectTransformScrollBtn`

- `GameObject _panelScrollConfirmInvalid`

- `CanvasGroup _canvasGroupScrollCounting`

- `RectTransform _rectTransformScrollCounting`

- `CharacterLvlupLevelAnchorView _levelAnchorView`

- `CanvasGroup _canvasGroupBtnClear`

- `CanvasGroup _canvasGroupBtnUpgrade`

- `RectTransform _rectTransformBtnUpgrade`

- `GameObject _panelUpgradeInvalid`

- `CanvasGroup _canvasGroupWasteTips`

- `Text _txtWasteExpTips`

- `Action onWheelBeginDrag`

- `Action onMoveToMaxValidLevel`

- `Boolean m_isInited`

- `CountingPartSwitchTween m_countingPartSwitchTween`

- `ScrollBtnSwitchTween m_scrollBtnSwitchTween`

- `UpgradeBtnSwitchTween m_upgradeBtnSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void _OnModifyingCardNum(Int32, Int32)`

- `Void _OnMoveToMaxValidLevel()`

- `Void _OnWheelBeginDrag()`

- `Void _OnWheelItemClicked(Int32)`

- `Void _OnWheelScrollEnd(Int32)`

- `Void _TryToFadeForCanvasGroup(CanvasGroup, Boolean)`

- `String _GeneLackExpStr(CharacterLvlupViewModel, Int32)`

- `String _GeneLackGoldStr(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupHomeView : DataBinder`1
{
	private const Single FADE_DURATION; // 0x0
	private Image _imgCampLogo; // 0x20
	private CharacterLvlupAttrAndExpInfoView _attrAndExpInfoView; // 0x28
	private CharacterLvlupItemCollectionView _itemCollectionView; // 0x30
	private GameObject _panelLackExp; // 0x38
	private GameObject _panelLackGold; // 0x40
	private Text _txtLackExp; // 0x48
	private Text _txtLackGold; // 0x50
	private CharacterLvlupWheelPickerView _wheelPickerView; // 0x58
	private GameObject _panelScrollTips; // 0x60
	private GameObject _panelScrollLevelNormal; // 0x68
	private GameObject _panelScrollLevelCounting; // 0x70
	private RectTransform _rectTransformScrollTargetTag; // 0x78
	private CharacterLvlupExpCircleView _expCircleView; // 0x80
	private CanvasGroup _canvasGroupScrollReset; // 0x88
	private CanvasGroup _canvasGroupScrollBtn; // 0x90
	private RectTransform _rectTransformScrollBtn; // 0x98
	private GameObject _panelScrollConfirmInvalid; // 0xa0
	private CanvasGroup _canvasGroupScrollCounting; // 0xa8
	private RectTransform _rectTransformScrollCounting; // 0xb0
	private CharacterLvlupLevelAnchorView _levelAnchorView; // 0xb8
	private CanvasGroup _canvasGroupBtnClear; // 0xc0
	private CanvasGroup _canvasGroupBtnUpgrade; // 0xc8
	private RectTransform _rectTransformBtnUpgrade; // 0xd0
	private GameObject _panelUpgradeInvalid; // 0xd8
	private CanvasGroup _canvasGroupWasteTips; // 0xe0
	private Text _txtWasteExpTips; // 0xe8
	public Action`2 onModifyingCardNum; // 0xf0
	public Action onWheelBeginDrag; // 0xf8
	public Action`1 onWheelScrollEnd; // 0x100
	public Action`1 onWheelItemClicked; // 0x108
	public Action onMoveToMaxValidLevel; // 0x110
	private Boolean m_isInited; // 0x118
	private CountingPartSwitchTween m_countingPartSwitchTween; // 0x120
	private ScrollBtnSwitchTween m_scrollBtnSwitchTween; // 0x128
	private UpgradeBtnSwitchTween m_upgradeBtnSwitchTween; // 0x130
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnModifyingCardNum; // 0x10
	private static DelegateBridge __Hotfix0__OnMoveToMaxValidLevel; // 0x18
	private static DelegateBridge __Hotfix0__OnWheelBeginDrag; // 0x20
	private static DelegateBridge __Hotfix0__OnWheelItemClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnWheelScrollEnd; // 0x30
	private static DelegateBridge __Hotfix0__TryToFadeForCanvasGroup; // 0x38
	private static DelegateBridge __Hotfix0__GeneLackExpStr; // 0x40
	private static DelegateBridge __Hotfix0__GeneLackGoldStr; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2d74ee8 VA: 0x759538cee8
	public override Void OnValueChanged(CharacterLvlupViewProperty property) { }
	// RVA: 0x2d754f8 VA: 0x759538d4f8
	private Void _InitIfNot() { }
	// RVA: 0x2d762c8 VA: 0x759538e2c8
	private Void _OnModifyingCardNum(Int32 index, Int32 deltaNum) { }
	// RVA: 0x2d76374 VA: 0x759538e374
	private Void _OnMoveToMaxValidLevel() { }
	// RVA: 0x2d763f8 VA: 0x759538e3f8
	private Void _OnWheelBeginDrag() { }
	// RVA: 0x2d7647c VA: 0x759538e47c
	private Void _OnWheelItemClicked(Int32 pageIndex) { }
	// RVA: 0x2d7651c VA: 0x759538e51c
	private Void _OnWheelScrollEnd(Int32 index) { }
	// RVA: 0x2d75d28 VA: 0x759538dd28
	private Void _TryToFadeForCanvasGroup(CanvasGroup canvasGroup, Boolean isShow) { }
	// RVA: 0x2d75978 VA: 0x759538d978
	private String _GeneLackExpStr(CharacterLvlupViewModel viewModel, Int32 lackExp) { }
	// RVA: 0x2d75ad8 VA: 0x759538dad8
	private String _GeneLackGoldStr(Int64 lackGold) { }
	// RVA: 0x2d765bc VA: 0x759538e5bc
	public Void .ctor() { }
}
```