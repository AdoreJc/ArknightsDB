# ClimbTowerSquadCreateStateBean

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SquadGroupViewProperty m_squadProperty`

- `Int32 m_selectAssistIndex`

- `ProfessionCategory m_assistProfession`

- `FriendAssistDataStruct m_friendDataCache`

- `String m_towerId`

- `Int32 m_currentStep`

- `Int32 m_totalStepCount`


## Properties

- `Int32 selectAssistIndex`

- `ProfessionCategory assistProfession`

- `SquadGroupViewProperty squadProperty`

- `FriendAssistDataStruct friendDataCache`

- `Int32 totalStepCount`

- `Int32 currentStep`


## Methods

- `Int32 get_selectAssistIndex()`

- `Void set_selectAssistIndex(Int32)`

- `ProfessionCategory get_assistProfession()`

- `Void set_assistProfession(ProfessionCategory)`

- `SquadGroupViewProperty get_squadProperty()`

- `FriendAssistDataStruct get_friendDataCache()`

- `Void set_friendDataCache(FriendAssistDataStruct)`

- `Int32 get_totalStepCount()`

- `Int32 get_currentStep()`

- `Void InitData()`

- `Void _InitSquadProperty(PlayerTower)`

- `Boolean CheckIfContainedInOtherAssist(String)`

- `Boolean TryGetMutuallyExclusiveCharInfoInAssist(String, out)`

- `Void ApplyToFriendAssistBean(SquadFriendAssistStateBean)`

- `Boolean ReceiveFromFriendAssistBean(SquadFriendAssistStateBean)`

- `Void ApplySquadFromCharSelect(CharSelectStateBean)`

- `Void RefreshData()`

- `Void SaveConfigToCache()`

- `Void SetHasSelectSquad()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadCreateStateBean : IStateBean, IHotfixable
{
	private SquadGroupViewProperty m_squadProperty; // 0x10
	private Int32 m_selectAssistIndex; // 0x18
	private ProfessionCategory m_assistProfession; // 0x1c
	private FriendAssistDataStruct m_friendDataCache; // 0x20
	private String m_towerId; // 0x30
	private Int32 m_currentStep; // 0x38
	private Int32 m_totalStepCount; // 0x3c
	private static DelegateBridge __Hotfix0_get_selectAssistIndex; // 0x0
	private static DelegateBridge __Hotfix0_set_selectAssistIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_assistProfession; // 0x10
	private static DelegateBridge __Hotfix0_set_assistProfession; // 0x18
	private static DelegateBridge __Hotfix0_get_squadProperty; // 0x20
	private static DelegateBridge __Hotfix0_get_friendDataCache; // 0x28
	private static DelegateBridge __Hotfix0_set_friendDataCache; // 0x30
	private static DelegateBridge __Hotfix0_get_totalStepCount; // 0x38
	private static DelegateBridge __Hotfix0_get_currentStep; // 0x40
	private static DelegateBridge __Hotfix0_InitData; // 0x48
	private static DelegateBridge __Hotfix0__InitSquadProperty; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfContainedInOtherAssist; // 0x58
	private static DelegateBridge __Hotfix0_TryGetMutuallyExclusiveCharInfoInAssist; // 0x60
	private static DelegateBridge __Hotfix0_ApplyToFriendAssistBean; // 0x68
	private static DelegateBridge __Hotfix0_ReceiveFromFriendAssistBean; // 0x70
	private static DelegateBridge __Hotfix0_ApplySquadFromCharSelect; // 0x78
	private static DelegateBridge __Hotfix0_RefreshData; // 0x80
	private static DelegateBridge __Hotfix0_SaveConfigToCache; // 0x88
	private static DelegateBridge __Hotfix0_SetHasSelectSquad; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public Int32 selectAssistIndex { get; set; }
	public ProfessionCategory assistProfession { get; set; }
	public SquadGroupViewProperty squadProperty { get; }
	public FriendAssistDataStruct friendDataCache { get; set; }
	public Int32 totalStepCount { get; }
	public Int32 currentStep { get; }

	// RVA: 0x2cb41bc VA: 0x75952cc1bc
	public Int32 get_selectAssistIndex() { }
	// RVA: 0x2cb4224 VA: 0x75952cc224
	public Void set_selectAssistIndex(Int32 value) { }
	// RVA: 0x2cb42a0 VA: 0x75952cc2a0
	public ProfessionCategory get_assistProfession() { }
	// RVA: 0x2cb4308 VA: 0x75952cc308
	public Void set_assistProfession(ProfessionCategory value) { }
	// RVA: 0x2cb3894 VA: 0x75952cb894
	public SquadGroupViewProperty get_squadProperty() { }
	// RVA: 0x2cb4384 VA: 0x75952cc384
	public FriendAssistDataStruct get_friendDataCache() { }
	// RVA: 0x2cb3e94 VA: 0x75952cbe94
	public Void set_friendDataCache(FriendAssistDataStruct value) { }
	// RVA: 0x2cb43e8 VA: 0x75952cc3e8
	public Int32 get_totalStepCount() { }
	// RVA: 0x2cb4450 VA: 0x75952cc450
	public Int32 get_currentStep() { }
	// RVA: 0x2cb44b8 VA: 0x75952cc4b8
	public Void InitData() { }
	// RVA: 0x2cb45b8 VA: 0x75952cc5b8
	private Void _InitSquadProperty(PlayerTower playerTower) { }
	// RVA: 0x2cb2e84 VA: 0x75952cae84
	public Boolean CheckIfContainedInOtherAssist(String charId) { }
	// RVA: 0x2cb2f80 VA: 0x75952caf80
	public Boolean TryGetMutuallyExclusiveCharInfoInAssist(String charId, out String exclusiveCharInfo) { }
	// RVA: 0x2cb4c38 VA: 0x75952ccc38
	public Void ApplyToFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x2cb4fa4 VA: 0x75952ccfa4
	public Boolean ReceiveFromFriendAssistBean(SquadFriendAssistStateBean assistBean) { }
	// RVA: 0x2cb5250 VA: 0x75952cd250
	public Void ApplySquadFromCharSelect(CharSelectStateBean charSelectBean) { }
	// RVA: 0x2cb5c84 VA: 0x75952cdc84
	public Void RefreshData() { }
	// RVA: 0x2cb5d7c VA: 0x75952cdd7c
	public Void SaveConfigToCache() { }
	// RVA: 0x2cb620c VA: 0x75952ce20c
	public Void SetHasSelectSquad() { }
	// RVA: 0x2cb62dc VA: 0x75952ce2dc
	public Void .ctor() { }
}
```