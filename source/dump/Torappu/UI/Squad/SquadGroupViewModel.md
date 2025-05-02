# SquadGroupViewModel

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadMode mode`

- `Int32 selectedIndex`

- `SquadFriendData assistCharModel`

- `SquadGroupConstrainPolicy m_constrainPolicy`

- `Boolean isFriendAssist`


## Properties

- `SquadMode squadMode`


## Methods

- `SquadMode get_squadMode()`

- `Void SetConstrainPolicy(SquadGroupConstrainPolicy)`

- `Boolean CheckIfAssistLocked()`

- `Boolean CheckIfSquadSlotLocked(SquadViewModel, Int32)`

- `Boolean IsAssistEnabled()`

- `Void LoadDataNormal()`

- `Void ReloadName()`

- `Void LoadDataPredefined(List`1)`

- `Void LoadDataOverrideSkillSelectable()`

- `Void LoadDataAutoBattle(BattleLog)`

- `Void GenerateAutoBattleBannedCharList(ExternalRuneChecker)`

- `Boolean IsAutoBattleCharBanned(String)`

- `Void EnsureAutoBattleBannedList()`

- `Void LoadDataCustomized()`

- `Void ClearAssistCharIfConflict(IList`1)`

- `Int32 GetCurSquadValidMemberNum()`

- `Int32 GetSquadAssistNum()`

- `SquadGroupConstrainPolicy EnsureConstrains()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadGroupViewModel : IHotfixable
{
	protected SquadMode mode; // 0x10
	public Int32 selectedIndex; // 0x14
	public SquadViewModel[] squads; // 0x18
	public SquadFriendData assistCharModel; // 0x20
	private SquadGroupConstrainPolicy m_constrainPolicy; // 0x28
	private HashSet`1 m_autoModeBannedCharIds; // 0x30
	public Boolean isFriendAssist; // 0x38
	private static DelegateBridge __Hotfix0_get_squadMode; // 0x0
	private static DelegateBridge __Hotfix0_SetConstrainPolicy; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfAssistLocked; // 0x10
	private static DelegateBridge __Hotfix0_CheckIfSquadSlotLocked; // 0x18
	private static DelegateBridge __Hotfix0_IsAssistEnabled; // 0x20
	private static DelegateBridge __Hotfix0_LoadDataNormal; // 0x28
	private static DelegateBridge __Hotfix0_ReloadName; // 0x30
	private static DelegateBridge __Hotfix0_LoadDataPredefined; // 0x38
	private static DelegateBridge __Hotfix0_LoadDataOverrideSkillSelectable; // 0x40
	private static DelegateBridge __Hotfix0_LoadDataAutoBattle; // 0x48
	private static DelegateBridge __Hotfix0_GenerateAutoBattleBannedCharList; // 0x50
	private static DelegateBridge __Hotfix0_IsAutoBattleCharBanned; // 0x58
	private static DelegateBridge __Hotfix0_EnsureAutoBattleBannedList; // 0x60
	private static DelegateBridge __Hotfix0_LoadDataCustomized; // 0x68
	private static DelegateBridge __Hotfix0_GeneSquadFriendData; // 0x70
	private static DelegateBridge __Hotfix0_ClearAssistCharIfConflict; // 0x78
	private static DelegateBridge __Hotfix0_GetCurSquadValidMemberNum; // 0x80
	private static DelegateBridge __Hotfix0_GetSquadAssistNum; // 0x88
	private static DelegateBridge __Hotfix0_EnsureConstrains; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public SquadMode squadMode { get; }

	// RVA: 0x2393a88 VA: 0x75949aba88
	public SquadMode get_squadMode() { }
	// RVA: 0x238ec0c VA: 0x75949a6c0c
	public Void SetConstrainPolicy(SquadGroupConstrainPolicy policy) { }
	// RVA: 0x2393af0 VA: 0x75949abaf0
	public Boolean CheckIfAssistLocked() { }
	// RVA: 0x2393c1c VA: 0x75949abc1c
	public Boolean CheckIfSquadSlotLocked(SquadViewModel squadModel, Int32 index) { }
	// RVA: 0x2393cbc VA: 0x75949abcbc
	public Boolean IsAssistEnabled() { }
	// RVA: 0x2393d48 VA: 0x75949abd48
	public Void LoadDataNormal() { }
	// RVA: 0x2388820 VA: 0x75949a0820
	public Void ReloadName() { }
	// RVA: 0x23941d0 VA: 0x75949ac1d0
	public Void LoadDataPredefined(List`1 predefined) { }
	// RVA: 0x2394480 VA: 0x75949ac480
	public Void LoadDataOverrideSkillSelectable() { }
	// RVA: 0x23944ec VA: 0x75949ac4ec
	public Void LoadDataAutoBattle(BattleLog battleLog) { }
	// RVA: 0x2394950 VA: 0x75949ac950
	public Void GenerateAutoBattleBannedCharList(ExternalRuneChecker checker) { }
	// RVA: 0x2394c20 VA: 0x75949acc20
	public Boolean IsAutoBattleCharBanned(String charId) { }
	// RVA: 0x2394b58 VA: 0x75949acb58
	private Void EnsureAutoBattleBannedList() { }
	// RVA: 0x238ec90 VA: 0x75949a6c90
	public Void LoadDataCustomized() { }
	// RVA: 0x2394cf8 VA: 0x75949accf8
	protected virtual SquadFriendData GeneSquadFriendData(PredefinedAssistData predefinedAssistData) { }
	// RVA: 0x237fbdc VA: 0x7594997bdc
	public Void ClearAssistCharIfConflict(IList`1 squadMembers) { }
	// RVA: 0x2390ec0 VA: 0x75949a8ec0
	public Int32 GetCurSquadValidMemberNum() { }
	// RVA: 0x2390f60 VA: 0x75949a8f60
	public Int32 GetSquadAssistNum() { }
	// RVA: 0x2393b6c VA: 0x75949abb6c
	protected SquadGroupConstrainPolicy EnsureConstrains() { }
	// RVA: 0x23917c4 VA: 0x75949a97c4
	public Void .ctor() { }
}
```