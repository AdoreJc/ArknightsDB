# TacticalBuffGroupModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Boolean m_hasTowerPass`

- `Int32 m_currentStep`

- `Int32 m_totalStepCount`


## Properties

- `Int32 totalStepCount`

- `Int32 currentStep`


## Methods

- `Int32 get_totalStepCount()`

- `Int32 get_currentStep()`

- `Boolean CanToggleBuff()`

- `Void InitData(PlayerTower)`

- `String _GetSavedBuffIdByProfession(TowerTactical, ProfessionCategory)`

- `Void SelectBuff(ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class TacticalBuffGroupModel : IHotfixable
{
	private Boolean m_hasTowerPass; // 0x10
	private List`1 m_tacticalGroupList; // 0x18
	private Int32 m_currentStep; // 0x20
	private Int32 m_totalStepCount; // 0x24
	private static DelegateBridge __Hotfix0_get_tacticalGroupList; // 0x0
	private static DelegateBridge __Hotfix0_get_totalStepCount; // 0x8
	private static DelegateBridge __Hotfix0_get_currentStep; // 0x10
	private static DelegateBridge __Hotfix0_CanToggleBuff; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x20
	private static DelegateBridge __Hotfix0__GetSavedBuffIdByProfession; // 0x28
	private static DelegateBridge __Hotfix0_SelectBuff; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public List`1 tacticalGroupList { get; }
	public Int32 totalStepCount { get; }
	public Int32 currentStep { get; }

	// RVA: 0x2c8a608 VA: 0x75952a2608
	public List`1 get_tacticalGroupList() { }
	// RVA: 0x2c8bc90 VA: 0x75952a3c90
	public Int32 get_totalStepCount() { }
	// RVA: 0x2c8bcf8 VA: 0x75952a3cf8
	public Int32 get_currentStep() { }
	// RVA: 0x2c8a0d8 VA: 0x75952a20d8
	public Boolean CanToggleBuff() { }
	// RVA: 0x2c8b908 VA: 0x75952a3908
	public Void InitData(PlayerTower towerPlayerData) { }
	// RVA: 0x2c8bfe0 VA: 0x75952a3fe0
	private String _GetSavedBuffIdByProfession(TowerTactical savedTactical, ProfessionCategory profession) { }
	// RVA: 0x2c8a140 VA: 0x75952a2140
	public Void SelectBuff(ProfessionCategory profession) { }
	// RVA: 0x2c8c2b8 VA: 0x75952a42b8
	public Void .ctor() { }
}
```