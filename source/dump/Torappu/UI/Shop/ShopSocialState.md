# ShopSocialState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopSocialStateBean _stateBean`

- `ShopSocialView _itemView`

- `TwoStateToggle _twoState`

- `UICommonTrackPoint _socialTrackPoint`

- `TrackPointViewProperty m_socialShopTrackProp`


## Methods

- `Void _UpdateSocialState()`

- `Void SendGetSocialRequest()`

- `Void OpenSocialDetail()`

- `Void ApplyData(GetSocialGoodListResponse)`

- `Void <RegisterToDataListener>b__6_0(IStateBean)`

- `Void <_UpdateSocialState>b__9_0(GetSocialGoodListResponse, Boolean)`

- `Void <SendGetSocialRequest>b__10_0(ReceiveSocialPointResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopSocialState : ShopCommonState
{
	private ShopSocialStateBean _stateBean; // 0x68
	private ShopSocialView _itemView; // 0x70
	private TwoStateToggle _twoState; // 0x78
	private UICommonTrackPoint _socialTrackPoint; // 0x80
	private TrackPointViewProperty m_socialShopTrackProp; // 0x88
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0__UpdateSocialState; // 0x20
	private static DelegateBridge __Hotfix0_SendGetSocialRequest; // 0x28
	private static DelegateBridge __Hotfix0_OpenSocialDetail; // 0x30
	private static DelegateBridge __Hotfix0_ApplyData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x246d63c VA: 0x7594a8563c
	protected override Void OnEnter() { }
	// RVA: 0x246d860 VA: 0x7594a85860
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x246d9d8 VA: 0x7594a859d8
	protected override Void OnResume() { }
	// RVA: 0x246daa8 VA: 0x7594a85aa8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x246d740 VA: 0x7594a85740
	private Void _UpdateSocialState() { }
	// RVA: 0x246db10 VA: 0x7594a85b10
	public Void SendGetSocialRequest() { }
	// RVA: 0x246ddc4 VA: 0x7594a85dc4
	public Void OpenSocialDetail() { }
	// RVA: 0x246ded0 VA: 0x7594a85ed0
	public Void ApplyData(GetSocialGoodListResponse response) { }
	// RVA: 0x246e544 VA: 0x7594a86544
	public Void .ctor() { }
	// RVA: 0x246e5f4 VA: 0x7594a865f4
	private Void <RegisterToDataListener>b__6_0(IStateBean stateBean) { }
	// RVA: 0x246e6ac VA: 0x7594a866ac
	private Void <_UpdateSocialState>b__9_0(GetSocialGoodListResponse response, Boolean isDataUpdated) { }
	// RVA: 0x246e6b8 VA: 0x7594a866b8
	private Void <SendGetSocialRequest>b__10_0(ReceiveSocialPointResponse response) { }
	// RVA: 0x246e820 VA: 0x7594a86820
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x246e828 VA: 0x7594a86828
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x246e830 VA: 0x7594a86830
	private Void <>xLuaBaseProxy_OnResume() { }
}
```