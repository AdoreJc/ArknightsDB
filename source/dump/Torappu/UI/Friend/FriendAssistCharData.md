# FriendAssistCharData

**Namespace:** `Torappu.UI.Friend`


## Fields

- `CharacterCardViewModel m_charCard`

- `Boolean m_isAllSpecMax`

- `Int32 m_mainSkillLvl`

- `Int32 m_skillIndex`

- `String m_equipId`


## Properties

- `CharacterCardViewModel charCard`

- `Int32 skillIndex`

- `String equipId`

- `Int32 mainSkillLvl`

- `Boolean isAllSpecMax`


## Methods

- `CharacterCardViewModel get_charCard()`

- `Int32 get_skillIndex()`

- `String get_equipId()`

- `Int32 get_mainSkillLvl()`

- `Boolean get_isAllSpecMax()`

- `Void LoadData(CharacterCardViewModel, Int32, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendAssistCharData
{
	private CharacterCardViewModel m_charCard; // 0x10
	private List`1 m_charEquipInfos; // 0x18
	private PlayerCharSkill[] m_charSkills; // 0x20
	private Boolean m_isAllSpecMax; // 0x28
	private Int32 m_mainSkillLvl; // 0x2c
	private Int32 m_skillIndex; // 0x30
	private String m_equipId; // 0x38

	public List`1 charEquipInfos { get; }
	public CharacterCardViewModel charCard { get; }
	public Int32 skillIndex { get; }
	public String equipId { get; }
	public PlayerCharSkill[] charSkills { get; }
	public Int32 mainSkillLvl { get; }
	public Boolean isAllSpecMax { get; }

	// RVA: 0x28be080 VA: 0x7594ed6080
	public List`1 get_charEquipInfos() { }
	// RVA: 0x28be088 VA: 0x7594ed6088
	public CharacterCardViewModel get_charCard() { }
	// RVA: 0x28be090 VA: 0x7594ed6090
	public Int32 get_skillIndex() { }
	// RVA: 0x28be098 VA: 0x7594ed6098
	public String get_equipId() { }
	// RVA: 0x28be0a0 VA: 0x7594ed60a0
	public PlayerCharSkill[] get_charSkills() { }
	// RVA: 0x28be0a8 VA: 0x7594ed60a8
	public Int32 get_mainSkillLvl() { }
	// RVA: 0x28be0b0 VA: 0x7594ed60b0
	public Boolean get_isAllSpecMax() { }
	// RVA: 0x28bd90c VA: 0x7594ed590c
	public Void LoadData(CharacterCardViewModel characterCard, Int32 skillIndex, String equipId) { }
	// RVA: 0x28bd8fc VA: 0x7594ed58fc
	public Void .ctor() { }
}
```