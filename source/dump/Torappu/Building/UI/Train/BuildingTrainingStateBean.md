# BuildingTrainingStateBean

**Namespace:** `Torappu.Building.UI.Train`


## Fields

- `SkillGroupViewProperty skillProperty`

- `Int32 traineeInstId`

- `Int32 selectSkillIndex`

- `Int32 targetSkillLevel`

- `Int32 targetSpecialLevel`

- `Int32 m_specialLvlUpTime`


## Properties

- `Int32 specialLvlUpTime`


## Methods

- `Int32 get_specialLvlUpTime()`

- `String CheckAllSKillRequirements()`

- `String CheckSpecializedSKillRequirements()`

- `Void RefreshAllData()`

- `Void RefreshSpecialData()`

- `Boolean CheckIfTraineeValidAndIdle()`

- `String _CheckRequireViewModels(IList`1)`

- `Void _LoadAllLvlUpData()`

- `Void _LoadSpecialLvlUpData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Train
public class BuildingTrainingStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public SkillGroupViewProperty skillProperty; // 0x18
	public Int32 traineeInstId; // 0x20
	public Int32 selectSkillIndex; // 0x24
	public Int32 targetSkillLevel; // 0x28
	public Int32 targetSpecialLevel; // 0x2c
	private RequireViewModel[] m_cacheViewModel; // 0x30
	private RequireViewModel[] m_cacheSpecialViewModel; // 0x38
	private Int32 m_specialLvlUpTime; // 0x40
	private static DelegateBridge __Hotfix0_get_specialLvlUpTime; // 0x0
	private static DelegateBridge __Hotfix0_get_requireSpecialItem; // 0x8
	private static DelegateBridge __Hotfix0_get_requireItem; // 0x10
	private static DelegateBridge __Hotfix0_CheckAllSKillRequirements; // 0x18
	private static DelegateBridge __Hotfix0_CheckSpecializedSKillRequirements; // 0x20
	private static DelegateBridge __Hotfix0_RefreshAllData; // 0x28
	private static DelegateBridge __Hotfix0_RefreshSpecialData; // 0x30
	private static DelegateBridge __Hotfix0_CheckIfTraineeValidAndIdle; // 0x38
	private static DelegateBridge __Hotfix0__CheckRequireViewModels; // 0x40
	private static DelegateBridge __Hotfix0__LoadAllLvlUpData; // 0x48
	private static DelegateBridge __Hotfix0__LoadSpecialLvlUpData; // 0x50
	private static DelegateBridge __Hotfix0__ParseSkillAllLvlUpRequirements; // 0x58
	private static DelegateBridge __Hotfix0__ParseSkillSpecialLvlUpRequirements; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Int32 specialLvlUpTime { get; }
	public RequireViewModel[] requireSpecialItem { get; }
	public RequireViewModel[] requireItem { get; }

	// RVA: 0x3d77de4 VA: 0x759638fde4
	public Int32 get_specialLvlUpTime() { }
	// RVA: 0x3d781a0 VA: 0x75963901a0
	public RequireViewModel[] get_requireSpecialItem() { }
	// RVA: 0x3d78210 VA: 0x7596390210
	public RequireViewModel[] get_requireItem() { }
	// RVA: 0x3d785c8 VA: 0x75963905c8
	public String CheckAllSKillRequirements() { }
	// RVA: 0x3d789a8 VA: 0x75963909a8
	public String CheckSpecializedSKillRequirements() { }
	// RVA: 0x3d78a14 VA: 0x7596390a14
	public Void RefreshAllData() { }
	// RVA: 0x3d78a7c VA: 0x7596390a7c
	public Void RefreshSpecialData() { }
	// RVA: 0x3d78ae4 VA: 0x7596390ae4
	public Boolean CheckIfTraineeValidAndIdle() { }
	// RVA: 0x3d78634 VA: 0x7596390634
	private String _CheckRequireViewModels(IList`1 models) { }
	// RVA: 0x3d78280 VA: 0x7596390280
	private Void _LoadAllLvlUpData() { }
	// RVA: 0x3d77e54 VA: 0x759638fe54
	private Void _LoadSpecialLvlUpData() { }
	// RVA: 0x3d78c28 VA: 0x7596390c28
	private RequireViewModel[] _ParseSkillAllLvlUpRequirements(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x3d7921c VA: 0x759639121c
	private RequireViewModel[] _ParseSkillSpecialLvlUpRequirements(PlayerCharacter playerChar, CharacterData charData, Int32 skillIndex) { }
	// RVA: 0x3d79754 VA: 0x7596391754
	public Void .ctor() { }
}
```