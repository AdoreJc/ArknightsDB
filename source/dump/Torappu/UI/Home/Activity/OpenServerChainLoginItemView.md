# OpenServerChainLoginItemView

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `Text _dayText`

- `Text _itemName`

- `Image _itemIcon`

- `Image _itemIcon_2`

- `RectTransform _alreadyLogin`

- `RectTransform _alreadyGet`

- `RectTransform _alreadyGet_2`

- `CanvasGroup _neverGet`

- `Text _countText`

- `Text _countText_2`

- `GameObject _canGet`

- `Image _upPart`

- `Image _downPart`

- `Animator _onFinish`

- `Transform _itemCardContainer`

- `Single _itemScaleFactor`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `Int32 m_index`


## Methods

- `Void _InitIfNot()`

- `Void Init(Int32, ChainLoginData)`

- `Void OnAnimator()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerChainLoginItemView : MonoBehaviour
{
	private Text _dayText; // 0x18
	private Text _itemName; // 0x20
	private Image _itemIcon; // 0x28
	private Image _itemIcon_2; // 0x30
	private RectTransform _alreadyLogin; // 0x38
	private RectTransform _alreadyGet; // 0x40
	private RectTransform _alreadyGet_2; // 0x48
	private CanvasGroup _neverGet; // 0x50
	private Text _countText; // 0x58
	private Text _countText_2; // 0x60
	private GameObject _canGet; // 0x68
	private Image _upPart; // 0x70
	private Image _downPart; // 0x78
	private List`1 _upSpritePart; // 0x80
	private List`1 _downSpritePart; // 0x88
	public Action`1 OnGetChainLogin; // 0x90
	private Animator _onFinish; // 0x98
	private Transform _itemCardContainer; // 0xa0
	private Single _itemScaleFactor; // 0xa8
	private Boolean m_isInited; // 0xac
	private UIItemCard m_itemCard; // 0xb0
	private Int32 m_index; // 0xb8
	private const String MISSION_COMPLETE_ANIMATOR; // 0x0


	// RVA: 0x28503e0 VA: 0x7594e683e0
	private Void _InitIfNot() { }
	// RVA: 0x2850538 VA: 0x7594e68538
	public Void Init(Int32 index, ChainLoginData data) { }
	// RVA: 0x2850d60 VA: 0x7594e68d60
	public Void OnAnimator() { }
	// RVA: 0x2850db8 VA: 0x7594e68db8
	public Void OnClick() { }
	// RVA: 0x2850dd8 VA: 0x7594e68dd8
	public Void .ctor() { }
}
```