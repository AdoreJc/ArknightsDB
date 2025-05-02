# ZoneHomeRecentViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String stageId`

- `String code`

- `String name`

- `HomeRecentStageType type`

- `String typeDesc`

- `String zoneId`

- `Boolean isRetro`


## Methods

- `Boolean IsStageEmpty()`

- `Void LoadData()`

- `Void _LoadLastRecentBattleStage(out, out)`

- `RecentBattleRecord _FindLastRecentBattleRecord()`

- `Void _LoadStageInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneHomeRecentViewModel : IHotfixable
{
	public String stageId; // 0x10
	public String code; // 0x18
	public String name; // 0x20
	public HomeRecentStageType type; // 0x28
	public String typeDesc; // 0x30
	public String zoneId; // 0x38
	public Boolean isRetro; // 0x40
	private static DelegateBridge __Hotfix0_IsStageEmpty; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__LoadLastRecentBattleStage; // 0x10
	private static DelegateBridge __Hotfix0__FindLastRecentBattleRecord; // 0x18
	private static DelegateBridge __Hotfix0__LoadStageInfo; // 0x20
	private static DelegateBridge __Hotfix0__GetTypeDesc; // 0x28
	private static DelegateBridge __Hotfix0__ConvertStageType; // 0x30
	private static DelegateBridge __Hotfix0__CheckIfRecordAvailable; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2f0c18c VA: 0x759552418c
	public Boolean IsStageEmpty() { }
	// RVA: 0x2f0c1f8 VA: 0x75955241f8
	public Void LoadData() { }
	// RVA: 0x2f0c2ac VA: 0x75955242ac
	private Void _LoadLastRecentBattleStage(out String stageId, out StageType type) { }
	// RVA: 0x2f0c6a4 VA: 0x75955246a4
	private RecentBattleRecord _FindLastRecentBattleRecord() { }
	// RVA: 0x2f0c560 VA: 0x7595524560
	private Void _LoadStageInfo() { }
	// RVA: 0x2f0c45c VA: 0x759552445c
	private static String _GetTypeDesc(HomeRecentStageType type) { }
	// RVA: 0x2f0c3cc VA: 0x75955243cc
	private static HomeRecentStageType _ConvertStageType(StageType stageType) { }
	// RVA: 0x2f0c7e8 VA: 0x75955247e8
	private static Boolean _CheckIfRecordAvailable(RecentBattleRecord record) { }
	// RVA: 0x2f0c8c4 VA: 0x75955248c4
	public Void .ctor() { }
}
```