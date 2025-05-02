# RL02TopicChallengeStatusInfo

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
private class RL02TopicChallengeStatusInfo : IHotfixable
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

	// RVA: 0x2b5bac8 VA: 0x7595173ac8
	public String get_challengeId() { }
	// RVA: 0x2b5bb30 VA: 0x7595173b30
	private Void set_challengeId(String value) { }
	// RVA: 0x2b5bbb4 VA: 0x7595173bb4
	public Int32 get_sortId() { }
	// RVA: 0x2b5bc1c VA: 0x7595173c1c
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2b5bc98 VA: 0x7595173c98
	public PlayerRoguelikeChallengeStatus get_status() { }
	// RVA: 0x2b5bd00 VA: 0x7595173d00
	private Void set_status(PlayerRoguelikeChallengeStatus value) { }
	// RVA: 0x2b5bd7c VA: 0x7595173d7c
	public static RL02TopicChallengeStatusInfo CreateStatusInfo(String challengeId, Int32 sortId) { }
	// RVA: 0x2b5bf14 VA: 0x7595173f14
	public Void RefreshStatus(PlayerRoguelikeChallengeStatus status) { }
	// RVA: 0x2b5bea4 VA: 0x7595173ea4
	public Void .ctor() { }
}
```