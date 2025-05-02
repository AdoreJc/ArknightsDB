# ClimbTowerSweepEndingStateBean

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSweepEndingProperty m_prop`

- `ClimbTowerSweepResponse m_inputRes`


## Properties

- `ClimbTowerSweepEndingProperty prop`


## Methods

- `ClimbTowerSweepEndingProperty get_prop()`

- `Void LoadData()`

- `Void SetDataSource(ClimbTowerSweepResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSweepEndingStateBean : IStateBean, IHotfixable
{
	private ClimbTowerSweepEndingProperty m_prop; // 0x10
	private ClimbTowerSweepResponse m_inputRes; // 0x18
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SetDataSource; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public ClimbTowerSweepEndingProperty prop { get; }

	// RVA: 0x2cd3320 VA: 0x75952eb320
	public ClimbTowerSweepEndingProperty get_prop() { }
	// RVA: 0x2cd328c VA: 0x75952eb28c
	public Void LoadData() { }
	// RVA: 0x2cd3d40 VA: 0x75952ebd40
	public Void SetDataSource(ClimbTowerSweepResponse input) { }
	// RVA: 0x2cd37f4 VA: 0x75952eb7f4
	public Void .ctor() { }
}
```