# RiftInfo

**Namespace:** ` `


## Fields

- `Boolean isUnlocked`

- `Int32 randomRemain`

- `Int32 teamLv`

- `Reservation reservation`

- `GameInfo gameInfo`

- `SettleInfo settleInfo`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RiftInfo
{
	public Boolean isUnlocked; // 0x10
	public Int32 randomRemain; // 0x14
	public Dictionary`2 reservedRifts; // 0x18
	public Dictionary`2 completedDifficultyLevel; // 0x20
	public Int32 teamLv; // 0x28
	public List`1 fixFinish; // 0x30
	public Reservation reservation; // 0x38
	public GameInfo gameInfo; // 0x40
	public SettleInfo settleInfo; // 0x48


	// RVA: 0x33af1ac VA: 0x75959c71ac
	public Void .ctor() { }
}
```