# SkillDB

**Namespace:** `Torappu`


## Methods

- `SkillData GetSkillOrDefault(String, Int32)`

- `Boolean TryGetSkill(MainSkill, Int32, out)`

- `Boolean TryGetSkill(String, Int32, out)`

- `Boolean _TryGetSkill(String, Int32, String, out)`

- `Boolean TryGetSkillBundle(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SkillDB : SimpleKVTable`2
{
	private static DelegateBridge __Hotfix0_GetSkillOrDefault; // 0x0
	private static DelegateBridge __Hotfix0_TryGetSkill; // 0x8
	private static DelegateBridge __Hotfix1_TryGetSkill; // 0x10
	private static DelegateBridge __Hotfix0__TryGetSkill; // 0x18
	private static DelegateBridge __Hotfix0_TryGetSkillBundle; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x31f75d4 VA: 0x759580f5d4
	public SkillData GetSkillOrDefault(String key, Int32 lvl) { }
	// RVA: 0x31f7720 VA: 0x759580f720
	public Boolean TryGetSkill(MainSkill mainSkill, Int32 lvl, out SkillData skillData) { }
	// RVA: 0x31f7678 VA: 0x759580f678
	public Boolean TryGetSkill(String key, Int32 lvl, out SkillData skillData) { }
	// RVA: 0x31f77cc VA: 0x759580f7cc
	private Boolean _TryGetSkill(String key, Int32 lvl, String overridePrefabKey, out SkillData skillData) { }
	// RVA: 0x31f78c4 VA: 0x759580f8c4
	public Boolean TryGetSkillBundle(String key, out SkillDataBundle skillBundle) { }
	// RVA: 0x31f795c VA: 0x759580f95c
	public Void .ctor() { }
}
```