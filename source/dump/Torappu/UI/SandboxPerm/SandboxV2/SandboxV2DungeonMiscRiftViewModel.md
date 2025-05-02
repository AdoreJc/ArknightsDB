# SandboxV2DungeonMiscRiftViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Boolean hasRift`

- `String mainTitle`

- `String subTitle`

- `String riftEndTips`

- `SandboxV2DungeonMiscRiftMainMissionState mainMissionState`

- `String seasonTitle`

- `String seasonDesc`

- `Color seasonCol`

- `Boolean isRandomRift`

- `Boolean isPreyRift`

- `Boolean hasGlobalEffect`

- `String globalEffectDesc`

- `Boolean useDifficulty`

- `Int32 curDifficultyLv`

- `String difficultyDesc`

- `Boolean hasTeam`

- `String teamName`

- `Int32 teamLv`

- `String teamDesc`

- `String m_riftId`

- `StringBuilder m_difficultyDescs`

- `StringBuilder m_teamDescs`


## Methods

- `Void LoadData(String, PlayerSandboxV2, SandboxV2Data, Dungeon)`

- `Void _LoadTitlePart(SandboxV2Data, Reservation)`

- `Void _LoadDayInfoPart(Dungeon)`

- `Void _LoadSeasonInfoPart(SandboxV2Data, Dungeon)`

- `Void _LoadFixRiftGlobalEffectPart(SandboxV2Data, RiftInfo)`

- `Void _LoadRiftDifficultyPart(SandboxV2Data, Reservation)`

- `Void _LoadTeamInfoPart(SandboxV2Data, RiftInfo, Reservation)`

- `SandboxV2DungeonMiscRiftMainMissionState _GetMainMissionState(GameInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMiscRiftViewModel : IHotfixable
{
	public Boolean hasRift; // 0x10
	public String mainTitle; // 0x18
	public String subTitle; // 0x20
	public String riftEndTips; // 0x28
	public SandboxV2DungeonMiscRiftMainMissionState mainMissionState; // 0x30
	public String seasonTitle; // 0x38
	public String seasonDesc; // 0x40
	public Color seasonCol; // 0x48
	public Boolean isRandomRift; // 0x58
	public Boolean isPreyRift; // 0x59
	public Boolean hasGlobalEffect; // 0x5a
	public String globalEffectDesc; // 0x60
	public Boolean useDifficulty; // 0x68
	public Int32 curDifficultyLv; // 0x6c
	public String difficultyDesc; // 0x70
	public Boolean hasTeam; // 0x78
	public String teamName; // 0x80
	public Int32 teamLv; // 0x88
	public String teamDesc; // 0x90
	private String m_riftId; // 0x98
	private StringBuilder m_difficultyDescs; // 0xa0
	private StringBuilder m_teamDescs; // 0xa8
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadTitlePart; // 0x8
	private static DelegateBridge __Hotfix0__LoadDayInfoPart; // 0x10
	private static DelegateBridge __Hotfix0__LoadSeasonInfoPart; // 0x18
	private static DelegateBridge __Hotfix0__LoadFixRiftGlobalEffectPart; // 0x20
	private static DelegateBridge __Hotfix0__LoadRiftDifficultyPart; // 0x28
	private static DelegateBridge __Hotfix0__LoadTeamInfoPart; // 0x30
	private static DelegateBridge __Hotfix0__GetMainMissionState; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x25b3694 VA: 0x7594bcb694
	public Void LoadData(String topicId, PlayerSandboxV2 playerTopicData, SandboxV2Data topicDetailData, Dungeon playerDungeonData) { }
	// RVA: 0x25b38bc VA: 0x7594bcb8bc
	private Void _LoadTitlePart(SandboxV2Data topicDetailData, Reservation riftReservation) { }
	// RVA: 0x25b3a14 VA: 0x7594bcba14
	private Void _LoadDayInfoPart(Dungeon playerDungeonData) { }
	// RVA: 0x25b3c28 VA: 0x7594bcbc28
	private Void _LoadSeasonInfoPart(SandboxV2Data topicDetailData, Dungeon playerDungeonData) { }
	// RVA: 0x25b3dc0 VA: 0x7594bcbdc0
	private Void _LoadFixRiftGlobalEffectPart(SandboxV2Data topicDetailData, RiftInfo riftInfo) { }
	// RVA: 0x25b3ef4 VA: 0x7594bcbef4
	private Void _LoadRiftDifficultyPart(SandboxV2Data topicDetailData, Reservation riftReservation) { }
	// RVA: 0x25b41e8 VA: 0x7594bcc1e8
	private Void _LoadTeamInfoPart(SandboxV2Data topicDetailData, RiftInfo riftInfo, Reservation riftReservation) { }
	// RVA: 0x25b3b18 VA: 0x7594bcbb18
	private SandboxV2DungeonMiscRiftMainMissionState _GetMainMissionState(GameInfo playerRiftGameInfo) { }
	// RVA: 0x25b44cc VA: 0x7594bcc4cc
	public Void .ctor() { }
}
```