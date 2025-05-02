# HomeMailItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _imageAvatar`

- `Text _textTitle`

- `Text _textTime`

- `Text _textTimeWithItem`

- `Text _textFrom`

- `GameObject _readMask`

- `Transform _itemCardContainer`

- `GameObject _itemCardPrefab`

- `Text _getText`

- `Image _priceImage`

- `Single _itemScaleFactor`

- `Image _mailStyleImg`

- `HomeMailIndex m_cacheId`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(Int64, MailItemViewModel)`

- `Void EventOnMailClick()`

- `Void EventOnDetailClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailItemView : MonoBehaviour
{
	private Image _imageAvatar; // 0x18
	private GameObject[] _itemPart; // 0x20
	private GameObject[] _noItemPart; // 0x28
	private Text _textTitle; // 0x30
	private Text _textTime; // 0x38
	private Text _textTimeWithItem; // 0x40
	private Text _textFrom; // 0x48
	private GameObject _readMask; // 0x50
	private Transform _itemCardContainer; // 0x58
	private GameObject _itemCardPrefab; // 0x60
	private Text _getText; // 0x68
	private Image _priceImage; // 0x70
	private Single _itemScaleFactor; // 0x78
	private Image _mailStyleImg; // 0x80
	private GameObject[] _panelSpecialMail; // 0x88
	public Action`1 onMailClick; // 0x90
	public Action`1 onMailDetailClick; // 0x98
	private HomeMailIndex m_cacheId; // 0xa0
	private UIItemCard m_itemCard; // 0xb8
	private Boolean m_isInited; // 0xc0


	// RVA: 0x2843f2c VA: 0x7594e5bf2c
	private Void _InitIfNot() { }
	// RVA: 0x2844060 VA: 0x7594e5c060
	public Void Render(Int64 inputIndex, MailItemViewModel viewModel) { }
	// RVA: 0x2844630 VA: 0x7594e5c630
	private static Void _SetGameObjectGroupActive(GameObject[] group, Boolean isActive) { }
	// RVA: 0x28446d4 VA: 0x7594e5c6d4
	public Void EventOnMailClick() { }
	// RVA: 0x284471c VA: 0x7594e5c71c
	public Void EventOnDetailClick() { }
	// RVA: 0x2844764 VA: 0x7594e5c764
	public Void .ctor() { }
}
```