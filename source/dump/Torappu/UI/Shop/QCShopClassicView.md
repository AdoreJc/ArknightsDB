# QCShopClassicView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `QCShopClassicViewModel _viewModel`

- `Transform _objTransform`

- `QCNormalGoodItem _highObj`

- `QCNormalGoodItem _progressObj`

- `SpriteHub m_priceTypeHub`


## Methods

- `Void OnEnter(ShopPage)`

- `Void _ApplyData(GetClassicGoodListResponse)`

- `Void _TryOpenItemDetail()`

- `Void <OnEnter>b__7_0(GetClassicGoodListResponse, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopClassicView : MonoBehaviour, IHotfixable
{
	private QCShopClassicViewModel _viewModel; // 0x18
	private Transform _objTransform; // 0x20
	private QCNormalGoodItem _highObj; // 0x28
	private QCNormalGoodItem _progressObj; // 0x30
	private ListDict`2 m_itemViews; // 0x38
	private HashSet`1 m_sharedHashSet; // 0x40
	private SpriteHub m_priceTypeHub; // 0x48
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__ApplyData; // 0x8
	private static DelegateBridge __Hotfix0__TryOpenItemDetail; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x244ef24 VA: 0x7594a66f24
	public Void OnEnter(ShopPage shopPage) { }
	// RVA: 0x244f104 VA: 0x7594a67104
	private Void _ApplyData(GetClassicGoodListResponse response) { }
	// RVA: 0x244fb5c VA: 0x7594a67b5c
	private Void _TryOpenItemDetail() { }
	// RVA: 0x244fc44 VA: 0x7594a67c44
	public Void .ctor() { }
	// RVA: 0x244fd58 VA: 0x7594a67d58
	private Void <OnEnter>b__7_0(GetClassicGoodListResponse response, Boolean isDataUpdated) { }
}
```