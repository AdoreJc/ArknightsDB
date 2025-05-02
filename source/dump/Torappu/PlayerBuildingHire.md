# PlayerBuildingHire

**Namespace:** `Torappu`


## Fields

- `PlayerBuildingHireBuff buff`

- `Int32 recruitSlotId`

- `PlayerBuildingHiringState state`

- `Double processPoint`

- `Single speed`

- `DateTime lastUpdateTime`

- `Int32 refreshCount`

- `DateTime completeWorkTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerBuildingHire
{
	public PlayerBuildingHireBuff buff; // 0x10
	public Int32 recruitSlotId; // 0x18
	public PlayerBuildingHiringState state; // 0x1c
	public Double processPoint; // 0x20
	public Single speed; // 0x28
	public DateTime lastUpdateTime; // 0x30
	public Int32 refreshCount; // 0x38
	public DateTime completeWorkTime; // 0x40
	public List`1 presetQueue; // 0x48


	// RVA: 0x32d721c VA: 0x75958ef21c
	public Void .ctor() { }
}
```