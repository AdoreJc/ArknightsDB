# CrisisShopState

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `CrisisShopStateBean _stateBean`

- `CrisisShopViewHolder _viewHolder`

- `Transform _viewHolderContainer`

- `CanvasGroup _alphaGroup`

- `CrisisShopEvent _clickEvent`

- `CrisisShopViewHolder m_viewHolder`

- `CrisisShopWrapped m_cacheData`


## Properties

- `CrisisShopViewHolder viewHolder`


## Methods

- `CrisisShopViewHolder get_viewHolder()`

- `Void OnEnterDetail(CrisisShopWrapped)`

- `Void _SendGetInfo()`

- `IEnumerator ShowDetailCoroutine()`

- `Void <RegisterToDataListener>b__10_0(IStateBean)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <_SendGetInfo>b__16_0(CrisisCommonGetShopDataResponse)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopState : PopupFadeState
{
	private CrisisShopStateBean _stateBean; // 0x70
	private CrisisShopViewHolder _viewHolder; // 0x78
	private Transform _viewHolderContainer; // 0x80
	private CanvasGroup _alphaGroup; // 0x88
	private CrisisShopEvent _clickEvent; // 0x90
	private CrisisShopViewHolder m_viewHolder; // 0x98
	private CrisisShopWrapped m_cacheData; // 0xa0
	private const Single ITEM_FADE_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_get_viewHolder; // 0x0
	private static DelegateBridge __Hotfix0_OnEnterDetail; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnResume; // 0x38
	private static DelegateBridge __Hotfix0__SendGetInfo; // 0x40
	private static DelegateBridge __Hotfix0_ShowDetailCoroutine; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public CrisisShopViewHolder viewHolder { get; }

	// RVA: 0x2c1bc1c VA: 0x7595233c1c
	public CrisisShopViewHolder get_viewHolder() { }
	// RVA: 0x2c1bd30 VA: 0x7595233d30
	public Void OnEnterDetail(CrisisShopWrapped shopWrapped) { }
	// RVA: 0x2c1be60 VA: 0x7595233e60
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2c1bfd8 VA: 0x7595233fd8
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2c1c16c VA: 0x759523416c
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2c1c358 VA: 0x7595234358
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c1c3c0 VA: 0x75952343c0
	protected override Void OnEnter() { }
	// RVA: 0x2c1c680 VA: 0x7595234680
	protected override Void OnResume() { }
	// RVA: 0x2c1c49c VA: 0x759523449c
	private Void _SendGetInfo() { }
	// RVA: 0x2c1c790 VA: 0x7595234790
	private IEnumerator ShowDetailCoroutine() { }
	// RVA: 0x2c1c864 VA: 0x7595234864
	public Void .ctor() { }
	// RVA: 0x2c1c8d4 VA: 0x75952348d4
	private Void <RegisterToDataListener>b__10_0(IStateBean stateBean) { }
	// RVA: 0x2c1c95c VA: 0x759523495c
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x2c1c984 VA: 0x7595234984
	private Void <_SendGetInfo>b__16_0(CrisisCommonGetShopDataResponse response) { }
	// RVA: 0x2c1ce40 VA: 0x7595234e40
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2c1ce48 VA: 0x7595234e48
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2c1ce70 VA: 0x7595234e70
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
	// RVA: 0x2c1ce98 VA: 0x7595234e98
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c1cea0 VA: 0x7595234ea0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```