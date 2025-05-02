# Act1LockSquadViewModel

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Boolean m_specialDefendInOtherStage`


## Properties

- `Boolean IsSpecialDefendInOtherStage`


## Methods

- `Boolean get_IsSpecialDefendInOtherStage()`

- `Void set_IsSpecialDefendInOtherStage(Boolean)`

- `Void LoadDataFromInterLockData(PlayerInterlockActivity, String, InterlockStageType)`

- `Boolean RestrictSquadMembers(HashSet`1)`

- `Boolean IsAutoBattle()`

- `SquadFriendData <>xLuaBaseProxy_GeneSquadFriendData(PredefinedAssistData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockSquadViewModel : SquadGroupViewModel
{
	private const Int32 INTERLOCK_SQUAD_NUM; // 0x0
	private Boolean m_specialDefendInOtherStage; // 0x39
	private static DelegateBridge __Hotfix0_get_IsSpecialDefendInOtherStage; // 0x0
	private static DelegateBridge __Hotfix0_set_IsSpecialDefendInOtherStage; // 0x8
	private static DelegateBridge __Hotfix0_LoadDataFromInterLockData; // 0x10
	private static DelegateBridge __Hotfix0_RestrictSquadMembers; // 0x18
	private static DelegateBridge __Hotfix0_GeneSquadFriendData; // 0x20
	private static DelegateBridge __Hotfix0_IsAutoBattle; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean IsSpecialDefendInOtherStage { get; set; }

	// RVA: 0x33d97c4 VA: 0x75959f17c4
	public Boolean get_IsSpecialDefendInOtherStage() { }
	// RVA: 0x33d7e48 VA: 0x75959efe48
	public Void set_IsSpecialDefendInOtherStage(Boolean value) { }
	// RVA: 0x33d7fd4 VA: 0x75959effd4
	public Void LoadDataFromInterLockData(PlayerInterlockActivity interlockData, String stageId, InterlockStageType stageType) { }
	// RVA: 0x33d8284 VA: 0x75959f0284
	public Boolean RestrictSquadMembers(HashSet`1 defendInstIdSet) { }
	// RVA: 0x33d982c VA: 0x75959f182c
	protected override SquadFriendData GeneSquadFriendData(PredefinedAssistData predefinedAssistData) { }
	// RVA: 0x33d9944 VA: 0x75959f1944
	public Boolean IsAutoBattle() { }
	// RVA: 0x33d7a78 VA: 0x75959efa78
	public Void .ctor() { }
	// RVA: 0x33d99b4 VA: 0x75959f19b4
	private SquadFriendData <>xLuaBaseProxy_GeneSquadFriendData(PredefinedAssistData P0) { }
}
```