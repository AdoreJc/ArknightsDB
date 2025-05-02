# ClimbTowerBattleFinishView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `UIFullScreenImage _fullScreenImage`

- `RectTransform _illustContainer`

- `AVGTypeWriterText _illustText`

- `GameObject _panelIllustText`

- `Text _txtBattleName`

- `UIAtlasObject _atlas`

- `Image _imgTowerLogo`

- `Text _txtTowerName`

- `Text _txtTowerSubName`

- `Text _txtCurProcess`

- `Text _txtTotalProcess`

- `GameObject _panelNewRecord`

- `UIAtlasImage _imgNewRecord`

- `GameObject _objHardTag`

- `GameObject _panelUnit`

- `SimpleLayoutContent _unitLayoutContent`

- `RectTransform _transformPanelStatus`

- `CanvasGroup _canvasGroupPanelStatus`

- `RectTransform _transformPanelUnit`

- `CanvasGroup _canvasGroupPanelUnit`

- `RectTransform _transformPanelReward`

- `CanvasGroup _canvasGroupPanelReward`

- `Image _iconLowerItem`

- `Image _iconHigherItem`

- `Text _textLowerItemName`

- `Text _textHigherItemName`

- `UISingleValueChangeBar _barLowerItem`

- `UISingleValueChangeBar _barHigherItem`

- `GameObject _iconLowerItemMax`

- `GameObject _iconHigherItemMax`

- `Text _textLowerItemGain`

- `Text _textHigherItemGain`

- `CanvasGroup _canvasLowerItemGain`

- `CanvasGroup _canvasHigherItemGain`

- `Boolean m_inited`

- `Adapter m_adapter`

- `UICharacterIllust m_illust`

- `Boolean m_needPanelUnit`

- `Boolean m_hasPlayedAnim`

- `Boolean m_isLowerItemMax`

- `Boolean m_isHigherItemMax`


## Methods

- `Void Render(ClimbTowerBattleFinishViewModel)`

- `Void _InitIfNot()`

- `Void _RetTweenElementsToBegin()`

- `Void _RenderIllust(String, Boolean)`

- `IEnumerator _ShowPanelAnim()`

- `IEnumerator _PlayPanelPopUpSound(Int32)`

- `CharWordShowType _GetCompleteProperVoiceShowType(Boolean)`

- `Void EventOnViewClicked()`

- `Void <_ShowPanelAnim>b__54_0()`

- `Void <_ShowPanelAnim>b__54_2()`

- `Void <_ShowPanelAnim>b__54_3()`

