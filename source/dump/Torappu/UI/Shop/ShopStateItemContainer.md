# ShopStateItemContainer

**Namespace:** `Torappu.UI.Shop`


## Fields

- `StateEngine _stateEngine`

- `UICommonTrackPoint _socialTrackPoint`

- `UICommonTrackPoint _freeLevelGPTrackPoint`

- `TrackPointViewProperty m_socialShopTrackProp`

- `TrackPointViewProperty m_freeGPTrackProp`

- `String m_openItemGoodId`

- `QCShopDetailShopEnum m_qcDetail`

- `Boolean m_isInited`

- `ShopType m_cacheShopType`

- `ShopType m_overrideBackPressedShop`


## Methods

- `ShopType ShopPage_ConsumeOverrideBackPressed()`

- `Void InitData(ShopRouteTarget, String)`

- `Boolean SwitchShopTypeWithService(ShopType, SwitchStateOptions)`

- `IEnumerator _RemoveTopAndReplaceTop()`

- `Boolean _ReplaceTop()`

- `Boolean SwitchShopTypeWithService(ShopType)`

- `Boolean SwitchShopTypeWithItem(ShopRouteTarget, String, SwitchStateOptions)`

- `Boolean SwitchShopTypeWithItem(ShopRouteTarget, String)`

- `Void OnClick(ShopType)`

- `Void _TrySendService(ShopType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopStateItemContainer : PageSingleComponent, IHotfixable
{
	private List`1 _buttonList; // 0x20
	private StateEngine _stateEngine; // 0x28
	private UICommonTrackPoint _socialTrackPoint; // 0x30
	private UICommonTrackPoint _freeLevelGPTrackPoint; // 0x38
	private TrackPointViewProperty m_socialShopTrackProp; // 0x40
	private TrackPointViewProperty m_freeGPTrackProp; // 0x48
	private String m_openItemGoodId; // 0x50
	private QCShopDetailShopEnum m_qcDetail; // 0x58
	private Boolean m_isInited; // 0x5c
	private ShopType m_cacheShopType; // 0x60
	private ShopType m_overrideBackPressedShop; // 0x64
	private static DelegateBridge __Hotfix0_get_openItemGoodId; // 0x0
	private static DelegateBridge __Hotfix0_set_openItemGoodId; // 0x8
	private static DelegateBridge __Hotfix0_get_qcDetail; // 0x10
	private static DelegateBridge __Hotfix0_set_qcDetail; // 0x18
	private static DelegateBridge __Hotfix0_ShopPage_ConsumeOverrideBackPressed; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x28
	private static DelegateBridge __Hotfix0_SwitchShopTypeWithService; // 0x30
	private static DelegateBridge __Hotfix0__RemoveTopAndReplaceTop; // 0x38
	private static DelegateBridge __Hotfix0__ReplaceTop; // 0x40
	private static DelegateBridge __Hotfix1_SwitchShopTypeWithService; // 0x48
	private static DelegateBridge __Hotfix0_SwitchShopTypeWithItem; // 0x50
	private static DelegateBridge __Hotfix1_SwitchShopTypeWithItem; // 0x58
	private static DelegateBridge __Hotfix0_OnClick; // 0x60
	private static DelegateBridge __Hotfix0_CheckIfShopUnlocked; // 0x68
	private static DelegateBridge __Hotfix0_CheckIfShopRouteTargetUnlocked; // 0x70
	private static DelegateBridge __Hotfix0__TrySendService; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public static String openItemGoodId { get; set; }
	public static QCShopDetailShopEnum qcDetail { get; set; }

	// RVA: 0x2468ab8 VA: 0x7594a80ab8
	public static String get_openItemGoodId() { }
	// RVA: 0x2468bbc VA: 0x7594a80bbc
	public static Void set_openItemGoodId(String value) { }
	// RVA: 0x2468cb8 VA: 0x7594a80cb8
	public static QCShopDetailShopEnum get_qcDetail() { }
	// RVA: 0x2468da0 VA: 0x7594a80da0
	public static Void set_qcDetail(QCShopDetailShopEnum value) { }
	// RVA: 0x24682a0 VA: 0x7594a802a0
	public ShopType ShopPage_ConsumeOverrideBackPressed() { }
	// RVA: 0x2467c78 VA: 0x7594a7fc78
	public Void InitData(ShopRouteTarget defaultRouteState, String defaultGood) { }
	// RVA: 0x2468e88 VA: 0x7594a80e88
	public Boolean SwitchShopTypeWithService(ShopType shopType, SwitchStateOptions options) { }
	// RVA: 0x VA: 0x0
	private IEnumerator _RemoveTopAndReplaceTop() { }
	// RVA: 0x VA: 0x0
	private Boolean _ReplaceTop() { }
	// RVA: 0x2461c18 VA: 0x7594a79c18
	public Boolean SwitchShopTypeWithService(ShopType shopType) { }
	// RVA: 0x24692c0 VA: 0x7594a812c0
	public Boolean SwitchShopTypeWithItem(ShopRouteTarget allShopType, String goodId, SwitchStateOptions options) { }
	// RVA: 0x24685ec VA: 0x7594a805ec
	public Boolean SwitchShopTypeWithItem(ShopRouteTarget allShopType, String goodId) { }
	// RVA: 0x24694b8 VA: 0x7594a814b8
	public Void OnClick(ShopType shopType) { }
	// RVA: 0x2468950 VA: 0x7594a80950
	public static Boolean CheckIfShopUnlocked(ShopType shopType) { }
	// RVA: 0x2468090 VA: 0x7594a80090
	public static Boolean CheckIfShopRouteTargetUnlocked(ShopRouteTarget shopRouteTarget) { }
	// RVA: 0x24691a8 VA: 0x7594a811a8
	private Void _TrySendService(ShopType targetShop) { }
	// RVA: 0x2469568 VA: 0x7594a81568
	public Void .ctor() { }
}
```