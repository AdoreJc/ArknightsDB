# Act5D1EmptyState

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `String m_cacheStageId`

- `Boolean m_hasTriedToResumeStage`


## Methods

- `Void JumpToMission()`

- `Void JumpToShop()`

- `Void JumpToStage(String)`

- `IEnumerator _TryResumeStageState()`

- `Void <RegisterToDataListener>b__4_0(IStateBean)`

- `Void <OnResume>b__5_0()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1EmptyState : State
{
	private const String ENTRY_GUIDE_SUBSIGNAL; // 0x0
	private String m_cacheStageId; // 0x50
	private Boolean m_hasTriedToResumeStage; // 0x58
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_JumpToMission; // 0x18
	private static DelegateBridge __Hotfix0_JumpToShop; // 0x20
	private static DelegateBridge __Hotfix0_JumpToStage; // 0x28
	private static DelegateBridge __Hotfix0__TryResumeStageState; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x31cd970 VA: 0x75957e5970
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31cd9d4 VA: 0x75957e59d4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x31cdb4c VA: 0x75957e5b4c
	protected override Void OnResume() { }
	// RVA: 0x31cdc30 VA: 0x75957e5c30
	public Void JumpToMission() { }
	// RVA: 0x31cdd3c VA: 0x75957e5d3c
	public Void JumpToShop() { }
	// RVA: 0x31cde48 VA: 0x75957e5e48
	public Void JumpToStage(String stageId) { }
	// RVA: 0x31cdf78 VA: 0x75957e5f78
	private IEnumerator _TryResumeStageState() { }
	// RVA: 0x31ce04c VA: 0x75957e604c
	public Void .ctor() { }
	// RVA: 0x31ce0bc VA: 0x75957e60bc
	private Void <RegisterToDataListener>b__4_0(IStateBean stateBean) { }
	// RVA: 0x31ce1c4 VA: 0x75957e61c4
	private Void <OnResume>b__5_0() { }
	// RVA: 0x31ce248 VA: 0x75957e6248
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x31ce250 VA: 0x75957e6250
	private Void <>xLuaBaseProxy_OnResume() { }
}
```