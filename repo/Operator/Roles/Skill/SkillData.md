# SkillData 技能数据
## key
## sortID
## name
## info
## animationKey
## maxLvl
## lvlInfo
## lvlBuffData
## childSkillId
## preSkillId
## scale
## elementInfo
## actualSkillId

```C#
// Namespace: Torappu.DB.Test
[Serializable]
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
}
```