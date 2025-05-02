# QCShopHighView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `QCShopHighViewModel _viewModel`

- `Transform _objTransform`

- `QCNormalGoodItem _highObj`

- `QCNormalGoodItem _progressObj`

- `SpriteHub m_priceTypeHub`


## Methods

- `Void OnEnter(ShopPage)`

- `Void ApplyData(GetHighGoodListResponse)`

- `Void _LEGACY_ApplyData(GetHighGoodListResponse)`

- `Void _ApplyDataImpl(GetHighGoodListResponse)`

- `Void _TryOpenItemDetail()`

- `Void <OnEnter>b__7_0(GetHighGoodListResponse, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopHighView : MonoBehaviour, IHotfixable
{
	private QCShopHighViewModel _viewModel; // 0x18
	private Transform _objTransform; // 0x20
	private QCNormalGoodItem _highObj; // 0x28
	private QCNormalGoodItem _progressObj; // 0x30
	private ListDict`2 m_itemViews; // 0x38
	private HashSet`1 m_sharedHashSet; // 0x40
	private SpriteHub m_priceTypeHub; // 0x48
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge __Hotfix0__LEGACY_ApplyData; // 0x10
	private static DelegateBridge __Hotfix0__ApplyDataImpl; // 0x18
	private static DelegateBridge __Hotfix0__TryOpenItemDetail; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2450fc4 VA: 0x7594a68fc4
	public Void OnEnter(ShopPage shopPage) { }
	// RVA: 0x2454570 VA: 0x7594a6c570
	public Void ApplyData(GetHighGoodListResponse response) { }
	// RVA: 0x2454ac4 VA: 0x7594a6cac4
	private Void _LEGACY_ApplyData(GetHighGoodListResponse response) { }
	// RVA: 0x24546bc VA: 0x7594a6c6bc
	private Void _ApplyDataImpl(GetHighGoodListResponse response) { }
	// RVA: 0x2455324 VA: 0x7594a6d324
	private Void _TryOpenItemDetail() { }
	// RVA: 0x245540c VA: 0x7594a6d40c
	public Void .ctor() { }
	// RVA: 0x2455520 VA: 0x7594a6d520
	private Void <OnEnter>b__7_0(GetHighGoodListResponse response, Boolean isDataUpdated) { }
}
```