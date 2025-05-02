# TemplateShopPage

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `TemplateShopResHolder m_cacheResHolder`


## Methods

- `String GetShopId()`

- `TemplateShopSource GetShopSourceType()`

- `String GetReplicateActId()`

- `Void <>xLuaBaseProxy_OnStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopPage : StateEnginePage
{
	public static TemplateCommonShopGoodViewModel detailViewModelCache; // 0x0
	private List`1 _resBarList; // 0xe8
	private TemplateShopResHolder m_cacheResHolder; // 0xf0
	private static DelegateBridge __Hotfix0_OnStart; // 0x8
	private static DelegateBridge __Hotfix0_GetShopId; // 0x10
	private static DelegateBridge __Hotfix0_GetShopSourceType; // 0x18
	private static DelegateBridge __Hotfix0_GetReplicateActId; // 0x20
	private static DelegateBridge __Hotfix0_GetShopIdStatic; // 0x28
	private static DelegateBridge __Hotfix0_GetReplicateActIdStatic; // 0x30
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_HandlerBuyRequest; // 0x40
	private static DelegateBridge __Hotfix0_JumpToDetailState; // 0x48
	private static DelegateBridge __Hotfix0_LoadTemplateShopResHolder; // 0x50
	private static DelegateBridge __Hotfix0_LoadTemplateShopTitle; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2358458 VA: 0x7594970458
	protected override Void OnStart() { }
	// RVA: 0x2358544 VA: 0x7594970544
	public String GetShopId() { }
	// RVA: 0x235873c VA: 0x759497073c
	public TemplateShopSource GetShopSourceType() { }
	// RVA: 0x2358808 VA: 0x7594970808
	public String GetReplicateActId() { }
	// RVA: 0x23588e4 VA: 0x75949708e4
	public static String GetShopIdStatic() { }
	// RVA: 0x2354660 VA: 0x759496c660
	public static String GetReplicateActIdStatic() { }
	// RVA: 0x23589ec VA: 0x75949709ec
	private static IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onFinish) { }
	// RVA: 0x2352d58 VA: 0x759496ad58
	public static Void HandlerBuyRequest(Int32 count, TemplateCommonShopGoodViewModel viewModel, Action onFinish) { }
	// RVA: 0x2358af4 VA: 0x7594970af4
	public static Void JumpToDetailState(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x2355654 VA: 0x759496d654
	public static TemplateShopResHolder LoadTemplateShopResHolder() { }
	// RVA: 0x23558b4 VA: 0x759496d8b4
	public static GameObject LoadTemplateShopTitle() { }
	// RVA: 0x2358cf0 VA: 0x7594970cf0
	public Void .ctor() { }
	// RVA: 0x2358d60 VA: 0x7594970d60
	private Void <>xLuaBaseProxy_OnStart() { }
}
```