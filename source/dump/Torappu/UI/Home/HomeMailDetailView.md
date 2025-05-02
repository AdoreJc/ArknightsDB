# HomeMailDetailView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _imageAvatar`

- `Text _textTitle`

- `Text _textFrom`

- `Transform _itemCardContainer`

- `Transform _rewardCardHolder`

- `GameObject _itemCardPrefab`

- `Single _itemScaleFactor`

- `GameObject _isReceivedPart`

- `GameObject _noReceivePart`

- `CanvasGroup _itemAlpha`

- `Text _timeCreate`

- `Text _timeExpire`

- `Text _mailDetail`

- `GameObject _normalPart`

- `GameObject _toMonthlySubPart`

- `GameObject _surveyItemButton`

- `GameObject _panelNormalBkg`

- `GameObject _panelSpecialBkg`


## Methods

- `Void InitData(MailItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailDetailView : MonoBehaviour
{
	private const Single MAIL_REWARD_ITEM_CARD_MIN_HEIGHT; // 0x0
	private const Single MAIL_REWARD_ITEM_CARD_MIN_WIDTH; // 0x0
	private Image _imageAvatar; // 0x18
	private Text _textTitle; // 0x20
	private Text _textFrom; // 0x28
	private Transform _itemCardContainer; // 0x30
	private Transform _rewardCardHolder; // 0x38
	private GameObject _itemCardPrefab; // 0x40
	private Single _itemScaleFactor; // 0x48
	private GameObject _isReceivedPart; // 0x50
	private GameObject _noReceivePart; // 0x58
	private CanvasGroup _itemAlpha; // 0x60
	private Text _timeCreate; // 0x68
	private Text _timeExpire; // 0x70
	private Text _mailDetail; // 0x78
	private GameObject _normalPart; // 0x80
	private GameObject _toMonthlySubPart; // 0x88
	private GameObject _surveyItemButton; // 0x90
	private GameObject _panelNormalBkg; // 0x98
	private GameObject _panelSpecialBkg; // 0xa0
	private List`1 m_itemCardsList; // 0xa8


	// RVA: 0x284245c VA: 0x7594e5a45c
	public Void InitData(MailItemViewModel viewModel) { }
	// RVA: 0x2842c84 VA: 0x7594e5ac84
	public Void .ctor() { }
}
```