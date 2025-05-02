# BuyLaborStateBean

**Namespace:** `Torappu.Building.UI`


## Fields

- `Int32 m_addCount`

- `BuildingLaborViewModel m_laborViewModel`

- `ActionPointViewModel _apviewModel`


## Properties

- `Int32 addCount`

- `Int32 maxCount`

- `Int32 apMaxCount`

- `Int32 laborCount`

- `Int32 laborLimit`

- `Int32 minCount`


## Methods

- `Int32 get_addCount()`

- `Void set_addCount(Int32)`

- `Int32 get_maxCount()`

- `Int32 get_apMaxCount()`

- `Int32 get_laborCount()`

- `Int32 get_laborLimit()`

- `Int32 get_minCount()`

- `Void OnInitialize()`

- `Void FixedUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuyLaborStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	private Int32 m_addCount; // 0x18
	private BuildingLaborViewModel m_laborViewModel; // 0x20
	private ActionPointViewModel _apviewModel; // 0x28
	private static DelegateBridge __Hotfix0_get_addCount; // 0x0
	private static DelegateBridge __Hotfix0_set_addCount; // 0x8
	private static DelegateBridge __Hotfix0_get_maxCount; // 0x10
	private static DelegateBridge __Hotfix0_get_apMaxCount; // 0x18
	private static DelegateBridge __Hotfix0_get_laborCount; // 0x20
	private static DelegateBridge __Hotfix0_get_laborLimit; // 0x28
	private static DelegateBridge __Hotfix0_get_minCount; // 0x30
	private static DelegateBridge __Hotfix0_OnInitialize; // 0x38
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 addCount { get; set; }
	public Int32 maxCount { get; }
	public Int32 apMaxCount { get; }
	public Int32 laborCount { get; }
	public Int32 laborLimit { get; }
	public Int32 minCount { get; }

	// RVA: 0x3d2f360 VA: 0x7596347360
	public Int32 get_addCount() { }
	// RVA: 0x3d2f478 VA: 0x7596347478
	public Void set_addCount(Int32 value) { }
	// RVA: 0x3d2f728 VA: 0x7596347728
	public Int32 get_maxCount() { }
	// RVA: 0x3d2fabc VA: 0x7596347abc
	public Int32 get_apMaxCount() { }
	// RVA: 0x3d2eca4 VA: 0x7596346ca4
	public Int32 get_laborCount() { }
	// RVA: 0x3d2ed18 VA: 0x7596346d18
	public Int32 get_laborLimit() { }
	// RVA: 0x3d2f62c VA: 0x759634762c
	public Int32 get_minCount() { }
	// RVA: 0x3d2ebf4 VA: 0x7596346bf4
	public Void OnInitialize() { }
	// RVA: 0x3d2fb90 VA: 0x7596347b90
	private Void FixedUpdate() { }
	// RVA: 0x3d2fc0c VA: 0x7596347c0c
	public Void .ctor() { }
}
```