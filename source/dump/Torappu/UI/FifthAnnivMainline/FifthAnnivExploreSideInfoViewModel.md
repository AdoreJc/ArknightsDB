# FifthAnnivExploreSideInfoViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `String currentGroupName`

- `String currentGroupCode`

- `String currentGroupDesc`

- `Boolean hasPrevValue`

- `Boolean isNextCheckpoint`

- `Boolean isNextCheckpointFulfill`

- `FifthAnnivExploreValueGroupViewModel valueGroupViewModel`

- `String currentGroupIconId`


## Methods

- `Void LoadData()`

- `Void LoadData(FifthAnnivExploreData, PlayerMainlineExplore)`

- `Boolean _IsNextCheckpoint(PlayerMainlineExplore)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreSideInfoViewModel : IHotfixable
{
	public String currentGroupName; // 0x10
	public String currentGroupCode; // 0x18
	public String currentGroupDesc; // 0x20
	public Dictionary`2 previousAbilityValues; // 0x28
	public Dictionary`2 currentAbilityValues; // 0x30
	public Boolean hasPrevValue; // 0x38
	public Boolean isNextCheckpoint; // 0x39
	public Boolean isNextCheckpointFulfill; // 0x3a
	public FifthAnnivExploreValueGroupViewModel valueGroupViewModel; // 0x40
	public String currentGroupIconId; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix1_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__IsNextCheckpoint; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x292f3e8 VA: 0x7594f473e8
	public Void LoadData() { }
	// RVA: 0x292a6bc VA: 0x7594f426bc
	public Void LoadData(FifthAnnivExploreData exploreData, PlayerMainlineExplore playerExplore) { }
	// RVA: 0x292f4c8 VA: 0x7594f474c8
	private Boolean _IsNextCheckpoint(PlayerMainlineExplore playerExplore) { }
	// RVA: 0x292abfc VA: 0x7594f42bfc
	public Void .ctor() { }
}
```