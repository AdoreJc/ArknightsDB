# Act5D1RuneShopState

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Act5D1RuneShopStateBean _stateBean`

- `Act5D1RuneShopItem _itemPrefab`

- `RectTransform _listRoot`

- `Act5D1ResourceBar _resourceBar`

- `Act5D1ShopCommonViewModel forOpenViewModel`


## Methods

- `Void _SendGetGoodList()`

- `Void TransDataToDetail(IStateBean)`

- `Void _Syn(Act5D1GetGoodsListResponse)`

- `Void NotifyBuyComplete()`

- `Void <_SendGetGoodList>b__7_0(Act5D1GetGoodsListResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneShopState : PopupFadeState
{
	private Act5D1RuneShopStateBean _stateBean; // 0x70
	private Act5D1RuneShopItem _itemPrefab; // 0x78
	private RectTransform _listRoot; // 0x80
	private Act5D1ResourceBar _resourceBar; // 0x88
	public Act5D1ShopCommonViewModel forOpenViewModel; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__SendGetGoodList; // 0x10
	private static DelegateBridge __Hotfix0_TransDataToDetail; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge __Hotfix0__Syn; // 0x30
	private static DelegateBridge __Hotfix0_NotifyBuyComplete; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x31d5c44 VA: 0x75957edc44
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31d5cac VA: 0x75957edcac
	protected override Void OnEnter() { }
	// RVA: 0x31d5d14 VA: 0x75957edd14
	private Void _SendGetGoodList() { }
	// RVA: 0x31d5f54 VA: 0x75957edf54
	public Void TransDataToDetail(IStateBean stateBean) { }
	// RVA: 0x31d6034 VA: 0x75957ee034
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x31d627c VA: 0x75957ee27c
	protected override Void OnResume() { }
	// RVA: 0x31d6304 VA: 0x75957ee304
	private Void _Syn(Act5D1GetGoodsListResponse response) { }
	// RVA: 0x31d59d0 VA: 0x75957ed9d0
	public Void NotifyBuyComplete() { }
	// RVA: 0x31d67a4 VA: 0x75957ee7a4
	public Void .ctor() { }
	// RVA: 0x31d6814 VA: 0x75957ee814
	private Void <_SendGetGoodList>b__7_0(Act5D1GetGoodsListResponse response) { }
	// RVA: 0x31d6818 VA: 0x75957ee818
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x31d6820 VA: 0x75957ee820
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x31d6828 VA: 0x75957ee828
	private Void <>xLuaBaseProxy_OnResume() { }
}
```