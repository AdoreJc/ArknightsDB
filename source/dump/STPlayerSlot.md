# STPlayerSlot

**Namespace:** ` `


## Fields

- `Int32 instId`

- `Int32 charInstId`

- `String charId`

- `Int32 level`

- `Int32 phase`

- `Int32 favorPoint`

- `Int32 potentialRank`

- `Int32 skillIndex`

- `Int32 skillLevel`

- `Int32 specSkillLevel`

- `String skinID`

- `String equipID`

- `Int32 equipLevel`

- `String implId`


## Methods

- `Void Read(IStreamReader)`

- `Void Write(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class STPlayerSlot : IStreamDeserialize, IStreamSerialize
{
	public Int32 instId; // 0x10
	public Int32 charInstId; // 0x14
	public String charId; // 0x18
	public Int32 level; // 0x20
	public Int32 phase; // 0x24
	public Int32 favorPoint; // 0x28
	public Int32 potentialRank; // 0x2c
	public Int32 skillIndex; // 0x30
	public Int32 skillLevel; // 0x34
	public Int32 specSkillLevel; // 0x38
	public String skinID; // 0x40
	public String equipID; // 0x48
	public Int32 equipLevel; // 0x50
	public String implId; // 0x58


	// RVA: 0x35a168c VA: 0x7595bb968c
	public Void Read(IStreamReader from) { }
	// RVA: 0x35a1c44 VA: 0x7595bb9c44
	public Void Write(IStreamWriter to) { }
	// RVA: 0x35a20e0 VA: 0x7595bba0e0
	public Void .ctor() { }
}
```