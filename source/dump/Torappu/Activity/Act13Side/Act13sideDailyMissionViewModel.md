# Act13sideDailyMissionViewModel

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `PlayerAct13sideActivity m_playerData`


## Properties

- `Int32 agenda`


## Methods

- `Int32 get_agenda()`

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionViewModel : IHotfixable
{
	private PlayerAct13sideActivity m_playerData; // 0x10
	public List`1 missionItemList; // 0x18
	private static DelegateBridge __Hotfix0_get_agenda; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Int32 agenda { get; }

	// RVA: 0x343840c VA: 0x7595a5040c
	public Int32 get_agenda() { }
	// RVA: 0x3438484 VA: 0x7595a50484
	public Void LoadData(String actId) { }
	// RVA: 0x343872c VA: 0x7595a5072c
	public Void .ctor() { }
}
```