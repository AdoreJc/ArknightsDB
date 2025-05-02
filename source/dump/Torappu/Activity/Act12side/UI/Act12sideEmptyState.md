# Act12sideEmptyState

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Act12sideStageController m_stageController`


## Properties

- `String activityId`

- `Act12sideStageController actController`


## Methods

- `String get_activityId()`

- `Act12sideStageController get_actController()`

- `Void _RegisterToMedalState(IStateBean)`

- `Void _RegisterToFavorUpState(IStateBean)`

- `Void _FetchStageController()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideEmptyState : State
{
	private Act12sideStageController m_stageController; // 0x50
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_get_actController; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__RegisterToMedalState; // 0x28
	private static DelegateBridge __Hotfix0__RegisterToFavorUpState; // 0x30
	private static DelegateBridge __Hotfix0__FetchStageController; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected String activityId { get; }
	protected Act12sideStageController actController { get; }

	// RVA: 0x345cab4 VA: 0x7595a74ab4
	protected String get_activityId() { }
	// RVA: 0x345cb84 VA: 0x7595a74b84
	protected Act12sideStageController get_actController() { }
	// RVA: 0x345cdcc VA: 0x7595a74dcc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x345ce30 VA: 0x7595a74e30
	protected override Void OnResume() { }
	// RVA: 0x345cf08 VA: 0x7595a74f08
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x345d0fc VA: 0x7595a750fc
	private Void _RegisterToMedalState(IStateBean stateBean) { }
	// RVA: 0x345d234 VA: 0x7595a75234
	private Void _RegisterToFavorUpState(IStateBean stateBean) { }
	// RVA: 0x345cc30 VA: 0x7595a74c30
	private Void _FetchStageController() { }
	// RVA: 0x345d3ec VA: 0x7595a753ec
	public Void .ctor() { }
	// RVA: 0x345d45c VA: 0x7595a7545c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x345d464 VA: 0x7595a75464
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```