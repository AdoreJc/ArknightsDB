# ShopGPMonthlySubItem

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Image _gpImg`

- `Text _remainTime`

- `Text _itemName`

- `Text _currency`

- `Text _price`

- `ShopGPMonthlySubItemViewModel m_cacheViewModel`


## Methods

- `Void ApplyData(ShopGPMonthlySubItemViewModel)`

- `Void _OpenDetailEvent()`

- `Void EnterDetailEvent()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPMonthlySubItem : MonoBehaviour, IHotfixable
{
	private Image _gpImg; // 0x18
	private Text _remainTime; // 0x20
	private Text _itemName; // 0x28
	private Text _currency; // 0x30
	private Text _price; // 0x38
	private ShopGPMonthlySubItemViewModel m_cacheViewModel; // 0x40
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__OpenDetailEvent; // 0x8
	private static DelegateBridge __Hotfix0_EnterDetailEvent; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2443e60 VA: 0x7594a5be60
	public Void ApplyData(ShopGPMonthlySubItemViewModel itemViewModel) { }
	// RVA: 0x244416c VA: 0x7594a5c16c
	private Void _OpenDetailEvent() { }
	// RVA: 0x24441f0 VA: 0x7594a5c1f0
	public Void EnterDetailEvent() { }
	// RVA: 0x2444258 VA: 0x7594a5c258
	public Void OnClick() { }
	// RVA: 0x24442e8 VA: 0x7594a5c2e8
	public Void .ctor() { }
}
```