# SkillDataBundle

**Namespace:** `Torappu`


## Fields

- `String skillId`

- `String iconId`

- `Boolean hidden`


## Methods

- `Boolean TryGetSkill(Int32, String, out)`

- `Boolean _TryGetInternal(Int32, out)`

- `String GetSkillId()`

- `String GetIconId()`

- `String _GetPrefabKey(LevelData, String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SkillDataBundle : ISkillData
{
	public String skillId; // 0x10
	public String iconId; // 0x18
	public Boolean hidden; // 0x20
	public List`1 levels; // 0x28


	// RVA: 0x34f58b0 VA: 0x7595b0d8b0
	public Boolean TryGetSkill(Int32 skillLevel, String overridePrefabKey, out SkillData data) { }
	// RVA: 0x34f5abc VA: 0x7595b0dabc
	private Boolean _TryGetInternal(Int32 skillLevel, out LevelData data) { }
	// RVA: 0x34f5bd8 VA: 0x7595b0dbd8
	public String GetSkillId() { }
	// RVA: 0x34f5be0 VA: 0x7595b0dbe0
	public String GetIconId() { }
	// RVA: 0x34f5b88 VA: 0x7595b0db88
	private String _GetPrefabKey(LevelData level, String overridePrefabKey, out Boolean isPrefabKeyOverrideen) { }
	// RVA: 0x34f5be8 VA: 0x7595b0dbe8
	public Void .ctor() { }
}
```