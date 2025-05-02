# PermModeZoneGroupViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String currRogueTopicId`

- `Boolean isOnBattle`

- `String onBattleTopicId`

- `String onBattleTopicName`

- `Boolean showRoguelikeDLCUpdateTag`

- `Boolean showRoguelikeReviewUpdateTag`

- `String currSandboxTopicId`

- `Boolean showSandboxUpdateTag`

- `Boolean isSandboxClosed`


## Methods

- `Void LoadData()`

- `Void RefreshPlayerData()`

- `Void _LoadRogueData(Int64)`

- `Void _LoadSandboxData(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class PermModeZoneGroupViewModel : ZoneGroupViewModel, IHotfixable
{
	public String currRogueTopicId; // 0x28
	public Boolean isOnBattle; // 0x30
	public String onBattleTopicId; // 0x38
	public String onBattleTopicName; // 0x40
	public Boolean showRoguelikeDLCUpdateTag; // 0x48
	public Boolean showRoguelikeReviewUpdateTag; // 0x49
	public String currSandboxTopicId; // 0x50
	public Boolean showSandboxUpdateTag; // 0x58
	public Boolean isSandboxClosed; // 0x59
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge __Hotfix0__LoadRogueData; // 0x10
	private static DelegateBridge __Hotfix0__LoadSandboxData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f12c0c VA: 0x759552ac0c
	public Void LoadData() { }
	// RVA: 0x2f12c7c VA: 0x759552ac7c
	public Void RefreshPlayerData() { }
	// RVA: 0x2f12d24 VA: 0x759552ad24
	private Void _LoadRogueData(Int64 currTs) { }
	// RVA: 0x2f12f54 VA: 0x759552af54
	private Void _LoadSandboxData(Int64 currTs) { }
	// RVA: 0x2f13088 VA: 0x759552b088
	public Void .ctor() { }
}
```