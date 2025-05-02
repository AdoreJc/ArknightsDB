# SandboxV2ExpeditionData

**Namespace:** `Torappu`


## Fields

- `String expeditionId`

- `String desc`

- `String effectDesc`

- `Int32 costAction`

- `Int32 costDrink`

- `Int32 charCnt`

- `ProfessionCategory profession`

- `Int32 minEliteRank`

- `Int32 duration`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2ExpeditionData
{
	public String expeditionId; // 0x10
	public String desc; // 0x18
	public String effectDesc; // 0x20
	public Int32 costAction; // 0x28
	public Int32 costDrink; // 0x2c
	public Int32 charCnt; // 0x30
	public ProfessionCategory profession; // 0x34
	public List`1 professions; // 0x38
	public Int32 minEliteRank; // 0x40
	public Int32 duration; // 0x44


	// RVA: 0x34f2104 VA: 0x7595b0a104
	public Void .ctor() { }
}
```