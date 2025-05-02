# EnemyDuelPrepareSelectModeViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Int32 seqNum`

- `String actId`

- `Boolean isRoom`

- `ActivityEnemyDuelData actData`

- `PlayerEnemyDuelActivity playerActData`

- `Single picRotateTime`

- `EnemyDuelPrepareSelectModeSelectionViewModel selectionViewModel`


## Methods

- `Void LoadData(String, Boolean, String)`

- `Void SelectMode(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareSelectModeViewModel : IHotfixable
{
	public Int32 seqNum; // 0x10
	public String actId; // 0x18
	public Boolean isRoom; // 0x20
	public ActivityEnemyDuelData actData; // 0x28
	public PlayerEnemyDuelActivity playerActData; // 0x30
	public Single picRotateTime; // 0x38
	public EnemyDuelPrepareSelectModeSelectionViewModel selectionViewModel; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SelectMode; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x299fe84 VA: 0x7594fb7e84
	public Void LoadData(String actId, Boolean isRoom, String selectModeId) { }
	// RVA: 0x29a04a4 VA: 0x7594fb84a4
	public Void SelectMode(Int32 idx) { }
	// RVA: 0x29a05a0 VA: 0x7594fb85a0
	public Void .ctor() { }
}
```