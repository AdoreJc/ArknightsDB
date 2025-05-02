# ShopGetServiceCenter

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Boolean m_isSendingService`


## Methods

- `Void TrySendService(String)`

- `Void MarkServiceDirty(String)`

- `Void BindToResponse(String, Action`2)`

- `Void BindToQCResponse(Action`1)`

- `RespWrapper _EnsureRespWrapper(String)`

- `Void _RouteService(String)`

- `Void _TryFetchMultiCurrencyDataIfNecessary(Action)`

- `Void _SendService(String, RequestType)`

- `Void _OnServiceResponse(String, IShopGetResposne)`

- `Void _SendShopSkinRequest(String)`

- `Void _SendShopCashRequest(String)`

- `Void _SendShopQCHighRequest(String)`

- `Void _SendShopQCLowRequest(String)`

- `Void _SendShopQCClassicRequest(String)`

- `Void _SendShopQCExtraRequest(String)`

- `Void _SendShopEPGSRequest(String)`

- `Void _SendShopREPRequest(String)`

- `Void _SendShopLMGTSRequest(String)`

- `Void _SendShopGPRequest(String)`

- `Void _SendShopSocialRequest(String)`

- `Void _SendShopStateRequest(String)`

- `Void _SendShopFurnitureStateRequest(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGetServiceCenter : PageSingleComponent, IHotfixable
{
	private const Int64 RESP_TIMEOUT_SECS; // 0x0
	private ListDict`2 m_responses; // 0x20
	private ListDict`2 m_listeners; // 0x28
	private Action`1 m_qcShopListener; // 0x30
	private Boolean m_isSendingService; // 0x38
	private static DelegateBridge __Hotfix0_MarkHighAndClassicServiceDirty; // 0x0
	private static DelegateBridge __Hotfix0_MarkCashServicesDirty; // 0x8
	private static DelegateBridge __Hotfix0_SendUpdateServiceAfterBuying; // 0x10
	private static DelegateBridge __Hotfix1_SendUpdateServiceAfterBuying; // 0x18
	private static DelegateBridge __Hotfix0__MarkDirtyAndSendUpdateService; // 0x20
	private static DelegateBridge __Hotfix0_TrySendService; // 0x28
	private static DelegateBridge __Hotfix0_MarkServiceDirty; // 0x30
	private static DelegateBridge __Hotfix0_BindToResponse; // 0x38
	private static DelegateBridge __Hotfix0_BindToQCResponse; // 0x40
	private static DelegateBridge __Hotfix0_GetServiceCodeByShop; // 0x48
	private static DelegateBridge __Hotfix0__InvokeRespCallback; // 0x50
	private static DelegateBridge __Hotfix0__EnsureRespWrapper; // 0x58
	private static DelegateBridge __Hotfix0__RouteService; // 0x60
	private static DelegateBridge __Hotfix0__TryFetchMultiCurrencyDataIfNecessary; // 0x68
	private static DelegateBridge __Hotfix0__SendService; // 0x70
	private static DelegateBridge __Hotfix0__OnServiceResponse; // 0x78
	private static DelegateBridge __Hotfix0__SendShopSkinRequest; // 0x80
	private static DelegateBridge __Hotfix0__SendShopCashRequest; // 0x88
	private static DelegateBridge __Hotfix0__SendShopQCHighRequest; // 0x90
	private static DelegateBridge __Hotfix0__SendShopQCLowRequest; // 0x98
	private static DelegateBridge __Hotfix0__SendShopQCClassicRequest; // 0xa0
	private static DelegateBridge __Hotfix0__SendShopQCExtraRequest; // 0xa8
	private static DelegateBridge __Hotfix0__SendShopEPGSRequest; // 0xb0
	private static DelegateBridge __Hotfix0__SendShopREPRequest; // 0xb8
	private static DelegateBridge __Hotfix0__SendShopLMGTSRequest; // 0xc0
	private static DelegateBridge __Hotfix0__SendShopGPRequest; // 0xc8
	private static DelegateBridge __Hotfix0__SendShopSocialRequest; // 0xd0
	private static DelegateBridge __Hotfix0__SendShopStateRequest; // 0xd8
	private static DelegateBridge __Hotfix0__SendShopFurnitureStateRequest; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8


	// RVA: 0x2428c5c VA: 0x7594a40c5c
	public static Void MarkHighAndClassicServiceDirty(String buyServiceCode) { }
	// RVA: 0x2429298 VA: 0x7594a41298
	public static Void MarkCashServicesDirty() { }
	// RVA: 0x2428e4c VA: 0x7594a40e4c
	public static Void SendUpdateServiceAfterBuying(String buyServiceCode) { }
	// RVA: 0x242958c VA: 0x7594a4158c
	public static Void SendUpdateServiceAfterBuying(ShopType shopType, QCShopDetailShopEnum qcShopType) { }
	// RVA: 0x24293c0 VA: 0x7594a413c0
	private static Void _MarkDirtyAndSendUpdateService(String listServiceCode) { }
	// RVA: 0x24298cc VA: 0x7594a418cc
	public Void TrySendService(String serviceCode) { }
	// RVA: 0x2428d74 VA: 0x7594a40d74
	public Void MarkServiceDirty(String serviceCode) { }
	// RVA: 0x VA: 0x0
	public Void BindToResponse(String serviceCode, Action`2 callback) { }
	// RVA: 0x2429e5c VA: 0x7594a41e5c
	public Void BindToQCResponse(Action`1 callback) { }
	// RVA: 0x2429610 VA: 0x7594a41610
	public static String GetServiceCodeByShop(ShopType shopType, QCShopDetailShopEnum qcDetail) { }
	// RVA: 0x VA: 0x0
	private static Void _InvokeRespCallback(String serviceCode, Action`2 callback, IShopGetResposne response, Boolean isResponseUpdated) { }
	// RVA: 0x2429a8c VA: 0x7594a41a8c
	private RespWrapper _EnsureRespWrapper(String serviceCode) { }
	// RVA: 0x2429efc VA: 0x7594a41efc
	private Void _RouteService(String serviceCode) { }
	// RVA: 0x2429c24 VA: 0x7594a41c24
	private Void _TryFetchMultiCurrencyDataIfNecessary(Action nextStep) { }
	// RVA: 0x VA: 0x0
	private Void _SendService(String serviceCode, RequestType request) { }
	// RVA: 0x242b02c VA: 0x7594a4302c
	private Void _OnServiceResponse(String serviceCode, IShopGetResposne response) { }
	// RVA: 0x242a428 VA: 0x7594a42428
	private Void _SendShopSkinRequest(String serviceCode) { }
	// RVA: 0x242a544 VA: 0x7594a42544
	private Void _SendShopCashRequest(String serviceCode) { }
	// RVA: 0x242a610 VA: 0x7594a42610
	private Void _SendShopQCHighRequest(String serviceCode) { }
	// RVA: 0x242a6dc VA: 0x7594a426dc
	private Void _SendShopQCLowRequest(String serviceCode) { }
	// RVA: 0x242a7a8 VA: 0x7594a427a8
	private Void _SendShopQCClassicRequest(String serviceCode) { }
	// RVA: 0x242a874 VA: 0x7594a42874
	private Void _SendShopQCExtraRequest(String serviceCode) { }
	// RVA: 0x242ae8c VA: 0x7594a42e8c
	private Void _SendShopEPGSRequest(String serviceCode) { }
	// RVA: 0x242af58 VA: 0x7594a42f58
	private Void _SendShopREPRequest(String serviceCode) { }
	// RVA: 0x242adc0 VA: 0x7594a42dc0
	private Void _SendShopLMGTSRequest(String serviceCode) { }
	// RVA: 0x242a940 VA: 0x7594a42940
	private Void _SendShopGPRequest(String serviceCode) { }
	// RVA: 0x242aa0c VA: 0x7594a42a0c
	private Void _SendShopSocialRequest(String serviceCode) { }
	// RVA: 0x242aad8 VA: 0x7594a42ad8
	private Void _SendShopStateRequest(String serviceCode) { }
	// RVA: 0x242acf4 VA: 0x7594a42cf4
	private Void _SendShopFurnitureStateRequest(String serviceCode) { }
	// RVA: 0x242b1ac VA: 0x7594a431ac
	public Void .ctor() { }
}
```