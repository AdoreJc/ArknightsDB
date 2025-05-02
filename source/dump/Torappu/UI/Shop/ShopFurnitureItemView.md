# ShopFurnitureItemView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `GameObject _furnPart`

- `GameObject _bothPart`

- `GameObject _diamPart`

- `Text _diamondOnlyPrice`

- `Text _furniOnlyPrice`

- `Text _diamondBothPrice`

- `Text _furniBothPrice`

- `Text _offsetPercent`

- `GameObject _offsetPart`

- `GameObject _soldOutPart`

- `GameObject _alreadyHavePart`

- `Image _furnImage`

- `Text _remainCount`

- `GameObject _remainCountPart`

- `Text _displayName`

- `Text _addAtmosText`

- `CanvasGroup _soldOutGroup`

- `GameObject _endTimePart`

- `Text _endTimeText`

- `Boolean isGoodFlag`

- `Good m_cacheGoodViewModel`

- `FurnGroupViewModel m_cacheGroupViewModel`

- `FurnitureData m_furnitureData`


## Methods

- `Void OnClick()`

- `Void OpenItemDetail()`

- `Void LoadData(FurnGroupViewModel)`

- `Void LoadData(Good)`

- `Void _OpenItemDetail()`

- `Boolean <_OpenItemDetail>b__27_0(PlayerGoodItemData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopFurnitureItemView : MonoBehaviour
{
	private GameObject _furnPart; // 0x18
	private GameObject _bothPart; // 0x20
	private GameObject _diamPart; // 0x28
	private Text _diamondOnlyPrice; // 0x30
	private Text _furniOnlyPrice; // 0x38
	private Text _diamondBothPrice; // 0x40
	private Text _furniBothPrice; // 0x48
	protected Text _offsetPercent; // 0x50
	protected GameObject _offsetPart; // 0x58
	private GameObject _soldOutPart; // 0x60
	private GameObject _alreadyHavePart; // 0x68
	private Image _furnImage; // 0x70
	private Text _remainCount; // 0x78
	private GameObject _remainCountPart; // 0x80
	private Text _displayName; // 0x88
	private Text _addAtmosText; // 0x90
	private CanvasGroup _soldOutGroup; // 0x98
	private GameObject _endTimePart; // 0xa0
	private Text _endTimeText; // 0xa8
	private Boolean isGoodFlag; // 0xb0
	private Good m_cacheGoodViewModel; // 0xb8
	private FurnGroupViewModel m_cacheGroupViewModel; // 0xc0
	private FurnitureData m_furnitureData; // 0xc8


	// RVA: 0x243ddb4 VA: 0x7594a55db4
	public Void OnClick() { }
	// RVA: 0x243def8 VA: 0x7594a55ef8
	public Void OpenItemDetail() { }
	// RVA: 0x243d820 VA: 0x7594a55820
	public Void LoadData(FurnGroupViewModel groupViewModel) { }
	// RVA: 0x243cfd8 VA: 0x7594a54fd8
	public Void LoadData(Good goodViewModel) { }
	// RVA: 0x243ddb8 VA: 0x7594a55db8
	private Void _OpenItemDetail() { }
	// RVA: 0x243df04 VA: 0x7594a55f04
	public Void .ctor() { }
	// RVA: 0x243df0c VA: 0x7594a55f0c
	private Boolean <_OpenItemDetail>b__27_0(PlayerGoodItemData x) { }
}
```