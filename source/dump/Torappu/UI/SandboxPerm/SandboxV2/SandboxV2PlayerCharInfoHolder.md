# SandboxV2PlayerCharInfoHolder

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Methods

- `Void _InitEquipList(PlayerCharacter)`

- `Void _InitSkillList(CharacterData, PlayerCharacter)`

- `PlayerCharSkill _FindPlayerSkill(PlayerCharSkill[], String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2PlayerCharInfoHolder : SandboxV2CharInfoHolder
{
	private static DelegateBridge __Hotfix0_LoadDataImpl; // 0x0
	private static DelegateBridge __Hotfix0__InitEquipList; // 0x8
	private static DelegateBridge __Hotfix0__InitSkillList; // 0x10
	private static DelegateBridge __Hotfix0__FindPlayerSkill; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2607460 VA: 0x7594c1f460
	protected override Void LoadDataImpl() { }
	// RVA: 0x26079ec VA: 0x7594c1f9ec
	private Void _InitEquipList(PlayerCharacter playerChar) { }
	// RVA: 0x260770c VA: 0x7594c1f70c
	private Void _InitSkillList(CharacterData charData, PlayerCharacter playerChar) { }
	// RVA: 0x2607e20 VA: 0x7594c1fe20
	private PlayerCharSkill _FindPlayerSkill(PlayerCharSkill[] playerCharSkills, String skillId) { }
	// RVA: 0x2607f30 VA: 0x7594c1ff30
	public Void .ctor() { }
}
```