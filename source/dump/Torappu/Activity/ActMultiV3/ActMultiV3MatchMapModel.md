# ActMultiV3MatchMapModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String m_actId`

- `String m_stageId`

- `Int64 m_startTime`

- `Int32 <totalStar>k__BackingField`

- `Int32 <currStar>k__BackingField`

- `Int64 <exScore>k__BackingField`


## Properties

- `Int32 totalStar`

- `Int32 currStar`

- `Int64 exScore`

- `String stageId`

- `Int64 startTime`


## Methods

- `Int32 get_totalStar()`

- `Void set_totalStar(Int32)`

- `Int32 get_currStar()`

- `Void set_currStar(Int32)`

- `Int64 get_exScore()`

- `Void set_exScore(Int64)`

- `String get_stageId()`

- `Int64 get_startTime()`

- `Boolean CheckIfOpen(Int64)`

- `Void LoadData(String, ActMultiV3Data, ActMultiV3MapData)`

- `Void UpdatePlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MatchMapModel : IHotfixable
{
	private String m_actId; // 0x10
	private String m_stageId; // 0x18
	private Int64 m_startTime; // 0x20
	private Int32 <totalStar>k__BackingField; // 0x28
	private Int32 <currStar>k__BackingField; // 0x2c
	private Int64 <exScore>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_totalStar; // 0x0
	private static DelegateBridge __Hotfix0_set_totalStar; // 0x8
	private static DelegateBridge __Hotfix0_get_currStar; // 0x10
	private static DelegateBridge __Hotfix0_set_currStar; // 0x18
	private static DelegateBridge __Hotfix0_get_exScore; // 0x20
	private static DelegateBridge __Hotfix0_set_exScore; // 0x28
	private static DelegateBridge __Hotfix0_get_stageId; // 0x30
	private static DelegateBridge __Hotfix0_get_startTime; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfOpen; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Int32 totalStar { get; set; }
	public Int32 currStar { get; set; }
	public Int64 exScore { get; set; }
	public String stageId { get; }
	public Int64 startTime { get; }

	// RVA: 0x3134470 VA: 0x759574c470
	public Int32 get_totalStar() { }
	// RVA: 0x313493c VA: 0x759574c93c
	private Void set_totalStar(Int32 value) { }
	// RVA: 0x31342e4 VA: 0x759574c2e4
	public Int32 get_currStar() { }
	// RVA: 0x31349b8 VA: 0x759574c9b8
	private Void set_currStar(Int32 value) { }
	// RVA: 0x31345f4 VA: 0x759574c5f4
	public Int64 get_exScore() { }
	// RVA: 0x3134a34 VA: 0x759574ca34
	private Void set_exScore(Int64 value) { }
	// RVA: 0x3134ab0 VA: 0x759574cab0
	public String get_stageId() { }
	// RVA: 0x313427c VA: 0x759574c27c
	public Int64 get_startTime() { }
	// RVA: 0x31341f8 VA: 0x759574c1f8
	public Boolean CheckIfOpen(Int64 currTs) { }
	// RVA: 0x3134780 VA: 0x759574c780
	public Void LoadData(String actId, ActMultiV3Data actData, ActMultiV3MapData mapData) { }
	// RVA: 0x3134878 VA: 0x759574c878
	public Void UpdatePlayerData() { }
	// RVA: 0x3134710 VA: 0x759574c710
	public Void .ctor() { }
}
```