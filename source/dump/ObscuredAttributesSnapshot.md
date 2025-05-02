# ObscuredAttributesSnapshot

**Namespace:** ` `


## Fields

- `ObscuredInt maxHp`

- `ObscuredInt atk`

- `ObscuredInt def`

- `ObscuredFP magicResistance`

- `ObscuredInt cost`

- `ObscuredInt blockCnt`

- `ObscuredInt respawnTime`

- `ObscuredInt maxDeployCount`

- `ObscuredInt maxDeckStackCnt`


## Methods

- `Void CopyFrom(Attributes, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ObscuredAttributesSnapshot
{
	public ObscuredInt maxHp; // 0x10
	public ObscuredInt atk; // 0x24
	public ObscuredInt def; // 0x38
	public ObscuredFP magicResistance; // 0x50
	public ObscuredInt cost; // 0x78
	public ObscuredInt blockCnt; // 0x8c
	public ObscuredInt respawnTime; // 0xa0
	public ObscuredInt maxDeployCount; // 0xb4
	public ObscuredInt maxDeckStackCnt; // 0xc8
	public ObscuredFP[] cardAttributeSnapshot; // 0xe0


	// RVA: 0x3fb382c VA: 0x75965cb82c
	public Void .ctor(Attributes attributes) { }
	// RVA: 0x3fb38ac VA: 0x75965cb8ac
	public Void CopyFrom(Attributes attributes, Boolean exceptCost) { }
}
```