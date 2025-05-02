# BuildingWorkshopHomeState

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `BuildingWorkshopStateBean _stateBean`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `BuildingWorkshopWholeView _wholeView`


## Methods

- `Void _InitTopMenu()`

- `Void _LoadFromRuntime(BuildingWorkshopModel)`

- `Void OnDestroy()`

- `Void _OnPlayerDataChanged()`

- `Void _SetWorkCount(Int32)`

- `Void OnCharacterButtonPressed()`

- `Void OnFormulaButtonPressed()`

- `Void OnAddButtonPressed()`

- `Void OnMinusButtonPressed()`

- `Void OnMaxButtonPressed()`

- `Void OnMinButtonPressed()`

- `Void OnProtectSwitchButtonPressed()`

- `Void _HandleWorkshopResult(WorkResult)`

- `Void _ShowOKDialog(String, Action)`

- `Void OnConfirmButtonPressed()`

- `Void OnPrevFormulaButtonPressed()`

- `Void OnIngredientJumpBtnPressed(Int32)`

- `Void <_InitTopMenu>b__4_0(GameObject)`

- `Void <_InitTopMenu>b__4_1()`

- `Void <RegisterToDataListener>b__10_0(IStateBean)`

- `Void <_HandleWorkshopResult>b__22_0()`

- `IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopHomeState : State
{
	private BuildingWorkshopStateBean _stateBean; // 0x50
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x58
	private BuildingWorkshopWholeView _wholeView; // 0x60
	private StateCacheHandler`1 m_runtimeHandler; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x8
	private static DelegateBridge __Hotfix0_get_cacheHandler; // 0x10
	private static DelegateBridge __Hotfix0__LoadFromRuntime; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge __Hotfix0_OnResume; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x40
	private static DelegateBridge __Hotfix0__SetWorkCount; // 0x48
	private static DelegateBridge __Hotfix0_OnCharacterButtonPressed; // 0x50
	private static DelegateBridge __Hotfix0_OnFormulaButtonPressed; // 0x58
	private static DelegateBridge __Hotfix0_OnAddButtonPressed; // 0x60
	private static DelegateBridge __Hotfix0_OnMinusButtonPressed; // 0x68
	private static DelegateBridge __Hotfix0_OnMaxButtonPressed; // 0x70
	private static DelegateBridge __Hotfix0_OnMinButtonPressed; // 0x78
	private static DelegateBridge __Hotfix0_OnProtectSwitchButtonPressed; // 0x80
	private static DelegateBridge __Hotfix0__HandleWorkshopResult; // 0x88
	private static DelegateBridge __Hotfix0__ShowOKDialog; // 0x90
	private static DelegateBridge __Hotfix0_OnConfirmButtonPressed; // 0x98
	private static DelegateBridge __Hotfix0_OnPrevFormulaButtonPressed; // 0xa0
	private static DelegateBridge __Hotfix0_OnIngredientJumpBtnPressed; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public override IStateCacheHandler cacheHandler { get; }

	// RVA: 0x3d69718 VA: 0x7596381718
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d69780 VA: 0x7596381780
	private Void _InitTopMenu() { }
	// RVA: 0x3d69844 VA: 0x7596381844
	public override IStateCacheHandler get_cacheHandler() { }
	// RVA: 0x3d69980 VA: 0x7596381980
	private Void _LoadFromRuntime(BuildingWorkshopModel model) { }
	// RVA: 0x3d69a38 VA: 0x7596381a38
	protected override Void OnEnter() { }
	// RVA: 0x3d6a014 VA: 0x7596382014
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3d6a18c VA: 0x759638218c
	protected override Void OnResume() { }
	// RVA: 0x3d6a22c VA: 0x759638222c
	private Void OnDestroy() { }
	// RVA: 0x3d6a32c VA: 0x759638232c
	private Void _OnPlayerDataChanged() { }
	// RVA: 0x3d6a3a0 VA: 0x75963823a0
	private Void _SetWorkCount(Int32 count) { }
	// RVA: 0x3d6a4a0 VA: 0x75963824a0
	public Void OnCharacterButtonPressed() { }
	// RVA: 0x3d6a558 VA: 0x7596382558
	public Void OnFormulaButtonPressed() { }
	// RVA: 0x3d6a664 VA: 0x7596382664
	public Void OnAddButtonPressed() { }
	// RVA: 0x3d6a6e0 VA: 0x75963826e0
	public Void OnMinusButtonPressed() { }
	// RVA: 0x3d6a75c VA: 0x759638275c
	public Void OnMaxButtonPressed() { }
	// RVA: 0x3d6a81c VA: 0x759638281c
	public Void OnMinButtonPressed() { }
	// RVA: 0x3d6a888 VA: 0x7596382888
	public Void OnProtectSwitchButtonPressed() { }
	// RVA: 0x3d6a928 VA: 0x7596382928
	private Void _HandleWorkshopResult(WorkResult workResult) { }
	// RVA: 0x3d6ac14 VA: 0x7596382c14
	private Void _ShowOKDialog(String content, Action okAction) { }
	// RVA: 0x3d6ad74 VA: 0x7596382d74
	public Void OnConfirmButtonPressed() { }
	// RVA: 0x3d6af48 VA: 0x7596382f48
	public Void OnPrevFormulaButtonPressed() { }
	// RVA: 0x3d6b14c VA: 0x759638314c
	public Void OnIngredientJumpBtnPressed(Int32 index) { }
	// RVA: 0x3d6b574 VA: 0x7596383574
	public Void .ctor() { }
	// RVA: 0x3d6b5e4 VA: 0x75963835e4
	private Void <_InitTopMenu>b__4_0(GameObject obj) { }
	// RVA: 0x3d6b6a8 VA: 0x75963836a8
	private Void <_InitTopMenu>b__4_1() { }
	// RVA: 0x3d6b6c8 VA: 0x75963836c8
	private Void <RegisterToDataListener>b__10_0(IStateBean stateBean) { }
	// RVA: 0x3d6b790 VA: 0x7596383790
	private Void <_HandleWorkshopResult>b__22_0() { }
	// RVA: 0x3d6b7ac VA: 0x75963837ac
	private IStateCacheHandler <>xLuaBaseProxy_get_cacheHandler() { }
	// RVA: 0x3d6b7b4 VA: 0x75963837b4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d6b7bc VA: 0x75963837bc
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3d6b7c4 VA: 0x75963837c4
	private Void <>xLuaBaseProxy_OnResume() { }
}
```