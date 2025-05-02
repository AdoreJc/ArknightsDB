# TemplateShopEmptyState

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `TemplateCommonShopStateBean m_stateBean`


## Methods

- `Void _ToListState(IStateBean)`

- `Void _ToRarityState(IStateBean)`

- `Void <OnEnter>b__5_0(TemplateGetGoodListResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopEmptyState : State
{
	private TemplateCommonShopStateBean m_stateBean; // 0x50
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0__ToListState; // 0x10
	private static DelegateBridge __Hotfix0__ToRarityState; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x235338c VA: 0x759496b38c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23533f4 VA: 0x759496b3f4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x23535e8 VA: 0x759496b5e8
	private Void _ToListState(IStateBean stateBean) { }
	// RVA: 0x23536d4 VA: 0x759496b6d4
	private Void _ToRarityState(IStateBean stateBean) { }
	// RVA: 0x23537c0 VA: 0x759496b7c0
	protected override Void OnEnter() { }
	// RVA: 0x2353a0c VA: 0x759496ba0c
	public Void .ctor() { }
	// RVA: 0x2353b28 VA: 0x759496bb28
	private Void <OnEnter>b__5_0(TemplateGetGoodListResponse response) { }
	// RVA: 0x2353da4 VA: 0x759496bda4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2353dac VA: 0x759496bdac
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```