# AutoChessOperationCase

**Namespace:** `Torappu.Battle.GameMode`


## Fields

- `AutoChessDragOperationFlag operationFlag`

- `AutoChessChessTypeBattle startType`

- `AutoChessChessTypeBattle endType`


## Methods

- `Void ApplyFlag(AutoChessDragOperationFlag, Boolean)`

- `Boolean ContainsFlag(AutoChessDragOperationFlag)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.GameMode
public class AutoChessOperationCase
{
	public AutoChessDragOperationFlag operationFlag; // 0x10
	public AutoChessChessTypeBattle startType; // 0x14
	public AutoChessChessTypeBattle endType; // 0x18


	// RVA: 0x1d07d58 VA: 0x759431fd58
	public Void ApplyFlag(AutoChessDragOperationFlag flag, Boolean apply) { }
	// RVA: 0x1d07d74 VA: 0x759431fd74
	public Boolean ContainsFlag(AutoChessDragOperationFlag flag) { }
	// RVA: 0x1d07dcc VA: 0x759431fdcc
	public Void .ctor() { }
}
```