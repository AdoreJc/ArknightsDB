# CrisisV2ShopState

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisShopStateBean _stateBean`

- `CrisisShopViewHolder _viewHolder`

- `Transform _viewHolderContainer`

- `TopMenuDynamicPrefabInstHolder _topmenuHolder`

- `Text _coinV2`

- `CanvasGroup _alphaGroup`

- `CrisisShopEvent _clickEvent`

- `CrisisShopWrapped m_cacheData`

- `CrisisShopViewHolder m_viewHolder`


## Properties

- `CrisisShopViewHolder viewHolder`


## Methods

- `CrisisShopViewHolder get_viewHolder()`

- `Void OnEnterDetail(CrisisShopWrapped)`

- `Void OnOpenV1ShopState()`

- `Void _TryConsumeGuidebook()`

- `Void _SendGetInfo()`

- `IEnumerator ShowDetailCoroutine()`

- `Void <RegisterToDataListener>b__13_0(IStateBean)`

- `Void <OnEnter>b__15_0(GameObject)`

- `Void <OnEnter>b__15_1()`

- `Void <_SendGetInfo>b__19_0(CrisisCommonGetShopDataResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2ShopState : State
{
	private const String GUIDE_BOOK_SUB_SIGNAL; // 0x0
	private CrisisShopStateBean _stateBean; // 0x50
	private CrisisShopViewHolder _viewHolder; // 0x58
	private Transform _viewHolderContainer; // 0x60
	private TopMenuDynamicPrefabInstHolder _topmenuHolder; // 0x68
	private Text _coinV2; // 0x70
	private CanvasGroup _alphaGroup; // 0x78
	private CrisisShopEvent _clickEvent; // 0x80
	private CrisisShopWrapped m_cacheData; // 0x88
	private CrisisShopViewHolder m_viewHolder; // 0x90
	private const Single ITEM_FADE_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_get_viewHolder; // 0x0
	private static DelegateBridge __Hotfix0_OnEnterDetail; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge __Hotfix0_OnOpenV1ShopState; // 0x30
	private static DelegateBridge __Hotfix0__TryConsumeGuidebook; // 0x38
	private static DelegateBridge __Hotfix0__SendGetInfo; // 0x40
	private static DelegateBridge __Hotfix0_ShowDetailCoroutine; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public CrisisShopViewHolder viewHolder { get; }

	// RVA: 0x2be0320 VA: 0x75951f8320
	public CrisisShopViewHolder get_viewHolder() { }
	// RVA: 0x2be0434 VA: 0x75951f8434
	public Void OnEnterDetail(CrisisShopWrapped shopWrapped) { }
	// RVA: 0x2be0564 VA: 0x75951f8564
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2be06dc VA: 0x75951f86dc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2be0744 VA: 0x75951f8744
	protected override Void OnEnter() { }
	// RVA: 0x2be0b30 VA: 0x75951f8b30
	protected override Void OnResume() { }
	// RVA: 0x2be0ca8 VA: 0x75951f8ca8
	public Void OnOpenV1ShopState() { }
	// RVA: 0x2be0a6c VA: 0x75951f8a6c
	private Void _TryConsumeGuidebook() { }
	// RVA: 0x2be0888 VA: 0x75951f8888
	private Void _SendGetInfo() { }
	// RVA: 0x2be0db4 VA: 0x75951f8db4
	private IEnumerator ShowDetailCoroutine() { }
	// RVA: 0x2be0e60 VA: 0x75951f8e60
	public Void .ctor() { }
	// RVA: 0x2be0ed0 VA: 0x75951f8ed0
	private Void <RegisterToDataListener>b__13_0(IStateBean stateBean) { }
	// RVA: 0x2be0f5c VA: 0x75951f8f5c
	private Void <OnEnter>b__15_0(GameObject gameObj) { }
	// RVA: 0x2be1058 VA: 0x75951f9058
	private Void <OnEnter>b__15_1() { }
	// RVA: 0x2be1108 VA: 0x75951f9108
	private Void <_SendGetInfo>b__19_0(CrisisCommonGetShopDataResponse response) { }
	// RVA: 0x2be15f8 VA: 0x75951f95f8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2be1600 VA: 0x75951f9600
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2be1608 VA: 0x75951f9608
	private Void <>xLuaBaseProxy_OnResume() { }
}
```