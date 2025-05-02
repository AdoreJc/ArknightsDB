# ClimbTowerEntryMissionViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String seasonId`

- `Int32 missionReceived`

- `Int32 missionCount`

- `Int32 seasonOrderNum`

- `String seasonName`

- `Int32 periodCurr`

- `Int32 periodCount`

- `Int64 endTs`

- `String remainTimeDesc`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryMissionViewModel : IHotfixable
{
	public String seasonId; // 0x10
	public List`1 itemModelList; // 0x18
	public Dictionary`2 itemModelMap; // 0x20
	public Int32 missionReceived; // 0x28
	public Int32 missionCount; // 0x2c
	public Int32 seasonOrderNum; // 0x30
	public String seasonName; // 0x38
	public Int32 periodCurr; // 0x40
	public Int32 periodCount; // 0x44
	public Int64 endTs; // 0x48
	public String remainTimeDesc; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2cd7c90 VA: 0x75952efc90
	public Void LoadData() { }
	// RVA: 0x2cd844c VA: 0x75952f044c
	public Void .ctor() { }
}
```