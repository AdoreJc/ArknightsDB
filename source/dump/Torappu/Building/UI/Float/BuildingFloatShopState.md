# BuildingFloatShopState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `BuildingFloatShopInfoView _shopInfoView`

- `FloatShopInfoViewProperty m_shopInfoProp`


## Methods

- `Void EventOnShopClick()`

- `Void _LoadData()`

- `Void <>xLuaBaseProxy_Start()`

- `Void <>xLuaBaseProxy_OnPlayerDataChanged(Object)`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatShopState : BuildingFloatVaultInfoState
{
	private BuildingFloatShopInfoView _shopInfoView; // 0xa0
	private FloatShopInfoViewProperty m_shopInfoProp; // 0xa8
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x18
	private static DelegateBridge __Hotfix0_EventOnShopClick; // 0x20
	private static DelegateBridge __Hotfix0__LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override FloatState state { get; }

	// RVA: 0x3e1fecc VA: 0x7596437ecc
	protected override FloatState get_state() { }
	// RVA: 0x3e1ff34 VA: 0x7596437f34
	protected override Void Start() { }
	// RVA: 0x3e2000c VA: 0x759643800c
	protected override Void OnPlayerDataChanged(Object args) { }
	// RVA: 0x3e202ec VA: 0x75964382ec
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e2038c VA: 0x759643838c
	public Void EventOnShopClick() { }
	// RVA: 0x3e20098 VA: 0x7596438098
	private Void _LoadData() { }
	// RVA: 0x3e2054c VA: 0x759643854c
	public Void .ctor() { }
	// RVA: 0x3e20628 VA: 0x7596438628
	private Void <>xLuaBaseProxy_Start() { }
	// RVA: 0x3e20630 VA: 0x7596438630
	private Void <>xLuaBaseProxy_OnPlayerDataChanged(Object P0) { }
	// RVA: 0x3e20638 VA: 0x7596438638
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
}
```