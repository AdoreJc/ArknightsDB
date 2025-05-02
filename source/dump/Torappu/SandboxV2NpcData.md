# SandboxV2NpcData

**Namespace:** `Torappu`


## Fields

- `String npcId`

- `String trapId`

- `SandboxV2NpcType npcType`

- `Direction npcOrientation`

- `String picId`

- `String picName`

- `Boolean showPic`

- `Int32 reactSkillIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2NpcData
{
	public String npcId; // 0x10
	public String trapId; // 0x18
	public SandboxV2NpcType npcType; // 0x20
	public Dictionary`2 dialogIds; // 0x28
	public List`1 npcLocation; // 0x30
	public Direction npcOrientation; // 0x38
	public String picId; // 0x40
	public String picName; // 0x48
	public Boolean showPic; // 0x50
	public Int32 reactSkillIndex; // 0x54


	// RVA: 0x34f20b4 VA: 0x7595b0a0b4
	public Void .ctor() { }
}
```