- `Void <_ShowPanelAnim>b__54_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBattleFinishView : MonoBehaviour, IHotfixable
{
	private const String TOTAL_LAYER_FORMAT; // 0x0
	private const String ITEM_GAIN_COUNT_FORMAT; // 0x0
	private const String NEW_RECORD_IMG_PREFIX; // 0x0
	private const Int32 TWEEN_WIDTH_OFFSET; // 0x0
	private const Single TWEEN_MOVE_DURATION; // 0x0
	private const Single TWEEN_MOVE_INTERVAL; // 0x0
	private static readonly Color ITEM_GAIN_TEXT_DEFAULT_COLOR; // 0x0
	private static readonly Color ITEM_GAIN_TEXT_ZERO_COLOR; // 0x10
	private UIFullScreenImage _fullScreenImage; // 0x18
	private RectTransform _illustContainer; // 0x20
	private AVGTypeWriterText _illustText; // 0x28
	private GameObject _panelIllustText; // 0x30
	private Text _txtBattleName; // 0x38
	private UIAtlasObject _atlas; // 0x40
	private Image _imgTowerLogo; // 0x48
	private Text _txtTowerName; // 0x50
	private Text _txtTowerSubName; // 0x58
	private Text _txtCurProcess; // 0x60
	private Text _txtTotalProcess; // 0x68
	private GameObject _panelNewRecord; // 0x70
	private UIAtlasImage _imgNewRecord; // 0x78
	private GameObject _objHardTag; // 0x80
	private GameObject _panelUnit; // 0x88
	private SimpleLayoutContent _unitLayoutContent; // 0x90
	private RectTransform _transformPanelStatus; // 0x98
	private CanvasGroup _canvasGroupPanelStatus; // 0xa0
	private RectTransform _transformPanelUnit; // 0xa8
	private CanvasGroup _canvasGroupPanelUnit; // 0xb0
	private RectTransform _transformPanelReward; // 0xb8
	private CanvasGroup _canvasGroupPanelReward; // 0xc0
	private Image _iconLowerItem; // 0xc8
	private Image _iconHigherItem; // 0xd0
	private Text _textLowerItemName; // 0xd8
	private Text _textHigherItemName; // 0xe0
	private UISingleValueChangeBar _barLowerItem; // 0xe8
	private UISingleValueChangeBar _barHigherItem; // 0xf0
	private GameObject _iconLowerItemMax; // 0xf8
	private GameObject _iconHigherItemMax; // 0x100
	private Text _textLowerItemGain; // 0x108
	private Text _textHigherItemGain; // 0x110
	private CanvasGroup _canvasLowerItemGain; // 0x118
	private CanvasGroup _canvasHigherItemGain; // 0x120
	private Boolean m_inited; // 0x128
	private Adapter m_adapter; // 0x130
	private UICharacterIllust m_illust; // 0x138
	private Boolean m_needPanelUnit; // 0x140
	private Boolean m_hasPlayedAnim; // 0x141
	private Boolean m_isLowerItemMax; // 0x142
	private Boolean m_isHigherItemMax; // 0x143
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__RetTweenElementsToBegin; // 0x30
	private static DelegateBridge __Hotfix0__RenderIllust; // 0x38
	private static DelegateBridge __Hotfix0__ShowPanelAnim; // 0x40
	private static DelegateBridge __Hotfix0__PlayPanelPopUpSound; // 0x48
	private static DelegateBridge __Hotfix0__GetCompleteProperVoiceShowType; // 0x50
	private static DelegateBridge __Hotfix0_EventOnViewClicked; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2cddf6c VA: 0x75952f5f6c
	public Void Render(ClimbTowerBattleFinishViewModel viewModel) { }
	// RVA: 0x2cde610 VA: 0x75952f6610
	private Void _InitIfNot() { }
	// RVA: 0x2cdeb58 VA: 0x75952f6b58
	private Void _RetTweenElementsToBegin() { }
	// RVA: 0x2cde74c VA: 0x75952f674c
	private Void _RenderIllust(String showInstId, Boolean isHardStage) { }
	// RVA: 0x2cdea9c VA: 0x75952f6a9c
	private IEnumerator _ShowPanelAnim() { }
	// RVA: 0x2cdecc4 VA: 0x75952f6cc4
	private IEnumerator _PlayPanelPopUpSound(Int32 count) { }
	// RVA: 0x2cdec08 VA: 0x75952f6c08
	private CharWordShowType _GetCompleteProperVoiceShowType(Boolean isHardStage) { }
	// RVA: 0x2cdedb0 VA: 0x75952f6db0
	public Void EventOnViewClicked() { }
	// RVA: 0x2cdee48 VA: 0x75952f6e48
	public Void .ctor() { }
	// RVA: 0x2cdef74 VA: 0x75952f6f74
	private static Void .cctor() { }
	// RVA: 0x2cdefd8 VA: 0x75952f6fd8
	private Void <_ShowPanelAnim>b__54_0() { }
	// RVA: 0x2cdf0b8 VA: 0x75952f70b8
	private Void <_ShowPanelAnim>b__54_2() { }
	// RVA: 0x2cdf0cc VA: 0x75952f70cc
	private Void <_ShowPanelAnim>b__54_3() { }
	// RVA: 0x2cdf0e0 VA: 0x75952f70e0
	private Void <_ShowPanelAnim>b__54_1() { }
}
```