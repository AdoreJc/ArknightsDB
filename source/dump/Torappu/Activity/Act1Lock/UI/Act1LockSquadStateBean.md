# Act1LockSquadStateBean

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `SquadGroupViewProperty squadGroupProperty`

- `String activityId`

- `String stageId`

- `InterlockStageType interlockStageType`

- `SquadMode squadMode`

- `SquadStartButtonTypeEnum startButtonMode`

- `String startButtonOverrideId`

- `Boolean m_isSquadValid`


## Properties

- `Boolean isFriendLegal`

- `Boolean isSquadValid`

- `Boolean isSquadImmutable`


## Methods

- `Boolean get_isFriendLegal()`

- `Boolean get_isSquadValid()`

- `Boolean get_isSquadImmutable()`

- `Void LoadData(Params)`

- `Void LoadDataInternal(String, String, InterlockStageType, Boolean, Boolean)`

- `Void TryReloadSquadData()`

- `SquadModel ParseBattleStartRequestSquad()`

- `Boolean IsCurrentSquadEmpty()`

- `Void CleanAssistChar()`

- `Boolean IsAssistSelected()`

- `Boolean CheckIfSquadChanged()`

- `SharedCharData GetSpecialAssistData()`

- `Boolean CheckIfCharSelectable(Int32)`

- `Boolean CheckIfCharSelectable(CharQuery)`

- `Boolean TryGetRegionInterlockIndex(out)`

- `Boolean _CheckIfMemberChanged(SquadItemStruct, PlayerSquadItem)`

- `Boolean _CheckIfSpecialAssistDefendInOtherStage()`

- `Boolean _CheckIsSpecialAssist(VerifyOption)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockSquadStateBean : IStateBean, IHotfixable, IDataBindWrapper
{
	public SquadGroupViewProperty squadGroupProperty; // 0x10
	public String activityId; // 0x18
	public String stageId; // 0x20
	public InterlockStageType interlockStageType; // 0x28
	public SquadMode squadMode; // 0x2c
	public SquadStartButtonTypeEnum startButtonMode; // 0x30
	public String startButtonOverrideId; // 0x38
	private Boolean m_isSquadValid; // 0x40
	private HashSet`1 m_defendCharInstIdSet; // 0x48
	private static DelegateBridge __Hotfix0_get_isFriendLegal; // 0x0
	private static DelegateBridge __Hotfix0_get_isSquadValid; // 0x8
	private static DelegateBridge __Hotfix0_get_isSquadImmutable; // 0x10
	private static DelegateBridge __Hotfix0_CreateSquadToStartBattle; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_LoadDataInternal; // 0x28
	private static DelegateBridge __Hotfix0_TryReloadSquadData; // 0x30
	private static DelegateBridge __Hotfix0_ParseBattleStartRequestSquad; // 0x38
	private static DelegateBridge __Hotfix0_IsCurrentSquadEmpty; // 0x40
	private static DelegateBridge __Hotfix0_CleanAssistChar; // 0x48
	private static DelegateBridge __Hotfix0_IsAssistSelected; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfSquadChanged; // 0x58
	private static DelegateBridge __Hotfix0_GetSpecialAssistData; // 0x60
	private static DelegateBridge __Hotfix0_CheckIfCharSelectable; // 0x68
	private static DelegateBridge __Hotfix1_CheckIfCharSelectable; // 0x70
	private static DelegateBridge __Hotfix0_TryGetRegionInterlockIndex; // 0x78
	private static DelegateBridge __Hotfix0__CheckIfMemberChanged; // 0x80
	private static DelegateBridge __Hotfix0__GetDefendCharInstIdSet; // 0x88
	private static DelegateBridge __Hotfix0__CheckIfSpecialAssistDefendInOtherStage; // 0x90
	private static DelegateBridge __Hotfix0__GetStartButtonType; // 0x98
	private static DelegateBridge __Hotfix0__CheckIsSpecialAssist; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public Boolean isFriendLegal { get; }
	public Boolean isSquadValid { get; }
	public Boolean isSquadImmutable { get; }

	// RVA: 0x33d7188 VA: 0x75959ef188
	public Boolean get_isFriendLegal() { }
	// RVA: 0x33d7378 VA: 0x75959ef378
	public Boolean get_isSquadValid() { }
	// RVA: 0x33d73e0 VA: 0x75959ef3e0
	public Boolean get_isSquadImmutable() { }
	// RVA: 0x33d7450 VA: 0x75959ef450
	public SquadItemStruct[] CreateSquadToStartBattle() { }
	// RVA: 0x33d7644 VA: 0x75959ef644
	public Void LoadData(Params pageParams) { }
	// RVA: 0x33d7714 VA: 0x75959ef714
	private Void LoadDataInternal(String activityId, String stageId, InterlockStageType interlockStageType, Boolean isAutoBattle, Boolean isPractice) { }
	// RVA: 0x33d8468 VA: 0x75959f0468
	public Void TryReloadSquadData() { }
	// RVA: 0x33d8568 VA: 0x75959f0568
	public SquadModel ParseBattleStartRequestSquad() { }
	// RVA: 0x33d88d0 VA: 0x75959f08d0
	public Boolean IsCurrentSquadEmpty() { }
	// RVA: 0x33d8ad8 VA: 0x75959f0ad8
	public Void CleanAssistChar() { }
	// RVA: 0x33d8b64 VA: 0x75959f0b64
	public Boolean IsAssistSelected() { }
	// RVA: 0x33d8bf4 VA: 0x75959f0bf4
	public Boolean CheckIfSquadChanged() { }
	// RVA: 0x33d9108 VA: 0x75959f1108
	public SharedCharData GetSpecialAssistData() { }
	// RVA: 0x33d9178 VA: 0x75959f1178
	public Boolean CheckIfCharSelectable(Int32 charInstId) { }
	// RVA: 0x33d9224 VA: 0x75959f1224
	public Boolean CheckIfCharSelectable(CharQuery charQuery) { }
	// RVA: 0x33d9324 VA: 0x75959f1324
	public Boolean TryGetRegionInterlockIndex(out Int32 index) { }
	// RVA: 0x33d8f64 VA: 0x75959f0f64
	private Boolean _CheckIfMemberChanged(SquadItemStruct viewItem, PlayerSquadItem prevMember) { }
	// RVA: 0x33d7ae8 VA: 0x75959efae8
	private HashSet`1 _GetDefendCharInstIdSet(String stageId) { }
	// RVA: 0x33d7dac VA: 0x75959efdac
	private Boolean _CheckIfSpecialAssistDefendInOtherStage() { }
	// RVA: 0x33d7ec8 VA: 0x75959efec8
	private static Void _GetStartButtonType(StageData stageData, InterlockStageType type, Boolean isPractice, out SquadStartButtonTypeEnum startButtonMode, out String startButtonOverrideId) { }
	// RVA: 0x33d9434 VA: 0x75959f1434
	private Boolean _CheckIsSpecialAssist(VerifyOption verifyOption) { }
	// RVA: 0x33d9538 VA: 0x75959f1538
	public Void .ctor() { }
}
```