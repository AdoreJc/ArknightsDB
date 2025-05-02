# RL03TopicChallengeStatusInfo

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
private class RL03TopicChallengeStatusInfo : IHotfixable
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

	// RVA: 0x2b8e668 VA: 0x75951a6668
	public String get_challengeId() { }
	// RVA: 0x2b8e6d0 VA: 0x75951a66d0
	private Void set_challengeId(String value) { }
	// RVA: 0x2b8e754 VA: 0x75951a6754
	public Int32 get_sortId() { }
	// RVA: 0x2b8e7bc VA: 0x75951a67bc
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2b8e838 VA: 0x75951a6838
	public PlayerRoguelikeChallengeStatus get_status() { }
	// RVA: 0x2b8e8a0 VA: 0x75951a68a0
	private Void set_status(PlayerRoguelikeChallengeStatus value) { }
	// RVA: 0x2b8e91c VA: 0x75951a691c
	public static RL03TopicChallengeStatusInfo CreateStatusInfo(String challengeId, Int32 sortId) { }
	// RVA: 0x2b8eab4 VA: 0x75951a6ab4
	public Void RefreshStatus(PlayerRoguelikeChallengeStatus status) { }
	// RVA: 0x2b8ea44 VA: 0x75951a6a44
	public Void .ctor() { }
}
```