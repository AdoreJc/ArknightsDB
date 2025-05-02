# OpenServerTotalCheckInItemView

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `Text _indexId`

- `Text _itemName`

- `Image _itemIcon`

- `Text _itemCount`

- `Image _itemIcon_2`

- `Text _itemCount_2`

- `CanvasGroup _neverGet`

- `RectTransform _alreadyGet`

- `RectTransform _alreadyGet_2`

- `Image _upPart`

- `Image _downPart`

- `GameObject _canGet`

- `GameObject _canGetHotSpot`

- `Animator _onFinish`

- `Int32 m_index`


## Methods

- `Void Init(Int32, TotalCheckinData)`

- `Void OnClick()`

- `Void OnAnimator()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerTotalCheckInItemView : MonoBehaviour
{
	private Text _indexId; // 0x18
	private Text _itemName; // 0x20
	private Image _itemIcon; // 0x28
	private Text _itemCount; // 0x30
	private Image _itemIcon_2; // 0x38
	private Text _itemCount_2; // 0x40
	private CanvasGroup _neverGet; // 0x48
	private RectTransform _alreadyGet; // 0x50
	private RectTransform _alreadyGet_2; // 0x58
	private Image _upPart; // 0x60
	private Image _downPart; // 0x68
	private List`1 _upSpritePart; // 0x70
	private List`1 _downSpritePart; // 0x78
	private GameObject _canGet; // 0x80
	private GameObject _canGetHotSpot; // 0x88
	public Action`1 OnGetCheckIn; // 0x90
	private Animator _onFinish; // 0x98
	private Int32 m_index; // 0xa0
	private const String MISSION_COMPLETE_ANIMATOR; // 0x0


	// RVA: 0x2852bd0 VA: 0x7594e6abd0
	public Void Init(Int32 index, TotalCheckinData data) { }
	// RVA: 0x2853234 VA: 0x7594e6b234
	public Void OnClick() { }
	// RVA: 0x2853254 VA: 0x7594e6b254
	public Void OnAnimator() { }
	// RVA: 0x28532ac VA: 0x7594e6b2ac
	public Void .ctor() { }
}
```