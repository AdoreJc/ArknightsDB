# QCShopExtraView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `QCShopExtraViewModel _viewModel`

- `Transform _objTransform`

- `QCShopExtraGoodItem _extraObj`

- `CountDownTask m_countDownTask`

- `DateTime m_timeLimit`

- `SpriteHub m_priceTypeHub`


## Methods

- `Void OnEnter(ShopPage)`

- `Void _ApplyData(GetExtraGoodListResponse)`

- `Void _RenderShopList()`

- `Void _TryOpenItemDetail()`

- `Void Update()`

- `Void <OnEnter>b__8_0(GetExtraGoodListResponse, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopExtraView : MonoBehaviour, IHotfixable
{
	private QCShopExtraViewModel _viewModel; // 0x18
	private Transform _objTransform; // 0x20
	private QCShopExtraGoodItem _extraObj; // 0x28
	private CountDownTask m_countDownTask; // 0x30
	private DateTime m_timeLimit; // 0x38
	private HashSet`1 m_sharedHashSet; // 0x40
	private ListDict`2 m_itemList; // 0x48
	private SpriteHub m_priceTypeHub; // 0x50
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__ApplyData; // 0x8
	private static DelegateBridge __Hotfix0__RenderShopList; // 0x10
	private static DelegateBridge __Hotfix0__TryOpenItemDetail; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x245133c VA: 0x7594a6933c
	public Void OnEnter(ShopPage page) { }
	// RVA: 0x2453544 VA: 0x7594a6b544
	private Void _ApplyData(GetExtraGoodListResponse response) { }
	// RVA: 0x2453a64 VA: 0x7594a6ba64
	private Void _RenderShopList() { }
	// RVA: 0x2453e08 VA: 0x7594a6be08
	private Void _TryOpenItemDetail() { }
	// RVA: 0x2453ef0 VA: 0x7594a6bef0
	private Void Update() { }
	// RVA: 0x2453f6c VA: 0x7594a6bf6c
	public Void .ctor() { }
	// RVA: 0x2454080 VA: 0x7594a6c080
	private Void <OnEnter>b__8_0(GetExtraGoodListResponse response, Boolean isDataUpdated) { }
}
```