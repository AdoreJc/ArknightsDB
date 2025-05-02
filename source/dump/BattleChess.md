# BattleChess

**Namespace:** ` `


## Fields

- `Direction dir`

- `GridPosition pos`

- `Boolean isToken`

- `Int32 buildSeq`


## Methods

- `Int32 CompareTo(BattleChess)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BattleChess : ChessBase, IComparable`1
{
	private const Int32 TOKEN_COMPARE_OFFSET; // 0x0
	public Direction dir; // 0x14
	public GridPosition pos; // 0x18
	public Boolean isToken; // 0x20
	public Int32 buildSeq; // 0x24


	// RVA: 0x1d00f68 VA: 0x7594318f68
	public Int32 CompareTo(BattleChess other) { }
	// RVA: 0x1d00fe8 VA: 0x7594318fe8
	public override String ToString() { }
	// RVA: 0x1cfce48 VA: 0x7594314e48
	public Void .ctor() { }
}
```