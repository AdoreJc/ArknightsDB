# ClimbTowerEntryFloatPanelViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String seasonId`

- `Int64 endTs`

- `String remainTimeDesc`

- `Int32 periodCurr`

- `Int32 periodCount`

- `Int32 seasonNum`

- `String seasonName`

- `Int32 missionSum`

- `Int32 missionComplete`

- `Boolean showMissionTrackPoint`

- `Boolean isMissionAndGodCardBanned`

- `Boolean isGodCardTabClose`


## Methods

- `Void LoadData()`

- `Void SetGodCardTabClosedStatusNot()`

- `Void _LoadSeasonGodCardData()`

- `Void _LoadTowerGodCardData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryFloatPanelViewModel : IHotfixable
{
	public String seasonId; // 0x10
	public Int64 endTs; // 0x18
	public String remainTimeDesc; // 0x20
	public Int32 periodCurr; // 0x28
	public Int32 periodCount; // 0x2c
	public Int32 seasonNum; // 0x30
	public String seasonName; // 0x38
	public Int32 missionSum; // 0x40
	public Int32 missionComplete; // 0x44
	public Boolean showMissionTrackPoint; // 0x48
	public Boolean isMissionAndGodCardBanned; // 0x49
	public List`1 godCardList; // 0x50
	public Boolean isGodCardTabClose; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetGodCardTabClosedStatusNot; // 0x8
	private static DelegateBridge __Hotfix0__LoadSeasonGodCardData; // 0x10
	private static DelegateBridge __Hotfix0__LoadTowerGodCardData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2cd5118 VA: 0x75952ed118
	public Void LoadData() { }
	// RVA: 0x2cd5928 VA: 0x75952ed928
	public Void SetGodCardTabClosedStatusNot() { }
	// RVA: 0x2cd5518 VA: 0x75952ed518
	private Void _LoadSeasonGodCardData() { }
	// RVA: 0x2cd56f0 VA: 0x75952ed6f0
	private Void _LoadTowerGodCardData() { }
	// RVA: 0x2cd6154 VA: 0x75952ee154
	public Void .ctor() { }
}
```