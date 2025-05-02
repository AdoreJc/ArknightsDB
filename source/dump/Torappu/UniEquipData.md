# UniEquipData

**Namespace:** `Torappu`


## Fields

- `String uniEquipId`

- `String uniEquipName`

- `String uniEquipIcon`

- `String uniEquipDesc`

- `String typeIcon`

- `String typeName1`

- `String typeName2`

- `String equipShiningColor`

- `EvolvePhase showEvolvePhase`

- `EvolvePhase unlockEvolvePhase`

- `String charId`

- `String tmplId`

- `Int32 showLevel`

- `Int32 unlockLevel`

- `UniEquipType type`

- `Int64 uniEquipGetTime`

- `Int64 uniEquipShowEnd`

- `Int32 charEquipOrder`

- `Boolean hasUnlockMission`

- `Boolean isSpecialEquip`

- `String specialEquipDesc`

- `String specialEquipColor`

- `String charColor`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class UniEquipData
{
	public String uniEquipId; // 0x10
	public String uniEquipName; // 0x18
	public String uniEquipIcon; // 0x20
	public String uniEquipDesc; // 0x28
	public String typeIcon; // 0x30
	public String typeName1; // 0x38
	public String typeName2; // 0x40
	public String equipShiningColor; // 0x48
	public EvolvePhase showEvolvePhase; // 0x50
	public EvolvePhase unlockEvolvePhase; // 0x54
	public String charId; // 0x58
	public String tmplId; // 0x60
	public Int32 showLevel; // 0x68
	public Int32 unlockLevel; // 0x6c
	public List`1 missionList; // 0x70
	public Dictionary`2 unlockFavors; // 0x78
	public Dictionary`2 itemCost; // 0x80
	public UniEquipType type; // 0x88
	public Int64 uniEquipGetTime; // 0x90
	public Int64 uniEquipShowEnd; // 0x98
	public Int32 charEquipOrder; // 0xa0
	public Boolean hasUnlockMission; // 0xa4
	public Boolean isSpecialEquip; // 0xa5
	public String specialEquipDesc; // 0xa8
	public String specialEquipColor; // 0xb0
	public String charColor; // 0xb8


	// RVA: 0x34f8d40 VA: 0x7595b10d40
	public virtual Boolean ShouldSerializespecialEquipDesc() { }
	// RVA: 0x34f8d48 VA: 0x7595b10d48
	public virtual Boolean ShouldSerializespecialEquipColor() { }
	// RVA: 0x34f8d50 VA: 0x7595b10d50
	public Void .ctor() { }
}
```