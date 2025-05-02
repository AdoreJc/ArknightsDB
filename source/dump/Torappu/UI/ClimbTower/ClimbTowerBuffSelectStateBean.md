# ClimbTowerBuffSelectStateBean

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `TacticalBuffGroupProp m_prop`

- `Boolean <isPlanFree>k__BackingField`

- `Boolean <hasTowerPass>k__BackingField`


## Properties

- `TacticalBuffGroupProp buffGroupProp`

- `Boolean isPlanFree`

- `Boolean hasTowerPass`

- `TowerGameStrategy currentStrategy`


## Methods

- `TacticalBuffGroupProp get_buffGroupProp()`

- `Boolean get_isPlanFree()`

- `Void set_isPlanFree(Boolean)`

- `Boolean get_hasTowerPass()`

- `Void set_hasTowerPass(Boolean)`

- `TowerGameStrategy get_currentStrategy()`

- `Void InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBuffSelectStateBean : IStateBean, IHotfixable
{
	private TacticalBuffGroupProp m_prop; // 0x10
	private Boolean <isPlanFree>k__BackingField; // 0x18
	private Boolean <hasTowerPass>k__BackingField; // 0x19
	private static DelegateBridge __Hotfix0_get_buffGroupProp; // 0x0
	private static DelegateBridge __Hotfix0_get_isPlanFree; // 0x8
	private static DelegateBridge __Hotfix0_set_isPlanFree; // 0x10
	private static DelegateBridge __Hotfix0_get_hasTowerPass; // 0x18
	private static DelegateBridge __Hotfix0_set_hasTowerPass; // 0x20
	private static DelegateBridge __Hotfix0_get_currentStrategy; // 0x28
	private static DelegateBridge __Hotfix0_InitData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public TacticalBuffGroupProp buffGroupProp { get; }
	public Boolean isPlanFree { get; set; }
	public Boolean hasTowerPass { get; set; }
	public TowerGameStrategy currentStrategy { get; }

	// RVA: 0x2c899d0 VA: 0x75952a19d0
	public TacticalBuffGroupProp get_buffGroupProp() { }
	// RVA: 0x2c89a38 VA: 0x75952a1a38
	public Boolean get_isPlanFree() { }
	// RVA: 0x2c8b808 VA: 0x75952a3808
	public Void set_isPlanFree(Boolean value) { }
	// RVA: 0x2c8b750 VA: 0x75952a3750
	public Boolean get_hasTowerPass() { }
	// RVA: 0x2c8b888 VA: 0x75952a3888
	public Void set_hasTowerPass(Boolean value) { }
	// RVA: 0x2c8ae00 VA: 0x75952a2e00
	public TowerGameStrategy get_currentStrategy() { }
	// RVA: 0x2c898d8 VA: 0x75952a18d8
	public Void InitData() { }
	// RVA: 0x2c8b2ac VA: 0x75952a32ac
	public Void .ctor() { }
}
```