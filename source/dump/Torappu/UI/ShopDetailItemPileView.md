# ShopDetailItemPileView

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _pileBoxPart`

- `Image _pileBoxImage`


## Methods

- `Void PileItem(Int32, String, ItemType)`

- `Void PileItem(Int32, Sprite)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ShopDetailItemPileView : MonoBehaviour, IHotfixable
{
	private Image[] _imageList; // 0x18
	private GameObject _pileBoxPart; // 0x20
	private Image _pileBoxImage; // 0x28
	private const Int32 MAX_COUNT; // 0x0
	private static readonly Vector2 DEFAULT_SIZE; // 0x0
	private static readonly Vector2 LITTLE_SIZE; // 0x8
	private static readonly Vector2[][] CONSTPOSLIST; // 0x10
	private static DelegateBridge __Hotfix0_PileItem; // 0x18
	private static DelegateBridge __Hotfix1_PileItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x22893b4 VA: 0x75948a13b4
	public Void PileItem(Int32 count, String itemId, ItemType itemType) { }
	// RVA: 0x22894e4 VA: 0x75948a14e4
	public Void PileItem(Int32 count, Sprite itemSprite) { }
	// RVA: 0x228983c VA: 0x75948a183c
	public Void .ctor() { }
	// RVA: 0x22898bc VA: 0x75948a18bc
	private static Void .cctor() { }
}
```