# ShopStateItemButton

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopType _shopType`

- `Animator _animator`

- `UIShopTypeEvent _clickEvent`

- `Boolean m_activeFlag`


## Methods

- `Void OnClick()`

- `Void OnEnable()`

- `Void ApplyShopType(ShopType)`

- `Boolean isActive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopStateItemButton : MonoBehaviour
{
	private ShopType _shopType; // 0x18
	private Animator _animator; // 0x20
	private UIShopTypeEvent _clickEvent; // 0x28
	private const String ACTIVEFLAG; // 0x0
	private Boolean m_activeFlag; // 0x30


	// RVA: 0x246880c VA: 0x7594a8080c
	public Void OnClick() { }
	// RVA: 0x2468880 VA: 0x7594a80880
	private Void OnEnable() { }
	// RVA: 0x24688d8 VA: 0x7594a808d8
	public Void ApplyShopType(ShopType currentShopType) { }
	// RVA: 0x2468948 VA: 0x7594a80948
	public Boolean isActive() { }
	// RVA: 0x2468a10 VA: 0x7594a80a10
	public Void .ctor() { }
}
```