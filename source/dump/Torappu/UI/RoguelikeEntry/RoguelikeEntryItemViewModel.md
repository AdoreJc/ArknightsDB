# RoguelikeEntryItemViewModel

**Namespace:** `Torappu.UI.RoguelikeEntry`


## Fields

- `Boolean isEmpty`

- `String topicId`

- `String bpName`

- `Int32 bpLevel`

- `Boolean isBpMax`

- `Boolean isFullStored`

- `Boolean isInDLCAct`

- `Boolean isInReviewAct`

- `Boolean isPinActive`

- `String description`

- `Boolean isOnBattle`

- `Boolean isEntryAccess`

- `String mainMedalId`

- `Boolean isMedalCollected`

- `Boolean showDLCUpdateTag`

- `Boolean showReviewUpdateTag`

- `Int64 startTs`

- `Int32 sortId`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeEntry
public class RoguelikeEntryItemViewModel : IComparable, IHotfixable
{
	public Boolean isEmpty; // 0x10
	public String topicId; // 0x18
	public String bpName; // 0x20
	public Int32 bpLevel; // 0x28
	public Boolean isBpMax; // 0x2c
	public Boolean isFullStored; // 0x2d
	public Boolean isInDLCAct; // 0x2e
	public Boolean isInReviewAct; // 0x2f
	public Boolean isPinActive; // 0x30
	public String description; // 0x38
	public Boolean isOnBattle; // 0x40
	public Boolean isEntryAccess; // 0x41
	public String mainMedalId; // 0x48
	public Boolean isMedalCollected; // 0x50
	public Boolean showDLCUpdateTag; // 0x51
	public Boolean showReviewUpdateTag; // 0x52
	public Int64 startTs; // 0x58
	public Int32 sortId; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge _c__Hotfix1_ctor; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10


	// RVA: 0x2631d70 VA: 0x7594c49d70
	public Void .ctor() { }
	// RVA: 0x2631dec VA: 0x7594c49dec
	public Void .ctor(RoguelikeTopicBasicData basicData, Int64 currTs) { }
	// RVA: 0x2631f84 VA: 0x7594c49f84
	public Int32 CompareTo(Object obj) { }
}
```