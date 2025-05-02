# PlayerCharacter

**Namespace:** `Torappu`


## Fields

- `Int32 instId`

- `String charId`

- `Int32 level`

- `Int32 exp`

- `EvolvePhase evolvePhase`

- `Int32 potentialRank`

- `Int32 favorPoint`

- `Int32 mainSkillLvl`

- `Int64 gainTime`

- `CharStarMarkState starMark`

- `String currentTmpl`

- `Int32 m_defaultSkillIndex`

- `String m_skinId`

- `String m_selectEquip`

- `VoiceLangType m_voiceLan`


## Methods

- `Int32 GetFinalSkillLvl(String, Int32)`

- `Int32 GetEquipLvl(String, String)`

- `PlayerCharPatch SafeTmpl(String)`

- `Int32 GetDefaultSkillIndex()`

- `String GetSkinId(String)`

- `String GetEquipId(String)`

- `Int32 GetCurEquipLevel(String)`

- `VoiceLangType GetVoiceLan(String)`

- `Boolean IsTmplUnlocked(String)`

- `Boolean HasMultiTmpls()`

- `PlayerCharacter ShallowClone()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerCharacter : IHotfixable
{
	public Int32 instId; // 0x10
	public String charId; // 0x18
	public Int32 level; // 0x20
	public Int32 exp; // 0x24
	public EvolvePhase evolvePhase; // 0x28
	public Int32 potentialRank; // 0x2c
	public Int32 favorPoint; // 0x30
	public Int32 mainSkillLvl; // 0x34
	public Int64 gainTime; // 0x38
	public CharStarMarkState starMark; // 0x40
	public String currentTmpl; // 0x48
	public ListDict`2 tmpl; // 0x50
	private PlayerCharSkill[] m_skills; // 0x58
	private Int32 m_defaultSkillIndex; // 0x60
	private String m_skinId; // 0x68
	private String m_selectEquip; // 0x70
	private ListDict`2 m_equips; // 0x78
	private VoiceLangType m_voiceLan; // 0x80
	private static DelegateBridge __Hotfix0_GetFinalSkillLvl; // 0x0
	private static DelegateBridge __Hotfix0_GetEquipLvl; // 0x8
	private static DelegateBridge __Hotfix0_SafeTmpl; // 0x10
	private static DelegateBridge __Hotfix0_GetCurSkills; // 0x18
	private static DelegateBridge __Hotfix0_GetSkills; // 0x20
	private static DelegateBridge __Hotfix0_GetDefaultSkillIndex; // 0x28
	private static DelegateBridge __Hotfix0_GetSkinId; // 0x30
	private static DelegateBridge __Hotfix0_GetEquips; // 0x38
	private static DelegateBridge __Hotfix0_GetEquipId; // 0x40
	private static DelegateBridge __Hotfix0_GetCurEquipLevel; // 0x48
	private static DelegateBridge __Hotfix0_GetVoiceLan; // 0x50
	private static DelegateBridge __Hotfix0_IsTmplUnlocked; // 0x58
	private static DelegateBridge __Hotfix0_HasMultiTmpls; // 0x60
	private static DelegateBridge __Hotfix0_ShallowClone; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x32ceebc VA: 0x75958e6ebc
	public Int32 GetFinalSkillLvl(String tmplId, Int32 skillIndex) { }
	// RVA: 0x32cf04c VA: 0x75958e704c
	public Int32 GetEquipLvl(String equipId, String tmplId) { }
	// RVA: 0x32cf1e8 VA: 0x75958e71e8
	public PlayerCharPatch SafeTmpl(String tmplId) { }
	// RVA: 0x32cf294 VA: 0x75958e7294
	public PlayerCharSkill[] GetCurSkills() { }
	// RVA: 0x32cef8c VA: 0x75958e6f8c
	public PlayerCharSkill[] GetSkills(String tmplId) { }
	// RVA: 0x32cf300 VA: 0x75958e7300
	public Int32 GetDefaultSkillIndex() { }
	// RVA: 0x32cf3ac VA: 0x75958e73ac
	public String GetSkinId(String tmplId) { }
	// RVA: 0x32cf120 VA: 0x75958e7120
	public ListDict`2 GetEquips(String tmplId) { }
	// RVA: 0x32cf474 VA: 0x75958e7474
	public String GetEquipId(String tmplId) { }
	// RVA: 0x32cf53c VA: 0x75958e753c
	public Int32 GetCurEquipLevel(String tmplId) { }
	// RVA: 0x32cf654 VA: 0x75958e7654
	public VoiceLangType GetVoiceLan(String tmplId) { }
	// RVA: 0x32cf6d0 VA: 0x75958e76d0
	public Boolean IsTmplUnlocked(String tmplId) { }
	// RVA: 0x32cf77c VA: 0x75958e777c
	public Boolean HasMultiTmpls() { }
	// RVA: 0x32cf808 VA: 0x75958e7808
	public PlayerCharacter ShallowClone() { }
	// RVA: 0x32cf8b0 VA: 0x75958e78b0
	public Void .ctor() { }
}
```