# CashShopItemObject

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Image _backSprite`

- `Image _countSprite`

- `Text _countText`

- `GameObject _availSpritePart`

- `GameObject _noSpritePart`

- `Text _constTextNoGift`

- `Text _priceIcon`

- `Text _priceText`

- `GameObject _isDoublePart`

- `CashItemViewModel m_cachedViewModel`


## Methods

- `Void Render(CashItemViewModel)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class CashShopItemObject : MonoBehaviour, IHotfixable
{
	private Image _backSprite; // 0x18
	private Image _countSprite; // 0x20
	private Text _countText; // 0x28
	private GameObject _availSpritePart; // 0x30
	private GameObject _noSpritePart; // 0x38
	private Text _constTextNoGift; // 0x40
	private Text _priceIcon; // 0x48
	private Text _priceText; // 0x50
	private GameObject _isDoublePart; // 0x58
	private CashItemViewModel m_cachedViewModel; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x24275e4 VA: 0x7594a3f5e4
	public Void Render(CashItemViewModel viewModel) { }
	// RVA: 0x2427974 VA: 0x7594a3f974
	public Void EventOnClicked() { }
	// RVA: 0x2427c4c VA: 0x7594a3fc4c
	public Void .ctor() { }
}
```