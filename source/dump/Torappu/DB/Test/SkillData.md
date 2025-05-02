# SkillData

**Namespace:** `Torappu.DB.Test`


## Fields

- `String key`

- `Int32 sortID`

- `String name`

- `String info`

- `String animationKey`

- `Int32 maxLvl`

- `String childSkillId`

- `String preSkillId`

- `Single scale`

- `ElementInfo elementInfo`

- `String actualSkillId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB.Test
public class SkillData
{
	public String key; // 0x10
	public Int32 sortID; // 0x18
	public String name; // 0x20
	public String info; // 0x28
	public String animationKey; // 0x30
	public Int32 maxLvl; // 0x38
	public Dictionary`2 lvlInfo; // 0x40
	public Dictionary`2 lvlBuffData; // 0x48
	public String childSkillId; // 0x50
	public String preSkillId; // 0x58
	public Single scale; // 0x60
	public ElementInfo elementInfo; // 0x68
	public String actualSkillId; // 0x70


	// RVA: 0x371f2d4 VA: 0x7595d372d4
	public Void .ctor() { }
}
```