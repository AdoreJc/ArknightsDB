# EnemyDuelPrepareSelectModeCardViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Int32 seqNum`

- `String actId`

- `Int32 sortedIdx`

- `Boolean isLock`

- `Boolean isRoom`

- `ActivityEnemyDuelModeData modeData`

- `ModeInfo playerModeData`

- `String lockText`

- `String lockToast`


## Methods

- `Int32 CompareTo(EnemyDuelPrepareSelectModeCardViewModel)`

- `Void RefreshData(EnemyDuelPrepareSelectModeViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareSelectModeCardViewModel : IComparable`1
{
	public Int32 seqNum; // 0x10
	public String actId; // 0x18
	public Int32 sortedIdx; // 0x20
	public Boolean isLock; // 0x24
	public Boolean isRoom; // 0x25
	public ActivityEnemyDuelModeData modeData; // 0x28
	public ModeInfo playerModeData; // 0x30
	public String lockText; // 0x38
	public String lockToast; // 0x40


	// RVA: 0x29a0a30 VA: 0x7594fb8a30
	public Int32 CompareTo(EnemyDuelPrepareSelectModeCardViewModel other) { }
	// RVA: 0x29a0770 VA: 0x7594fb8770
	public Void RefreshData(EnemyDuelPrepareSelectModeViewModel mainViewModel) { }
	// RVA: 0x29a0768 VA: 0x7594fb8768
	public Void .ctor() { }
}
```