# Act38sideEntryFireworkPuzzleViewModel

**Namespace:** `Torappu.Activity.Act38side`


## Fields

- `String actId`

- `Status status`

- `Boolean hasDailyTrack`

- `String unlockDesc`

- `String closeDesc`

- `String lockedToastText`

- `String closedToastText`

- `String puzzleCrossDayTrackId`


## Methods

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act38side
public class Act38sideEntryFireworkPuzzleViewModel : TemplateActivityViewModel, IHotfixable
{
	public String actId; // 0x20
	public Status status; // 0x28
	public Boolean hasDailyTrack; // 0x2c
	public String unlockDesc; // 0x30
	public String closeDesc; // 0x38
	public String lockedToastText; // 0x40
	public String closedToastText; // 0x48
	public String puzzleCrossDayTrackId; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8


	// RVA: 0x323d3cc VA: 0x75958553cc
	public Void .ctor(Object param) { }
	// RVA: 0x323d5b8 VA: 0x75958555b8
	public Void RefreshPlayerData() { }
}
```