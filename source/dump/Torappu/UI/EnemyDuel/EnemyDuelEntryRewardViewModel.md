# EnemyDuelEntryRewardViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Single operationSkipRate`

- `Single operationBetRate`

- `Single operationAllinRate`

- `Single standRate`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryRewardViewModel : IHotfixable
{
	public List`1 basicSore; // 0x10
	public List`1 operationScoreData; // 0x18
	public List`1 standScoreData; // 0x20
	public Single operationSkipRate; // 0x28
	public Single operationBetRate; // 0x2c
	public Single operationAllinRate; // 0x30
	public Single standRate; // 0x34
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x294e9bc VA: 0x7594f669bc
	public Void LoadData(String actId) { }
	// RVA: 0x294ec00 VA: 0x7594f66c00
	public Void .ctor() { }
}
```