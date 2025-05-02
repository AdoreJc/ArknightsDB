# EnemyDuelMatchViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Int32 curPlayer`

- `Int32 maxPlayer`

- `Single matchTime`

- `Boolean isMatchSucc`

- `String actId`

- `String modeId`

- `ActivityEnemyDuelConstToastData constToastData`


## Methods

- `Void LoadInitData(String, ActivityEnemyDuelModeData)`

- `Void SyncMatchStatus(EnemyDuelQueryMatchResponse)`

- `Void UpdateMatchTime(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelMatchViewModel : IHotfixable
{
	public Int32 curPlayer; // 0x10
	public Int32 maxPlayer; // 0x14
	public Single matchTime; // 0x18
	public Boolean isMatchSucc; // 0x1c
	public String actId; // 0x20
	public String modeId; // 0x28
	public ActivityEnemyDuelConstToastData constToastData; // 0x30
	private static DelegateBridge __Hotfix0_LoadInitData; // 0x0
	private static DelegateBridge __Hotfix0_SyncMatchStatus; // 0x8
	private static DelegateBridge __Hotfix0_UpdateMatchTime; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2998508 VA: 0x7594fb0508
	public Void LoadInitData(String actId, ActivityEnemyDuelModeData modeData) { }
	// RVA: 0x2997b84 VA: 0x7594fafb84
	public Void SyncMatchStatus(EnemyDuelQueryMatchResponse resp) { }
	// RVA: 0x2997cfc VA: 0x7594fafcfc
	public Void UpdateMatchTime(Single time) { }
	// RVA: 0x2998618 VA: 0x7594fb0618
	public Void .ctor() { }
}
```