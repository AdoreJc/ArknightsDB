# FireworkPuzzleItemModel

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `Int64 startTime`

- `String puzzleId`

- `String puzzleGroupId`

- `PuzzleStatus status`

- `Boolean willUnlockInOneDay`

- `String unlockRemainTimeStr`


## Methods

- `Int32 CompareTo(FireworkPuzzleItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleItemModel : IHotfixable, IComparable`1
{
	public Int64 startTime; // 0x10
	public String puzzleId; // 0x18
	public String puzzleGroupId; // 0x20
	public PuzzleStatus status; // 0x28
	public Boolean willUnlockInOneDay; // 0x2c
	public String unlockRemainTimeStr; // 0x30
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x28f5c20 VA: 0x7594f0dc20
	public Int32 CompareTo(FireworkPuzzleItemModel other) { }
	// RVA: 0x28f5cd4 VA: 0x7594f0dcd4
	public Void .ctor() { }
}
```