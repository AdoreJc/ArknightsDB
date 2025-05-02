# QCNormalGoodItem

**Namespace:** `Torappu.UI.Shop`


## Fields

- `GameObject _commonPart`

- `GameObject _gachaPart`

- `QCCommonObj m_cacheObj`

- `String m_gachaPoolId`

- `ShopDetailPriceType m_cachePriceType`


## Methods

- `Void ApplyNormalData(QCCommonObj, ShopDetailPriceType, SpriteHub)`

- `Void _ApplyNormalData(QCCommonObj, ShopDetailPriceType, SpriteHub)`

- `Void ApplyProgressData(QCCommonObj, ShopDetailPriceType, SpriteHub)`

- `Void _ApplyGachaData(QCCommonObj, ShopDetailPriceType, SpriteHub, String)`

- `Void _ApplyNormalGachaData(QCCommonObj, ShopDetailPriceType, SpriteHub)`

- `Void _ApplyGachaPoolData(QCCommonObj, ShopDetailPriceType, SpriteHub)`

- `Void _SetGachaPart(Boolean)`

- `Void OpenItemDetail()`

- `Void OnOpenGachaPage()`

- `Void EnterDetailEvent()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCNormalGoodItem : QCBaseGoodItem, IHotfixable
{
	private GameObject _commonPart; // 0xa8
	private GameObject _gachaPart; // 0xb0
	private QCCommonObj m_cacheObj; // 0xb8
	private String m_gachaPoolId; // 0xc0
	private ShopDetailPriceType m_cachePriceType; // 0xc8
	private static DelegateBridge __Hotfix0_ApplyNormalData; // 0x0
	private static DelegateBridge __Hotfix0__ApplyNormalData; // 0x8
	private static DelegateBridge __Hotfix0_ApplyProgressData; // 0x10
	private static DelegateBridge __Hotfix0__ApplyGachaData; // 0x18
	private static DelegateBridge __Hotfix0__ApplyNormalGachaData; // 0x20
	private static DelegateBridge __Hotfix0__ApplyGachaPoolData; // 0x28
	private static DelegateBridge __Hotfix0__SetGachaPart; // 0x30
	private static DelegateBridge __Hotfix0_OpenItemDetail; // 0x38
	private static DelegateBridge __Hotfix0_OnOpenGachaPage; // 0x40
	private static DelegateBridge __Hotfix0_EnterDetailEvent; // 0x48
	private static DelegateBridge __Hotfix0_OnClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x244e2c4 VA: 0x7594a662c4
	public Void ApplyNormalData(QCCommonObj obj, ShopDetailPriceType priceType, SpriteHub hub) { }
	// RVA: 0x244e3d8 VA: 0x7594a663d8
	private Void _ApplyNormalData(QCCommonObj obj, ShopDetailPriceType priceType, SpriteHub hub) { }
	// RVA: 0x244e6c4 VA: 0x7594a666c4
	public Void ApplyProgressData(QCCommonObj obj, ShopDetailPriceType priceType, SpriteHub hub) { }
	// RVA: 0x244e528 VA: 0x7594a66528
	private Void _ApplyGachaData(QCCommonObj obj, ShopDetailPriceType priceType, SpriteHub hub, String gachaPoolId) { }
	// RVA: 0x244e900 VA: 0x7594a66900
	private Void _ApplyNormalGachaData(QCCommonObj obj, ShopDetailPriceType priceType, SpriteHub hub) { }
	// RVA: 0x244ea98 VA: 0x7594a66a98
	private Void _ApplyGachaPoolData(QCCommonObj obj, ShopDetailPriceType priceType, SpriteHub hub) { }
	// RVA: 0x244e62c VA: 0x7594a6662c
	private Void _SetGachaPart(Boolean showFesPart) { }
	// RVA: 0x244ec14 VA: 0x7594a66c14
	public Void OpenItemDetail() { }
	// RVA: 0x244ec84 VA: 0x7594a66c84
	public Void OnOpenGachaPage() { }
	// RVA: 0x244ede4 VA: 0x7594a66de4
	public Void EnterDetailEvent() { }
	// RVA: 0x244ee4c VA: 0x7594a66e4c
	public Void OnClick() { }
	// RVA: 0x244eeb4 VA: 0x7594a66eb4
	public Void .ctor() { }
}
```