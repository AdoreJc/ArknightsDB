# CrisisShopRightViewHolder

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `CrisisShopCharRightView _charView`

- `CrisisShopComplexRightView _complexView`

- `CrisisShopSingleRightView _singleView`

- `Sprite _crisisV1Icon`

- `Sprite _crisisV2Icon`


## Methods

- `ShopDetailInfo _GetBuyItemInfoAndSetPrice(CrisisShopWrapped)`

- `Void Render(CrisisShopWrapped)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopRightViewHolder : MonoBehaviour
{
	private CrisisShopCharRightView _charView; // 0x18
	private CrisisShopComplexRightView _complexView; // 0x20
	private CrisisShopSingleRightView _singleView; // 0x28
	private List`1 _iconList; // 0x30
	private Sprite _crisisV1Icon; // 0x38
	private Sprite _crisisV2Icon; // 0x40


	// RVA: 0x2c3a870 VA: 0x7595252870
	private ShopDetailInfo _GetBuyItemInfoAndSetPrice(CrisisShopWrapped shopViewModel) { }
	// RVA: 0x2c3a9c0 VA: 0x75952529c0
	public Void Render(CrisisShopWrapped shopViewModel) { }
	// RVA: 0x2c3b280 VA: 0x7595253280
	public Void .ctor() { }
}
```