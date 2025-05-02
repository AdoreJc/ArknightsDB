# Act5D1ShopDetailProgressItem

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Image _itemSprite`

- `Image _priceSprite`

- `Text _priceText`

- `Text _index`

- `Text _count`

- `Image _backImage`

- `GameObject _isSoldOut`

- `GameObject _pricePart`


## Methods

- `Void InitCommonPart(Int32, Act5D1ProgressGoodItem)`

- `Void InitActiveData(Int32, ShopDetailPriceType, Act5D1ProgressGoodItem)`

- `Void InitUnActiveData(Int32, ShopDetailPriceType, Act5D1ProgressGoodItem, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1ShopDetailProgressItem : MonoBehaviour, IHotfixable
{
	private Image _itemSprite; // 0x18
	private Image _priceSprite; // 0x20
	private Text _priceText; // 0x28
	private Text _index; // 0x30
	private Text _count; // 0x38
	private Image _backImage; // 0x40
	private GameObject _isSoldOut; // 0x48
	private GameObject _pricePart; // 0x50
	private static readonly Single[] BACKIMAGEBLACKTYPE; // 0x0
	private static DelegateBridge __Hotfix0_InitCommonPart; // 0x8
	private static DelegateBridge __Hotfix0_InitActiveData; // 0x10
	private static DelegateBridge __Hotfix0_InitUnActiveData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31d8514 VA: 0x75957f0514
	private Void InitCommonPart(Int32 index, Act5D1ProgressGoodItem item) { }
	// RVA: 0x31d8750 VA: 0x75957f0750
	public Void InitActiveData(Int32 index, ShopDetailPriceType priceType, Act5D1ProgressGoodItem item) { }
	// RVA: 0x31d8800 VA: 0x75957f0800
	public Void InitUnActiveData(Int32 index, ShopDetailPriceType priceType, Act5D1ProgressGoodItem item, Boolean isSoldOut) { }
	// RVA: 0x31d896c VA: 0x75957f096c
	public Void .ctor() { }
	// RVA: 0x31d89ec VA: 0x75957f09ec
	private static Void .cctor() { }
}
```