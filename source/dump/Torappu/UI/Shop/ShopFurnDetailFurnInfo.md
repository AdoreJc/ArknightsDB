# ShopFurnDetailFurnInfo

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _furnName`

- `Text _countText`

- `Image _priceIcon`

- `Text _pricePart`

- `GameObject _needToPricePart`

- `GameObject _notNeedToBuyPart`

- `GameObject _ablePart`

- `GameObject _notAblePart`

- `FurnCurrentInfoViewModel m_furnInfo`


## Methods

- `Void Render(FurnCurrentInfoViewModel, SpriteHub, Int32)`

- `Void ApplyPriceState(SelectClass, Sprite, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopFurnDetailFurnInfo : MonoBehaviour, IHotfixable
{
	private Text _furnName; // 0x18
	private Text _countText; // 0x20
	private Image _priceIcon; // 0x28
	private Text _pricePart; // 0x30
	private GameObject _needToPricePart; // 0x38
	private GameObject _notNeedToBuyPart; // 0x40
	private GameObject _ablePart; // 0x48
	private GameObject _notAblePart; // 0x50
	private FurnCurrentInfoViewModel m_furnInfo; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ApplyPriceState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x242d748 VA: 0x7594a45748
	public Void Render(FurnCurrentInfoViewModel furnInfo, SpriteHub priceHub, Int32 currentGroup) { }
	// RVA: 0x242e9dc VA: 0x7594a469dc
	public Void ApplyPriceState(SelectClass selectClass, Sprite icon, Color textColor) { }
	// RVA: 0x242f000 VA: 0x7594a47000
	public Void .ctor() { }
}
```