# SandboxV2RiftQuestTrackerViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String mainTitlePrefix`

- `String mainTitle`

- `String mainStoryDesc`

- `String mainTargetDesc`

- `SandboxV2DungeonMiscRiftMainMissionState mainMissionState`

- `Int32 mainTargetProgress`

- `Int32 mainTargetTotal`

- `Boolean hasSubTarget`

- `String subTargetName`

- `String subTargetDesc`

- `Int32 subTargetProgress`

- `Int32 subTargetTotal`

- `Boolean isSubTargetComplete`

- `String m_riftId`

- `Boolean m_isRandomRift`

- `Boolean m_isPreyRift`

- `Int32 m_enterSeq`


## Properties

- `Int32 enterSeq`


## Methods

- `Int32 get_enterSeq()`

- `Void LoadData(String)`

- `Void NotifyEnterSeq()`

- `Void _LoadMainTargetPart(SandboxV2Data, List`1, Reservation, GameInfo)`

- `SandboxV2DungeonMiscRiftMainMissionState _GetMainMissionState(GameInfo)`

- `Void _LoadSubTargetPart(SandboxV2Data, Reservation, GameInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftQuestTrackerViewModel : IHotfixable
{
	public String mainTitlePrefix; // 0x10
	public String mainTitle; // 0x18
	public String mainStoryDesc; // 0x20
	public String mainTargetDesc; // 0x28
	public SandboxV2DungeonMiscRiftMainMissionState mainMissionState; // 0x30
	public Int32 mainTargetProgress; // 0x34
	public Int32 mainTargetTotal; // 0x38
	public List`1 mainTargetRewards; // 0x40
	public Boolean hasSubTarget; // 0x48
	public String subTargetName; // 0x50
	public String subTargetDesc; // 0x58
	public Int32 subTargetProgress; // 0x60
	public Int32 subTargetTotal; // 0x64
	public Boolean isSubTargetComplete; // 0x68
	public List`1 subTargetRewards; // 0x70
	private String m_riftId; // 0x78
	private Boolean m_isRandomRift; // 0x80
	private Boolean m_isPreyRift; // 0x81
	private Int32 m_enterSeq; // 0x84
	private const Int32 DEFAULT_ITEM_COUNT_FOR_DISPLAY; // 0x0
	private static DelegateBridge __Hotfix0_get_enterSeq; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_NotifyEnterSeq; // 0x10
	private static DelegateBridge __Hotfix0__LoadMainTargetPart; // 0x18
	private static DelegateBridge __Hotfix0__GetMainMissionState; // 0x20
	private static DelegateBridge __Hotfix0__LoadSubTargetPart; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 enterSeq { get; }

	// RVA: 0x2559114 VA: 0x7594b71114
	public Int32 get_enterSeq() { }
	// RVA: 0x255506c VA: 0x7594b6d06c
	public Void LoadData(String topicId) { }
	// RVA: 0x2555274 VA: 0x7594b6d274
	public Void NotifyEnterSeq() { }
	// RVA: 0x255a094 VA: 0x7594b72094
	private Void _LoadMainTargetPart(SandboxV2Data gameData, List`1 fixFinish, Reservation riftReservation, GameInfo riftGameInfo) { }
	// RVA: 0x255a9c8 VA: 0x7594b729c8
	private SandboxV2DungeonMiscRiftMainMissionState _GetMainMissionState(GameInfo playerRiftGameInfo) { }
	// RVA: 0x255a6d4 VA: 0x7594b726d4
	private Void _LoadSubTargetPart(SandboxV2Data gameData, Reservation riftReservation, GameInfo riftGameInfo) { }
	// RVA: 0x255aad8 VA: 0x7594b72ad8
	public Void .ctor() { }
}
```