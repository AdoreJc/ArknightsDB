# STBasicChar

**Namespace:** ` `


## Fields

- `Int32 instId`

- `Int32 charInstID`

- `String charID`

- `Int32 level`

- `EvolvePhase evolvePhase`

- `Int32 favorPoint`

- `Int32 potentialRank`

- `String currentTmpl`

- `Int32 mainSkillLvl`

- `Int32 defaultSkillIndex`

- `String currentEquip`

- `String skin`


## Methods

- `Void Read(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class STBasicChar : IStreamDeserialize
{
	public Int32 instId; // 0x10
	public Int32 charInstID; // 0x14
	public String charID; // 0x18
	public Int32 level; // 0x20
	public EvolvePhase evolvePhase; // 0x24
	public Int32 favorPoint; // 0x28
	public Int32 potentialRank; // 0x2c
	public String currentTmpl; // 0x30
	public Int32 mainSkillLvl; // 0x38
	public List`1 skills; // 0x40
	public Int32 defaultSkillIndex; // 0x48
	public String currentEquip; // 0x50
	public ListDict`2 equip; // 0x58
	public String skin; // 0x60


	// RVA: 0x35a0594 VA: 0x7595bb8594
	public Void Read(IStreamReader from) { }
	// RVA: 0x35a0b08 VA: 0x7595bb8b08
	public Void .ctor() { }
}
```