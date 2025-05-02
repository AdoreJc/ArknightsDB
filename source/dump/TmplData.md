# TmplData

**Namespace:** ` `


## Fields

- `Int32 skillIndex`

- `String skinId`

- `String selectEquip`

- `Int32 overrideSkillIndex`

- `String overrideEquipId`


## Methods

- `Int32 TryGetOverrideSkillIndex(Boolean)`

- `String TryGetOverrideEquipId(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TmplData
{
	public Int32 skillIndex; // 0x10
	public String skinId; // 0x18
	public SharedCharSkillData[] skills; // 0x20
	public String selectEquip; // 0x28
	public ListDict`2 equips; // 0x30
	public Int32 overrideSkillIndex; // 0x38
	public String overrideEquipId; // 0x40


	// RVA: 0x34a15e0 VA: 0x7595ab95e0
	public Int32 TryGetOverrideSkillIndex(Boolean forceFriendSet) { }
	// RVA: 0x34a1a7c VA: 0x7595ab9a7c
	public String TryGetOverrideEquipId(Boolean forceFriendSet) { }
	// RVA: 0x34a2088 VA: 0x7595aba088
	public Void .ctor() { }
}
```