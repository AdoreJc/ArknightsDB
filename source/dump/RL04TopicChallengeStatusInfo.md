# RL04TopicChallengeStatusInfo

**Namespace:** ` `


## Fields

- `String <challengeId>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `PlayerRoguelikeChallengeStatus <status>k__BackingField`


## Properties

- `String challengeId`

- `Int32 sortId`

- `PlayerRoguelikeChallengeStatus status`


## Methods

- `String get_challengeId()`

- `Void set_challengeId(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `PlayerRoguelikeChallengeStatus get_status()`

- `Void set_status(PlayerRoguelikeChallengeStatus)`

- `Void RefreshStatus(PlayerRoguelikeChallengeStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RL04TopicChallengeStatusInfo : IHotfixable
{
	private String <challengeId>k__BackingField; // 0x10
	private Int32 <sortId>k__BackingField; // 0x18
	private PlayerRoguelikeChallengeStatus <status>k__BackingField; // 0x1c
	private static DelegateBridge __Hotfix0_get_challengeId; // 0x0
	private static DelegateBridge __Hotfix0_set_challengeId; // 0x8
	private static DelegateBridge __Hotfix0_get_sortId; // 0x10
	private static DelegateBridge __Hotfix0_set_sortId; // 0x18
	private static DelegateBridge __Hotfix0_get_status; // 0x20
	private static DelegateBridge __Hotfix0_set_status; // 0x28
	private static DelegateBridge __Hotfix0_CreateStatusInfo; // 0x30
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String challengeId { get; set; }
	public Int32 sortId { get; set; }
	public PlayerRoguelikeChallengeStatus status { get; set; }

	// RVA: 0x2b0e3e0 VA: 0x75951263e0
	public String get_challengeId() { }
	// RVA: 0x2b0e448 VA: 0x7595126448
	private Void set_challengeId(String value) { }
	// RVA: 0x2b0e4cc VA: 0x75951264cc
	public Int32 get_sortId() { }
	// RVA: 0x2b0e534 VA: 0x7595126534
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2b0e5b0 VA: 0x75951265b0
	public PlayerRoguelikeChallengeStatus get_status() { }
	// RVA: 0x2b0e618 VA: 0x7595126618
	private Void set_status(PlayerRoguelikeChallengeStatus value) { }
	// RVA: 0x2b0e694 VA: 0x7595126694
	public static RL04TopicChallengeStatusInfo CreateStatusInfo(String challengeId, Int32 sortId) { }
	// RVA: 0x2b0e82c VA: 0x759512682c
	public Void RefreshStatus(PlayerRoguelikeChallengeStatus status) { }
	// RVA: 0x2b0e7bc VA: 0x75951267bc
	public Void .ctor() { }
}
```