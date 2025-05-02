# ExternalRuneChecker

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadNumChangeInfoByRune m_squadNumChangeInfo`


## Methods

- `Void LoadData(StageData, LevelData, List`1)`

- `Void LoadData(LevelData, List`1)`

- `Void _LoadDataImpl(Difficulty, LevelData, List`1)`

- `Void _ApplyExcludeOrSquadNumChangeRunes(String, RuneDataType, Func`2, ref, ref)`

- `CheckSquadResult CheckSquadHasExcludedCharOrLimit(IList`1, SharedCharData, Int32)`

- `Boolean CheckIfCharValid(CharQuery)`

- `Void LoadExcludedCharInSquad(IList`1, SharedCharData, List`1)`

- `Boolean TryGetSquadNumChangeInfo(out)`

- `Boolean _CheckIsFriendAssistExcluded(SharedCharData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class ExternalRuneChecker
{
	private List`1 m_excludeRunes; // 0x10
	private String[] m_commonExcludeCharIdList; // 0x18
	private SquadNumChangeInfoByRune m_squadNumChangeInfo; // 0x20


	// RVA: 0x238bb38 VA: 0x75949a3b38
	public Void .ctor() { }
	// RVA: 0x238bbf4 VA: 0x75949a3bf4
	public Void .ctor(StageData stageData, LevelData levelData) { }
	// RVA: 0x238bcec VA: 0x75949a3cec
	public Void LoadData(StageData stageData, LevelData levelData, List`1 selectedRunes) { }
	// RVA: 0x238c288 VA: 0x75949a4288
	public Void LoadData(LevelData levelData, List`1 selectedRunes) { }
	// RVA: 0x238bd00 VA: 0x75949a3d00
	private Void _LoadDataImpl(Difficulty difficulty, LevelData levelData, List`1 selectedRunes) { }
	// RVA: 0x VA: 0x0
	private Void _ApplyExcludeOrSquadNumChangeRunes(String runeKey, RuneDataType runeData, Func`2 convertRuneData, ref Int32 runeLimitNum, ref Int32 runeModifyNum) { }
	// RVA: 0x238c334 VA: 0x75949a4334
	public CheckSquadResult CheckSquadHasExcludedCharOrLimit(IList`1 squad, SharedCharData friendAssist, Int32 maxSquadNum) { }
	// RVA: 0x238cd5c VA: 0x75949a4d5c
	public Boolean CheckIfCharValid(CharQuery query) { }
	// RVA: 0x238cfb4 VA: 0x75949a4fb4
	public Void LoadExcludedCharInSquad(IList`1 squad, SharedCharData friendAssist, List`1 result) { }
	// RVA: 0x238d6e0 VA: 0x75949a56e0
	public Boolean TryGetSquadNumChangeInfo(out SquadNumChangeInfoByRune changeInfoByRune) { }
	// RVA: 0x238cc0c VA: 0x75949a4c0c
	private Boolean _CheckIsFriendAssistExcluded(SharedCharData friendAssist) { }
	// RVA: 0x238d748 VA: 0x75949a5748
	private static Boolean _TryGetSquadNumLimitFromRuneData(RuneData runeData, out Int32 squadNumLimit) { }
	// RVA: 0x238d7f0 VA: 0x75949a57f0
	private static Boolean _TryGetSquadNumModifyFromRuneData(RuneData runeData, out Int32 squadNumModify) { }
	// RVA: 0x238c7dc VA: 0x75949a47dc
	private static Int32 _GetValidSquadCharNum(IList`1 squad, SharedCharData friendAssist) { }
}
```