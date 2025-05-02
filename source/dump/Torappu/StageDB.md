# StageDB

**Namespace:** `Torappu`


## Methods

- `String GetNormalStageIdByHard(String)`

- `String GetNormalStageIdBySixStar(String)`

- `String _GetNormalStageId(String, Dictionary`2)`

- `String GetNormalStageIdByRelatedStageId(String)`

- `Boolean TryGetTileAppendInfo(String, out)`

- `Boolean TryGetStageFogInfoByStageId(String, out)`

- `Boolean TryGetStageFogInfoByFogId(String, out)`

- `Void _InitFogSearchTables()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StageDB : ConstTable`2
{
	public static readonly HashSet`1 AUDIT_ZONE_WHITE_LIST; // 0x0
	public const String AUDIT_DEFAULT_LEVEL; // 0x0
	private Dictionary`2 m_hardToNormalMap; // 0x60
	private Dictionary`2 m_sixStarToNormalMap; // 0x68
	private List`1 m_stageEvents; // 0x70
	private List`1 m_campaignStages; // 0x78
	private List`1 m_zoneVitalFogs; // 0x80
	private Dictionary`2 m_stageToFogMap; // 0x88
	private Dictionary`2 m_diffGroupStageIdToNormalMap; // 0x90
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_GetStageEventList; // 0x10
	private static DelegateBridge __Hotfix0_GetNormalStageIdByHard; // 0x18
	private static DelegateBridge __Hotfix0_GetNormalStageIdBySixStar; // 0x20
	private static DelegateBridge __Hotfix0__GetNormalStageId; // 0x28
	private static DelegateBridge __Hotfix0_GetNormalStageIdByRelatedStageId; // 0x30
	private static DelegateBridge __Hotfix0_TryGetTileAppendInfo; // 0x38
	private static DelegateBridge __Hotfix0_TryGetStageFogInfoByStageId; // 0x40
	private static DelegateBridge __Hotfix0_TryGetStageFogInfoByFogId; // 0x48
	private static DelegateBridge __Hotfix0_GetCampaignStages; // 0x50
	private static DelegateBridge __Hotfix0_GetZoneVitalFogEnumerator; // 0x58
	private static DelegateBridge __Hotfix0__FlushLevelsToDefault; // 0x60
	private static DelegateBridge __Hotfix0__InitFogSearchTables; // 0x68
	private static DelegateBridge __Hotfix0__CheckIfStageFogVitalForZone; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x31f9a70 VA: 0x7595811a70
	protected override Void OnInit() { }
	// RVA: 0x31fa71c VA: 0x759581271c
	public List`1 GetStageEventList() { }
	// RVA: 0x31fa794 VA: 0x7595812794
	public String GetNormalStageIdByHard(String hardStageId) { }
	// RVA: 0x31fa924 VA: 0x7595812924
	public String GetNormalStageIdBySixStar(String sixStarStageId) { }
	// RVA: 0x31fa828 VA: 0x7595812828
	private String _GetNormalStageId(String notNormalStageId, Dictionary`2 stageIdMap) { }
	// RVA: 0x31fa9b8 VA: 0x75958129b8
	public String GetNormalStageIdByRelatedStageId(String relatedStageId) { }
	// RVA: 0x31faab4 VA: 0x7595812ab4
	public Boolean TryGetTileAppendInfo(String tileKey, out TileAppendInfo tileInfo) { }
	// RVA: 0x31fabc8 VA: 0x7595812bc8
	public Boolean TryGetStageFogInfoByStageId(String stageId, out StageFogInfo fogInfo) { }
	// RVA: 0x31facb8 VA: 0x7595812cb8
	public Boolean TryGetStageFogInfoByFogId(String fogId, out StageFogInfo fogInfo) { }
	// RVA: 0x31fadc8 VA: 0x7595812dc8
	public List`1 GetCampaignStages() { }
	// RVA: 0x31fae40 VA: 0x7595812e40
	public IEnumerator`1 GetZoneVitalFogEnumerator() { }
	// RVA: 0x31fa5a4 VA: 0x75958125a4
	private static Void _FlushLevelsToDefault(StageTable stageTable) { }
	// RVA: 0x31fa1a0 VA: 0x75958121a0
	private Void _InitFogSearchTables() { }
	// RVA: 0x31faf18 VA: 0x7595812f18
	private static Boolean _CheckIfStageFogVitalForZone(StageFogInfo fogInfo, String curZone, Dictionary`2 fogToZoneMap, Dictionary`2 stageMap) { }
	// RVA: 0x31fb0c4 VA: 0x75958130c4
	public Void .ctor() { }
	// RVA: 0x31fb348 VA: 0x7595813348
	private static Void .cctor() { }
}
```