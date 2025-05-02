# CharacterInfoSelectSkillBean

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `SkillGroupViewProperty skillProperty`

- `Int32 charInstId`

- `Int32 skillIndex`

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

- `String _CheckRequireViewModels(IList`1)`

- `Void _LoadAllLvlUpData()`

- `Void _LoadSpecialLvlUpData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSelectSkillBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public SkillGroupViewProperty skillProperty; // 0x18
	public Int32 charInstId; // 0x20
	public Int32 skillIndex; // 0x24
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
	private static DelegateBridge __Hotfix0__CheckRequireViewModels; // 0x38
	private static DelegateBridge __Hotfix0__LoadAllLvlUpData; // 0x40
	private static DelegateBridge __Hotfix0__LoadSpecialLvlUpData; // 0x48
	private static DelegateBridge __Hotfix0__ParseSkillAllLvlUpRequirements; // 0x50
	private static DelegateBridge __Hotfix0__ParseSkillSpecialLvlUpRequirements; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Int32 specialLvlUpTime { get; }
	public RequireViewModel[] requireSpecialItem { get; }
	public RequireViewModel[] requireItem { get; }

	// RVA: 0x2d63794 VA: 0x759537b794
	public Int32 get_specialLvlUpTime() { }
	// RVA: 0x2d63b58 VA: 0x759537bb58
	public RequireViewModel[] get_requireSpecialItem() { }
	// RVA: 0x2d63bc8 VA: 0x759537bbc8
	public RequireViewModel[] get_requireItem() { }
	// RVA: 0x2d63f88 VA: 0x759537bf88
	public String CheckAllSKillRequirements() { }
	// RVA: 0x2d64368 VA: 0x759537c368
	public String CheckSpecializedSKillRequirements() { }
	// RVA: 0x2d643d4 VA: 0x759537c3d4
	public Void RefreshAllData() { }
	// RVA: 0x2d6443c VA: 0x759537c43c
	public Void RefreshSpecialData() { }
	// RVA: 0x2d63ff4 VA: 0x759537bff4
	private String _CheckRequireViewModels(IList`1 models) { }
	// RVA: 0x2d63c38 VA: 0x759537bc38
	private Void _LoadAllLvlUpData() { }
	// RVA: 0x2d63804 VA: 0x759537b804
	private Void _LoadSpecialLvlUpData() { }
	// RVA: 0x2d644a4 VA: 0x759537c4a4
	private RequireViewModel[] _ParseSkillAllLvlUpRequirements(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x2d64a98 VA: 0x759537ca98
	private RequireViewModel[] _ParseSkillSpecialLvlUpRequirements(PlayerCharacter playerChar, CharacterData charData, Int32 skillIndex) { }
	// RVA: 0x2d64fd0 VA: 0x759537cfd0
	public Void .ctor() { }
}
```