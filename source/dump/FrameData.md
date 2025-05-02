# FrameData

**Namespace:** ` `


## Methods

- `Void AppendWithdraw(Signiture, GridPosition, PlayerSide)`

- `Void AppendSpawn(Signiture, Direction, GridPosition, PlayerSide)`

- `Void AppendSkill(Signiture, GridPosition, PlayerSide)`

- `Void AppendCheat(Signiture, PlayerSide)`

- `Void Reset()`

- `Void DumpToPlayerOpQueue(PlayerOperationQueue)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FrameData
{
	public Queue`1 opQueue; // 0x10


	// RVA: 0x3f6cb7c VA: 0x7596584b7c
	public Void AppendWithdraw(Signiture sig, GridPosition pos, PlayerSide side) { }
	// RVA: 0x3f6cc50 VA: 0x7596584c50
	public Void AppendSpawn(Signiture sig, Direction direction, GridPosition pos, PlayerSide side) { }
	// RVA: 0x3f6cd24 VA: 0x7596584d24
	public Void AppendSkill(Signiture sig, GridPosition pos, PlayerSide side) { }
	// RVA: 0x3f6cdf8 VA: 0x7596584df8
	public Void AppendCheat(Signiture sig, PlayerSide side) { }
	// RVA: 0x3f6cebc VA: 0x7596584ebc
	public Void Reset() { }
	// RVA: 0x3f6cf0c VA: 0x7596584f0c
	public Void DumpToPlayerOpQueue(PlayerOperationQueue target) { }
	// RVA: 0x3f6d0a8 VA: 0x75965850a8
	public Void .ctor() { }
}
```