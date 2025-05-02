# EnemyDuelRoundEndStandViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String actId`

- `Int32 curRoundIndex`

- `Boolean isProtectedRound`

- `Boolean isLastRound`

- `EnemyDuelRoundEndBarModel barModel`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndStandViewModel : IHotfixable
{
	public String actId; // 0x10
	public Int32 curRoundIndex; // 0x18
	public Boolean isProtectedRound; // 0x1c
	public Boolean isLastRound; // 0x1d
	public readonly List`1 playerDataList; // 0x20
	public EnemyDuelRoundEndBarModel barModel; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x29900cc VA: 0x7594fa80cc
	public Void LoadData() { }
	// RVA: 0x2991108 VA: 0x7594fa9108
	public Void .ctor() { }
}
```