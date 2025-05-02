# EnemyDuelPrepareEntranceShowViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String actId`

- `Int32 maxPlayerCnt`

- `EnemyDuelModeType modeType`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareEntranceShowViewModel : IHotfixable
{
	public String actId; // 0x10
	public Int32 maxPlayerCnt; // 0x18
	public EnemyDuelModeType modeType; // 0x1c
	public List`1 playerViewModels; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2995308 VA: 0x7594fad308
	public Void LoadData(String actId) { }
	// RVA: 0x29961ac VA: 0x7594fae1ac
	public Void .ctor() { }
}
```