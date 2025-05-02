# BuildingWorkshopFormulaState

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `BuildingWorkshopFormulaView _formulaView`

- `StateBean m_stateBean`

- `BuildingWorkshopFormulaProperty m_viewProperty`

- `BuildingWorkshopFormulaViewModel m_formularViewModel`

- `Boolean m_isInited`


## Methods

- `Void Start()`

- `Void _InitIfNot()`

- `Void _OnFormulaClicked(IWorkshopFormula)`

- `Void OnFilterBuildingButtonPressed()`

- `Void OnFilterEliteButtonPressed()`

- `Void OnFilterSkillButtonPressed()`

- `Void OnFilterAscButtonPressed()`

- `Void OnFilterFurnitureButtonPressed()`

- `Void OnRarityFilterGroupBtnPressed()`

- `Void OnSortRarityButtonPressed()`

- `Void OnSortPriceButtonPressed()`

- `Void OnSortIdButtonPressed()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void <Start>b__9_0(GameObject)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopFormulaState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 MSG_FILTER_CLICK; // 0x0
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x70
	private BuildingWorkshopFormulaView _formulaView; // 0x78
	private StateBean m_stateBean; // 0x80
	private BuildingWorkshopFormulaProperty m_viewProperty; // 0x88
	private BuildingWorkshopFormulaViewModel m_formularViewModel; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0__OnFormulaClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnFilterBuildingButtonPressed; // 0x30
	private static DelegateBridge __Hotfix0_OnFilterEliteButtonPressed; // 0x38
	private static DelegateBridge __Hotfix0_OnFilterSkillButtonPressed; // 0x40
	private static DelegateBridge __Hotfix0_OnFilterAscButtonPressed; // 0x48
	private static DelegateBridge __Hotfix0_OnFilterFurnitureButtonPressed; // 0x50
	private static DelegateBridge __Hotfix0_OnRarityFilterGroupBtnPressed; // 0x58
	private static DelegateBridge __Hotfix0_OnSortRarityButtonPressed; // 0x60
	private static DelegateBridge __Hotfix0_OnSortPriceButtonPressed; // 0x68
	private static DelegateBridge __Hotfix0_OnSortIdButtonPressed; // 0x70
	private static DelegateBridge __Hotfix0_OnMessage; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x3d685e0 VA: 0x75963805e0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d68648 VA: 0x7596380648
	private Void Start() { }
	// RVA: 0x3d6870c VA: 0x759638070c
	private Void _InitIfNot() { }
	// RVA: 0x3d688f8 VA: 0x75963808f8
	protected override Void OnEnter() { }
	// RVA: 0x3d689b8 VA: 0x75963809b8
	protected override Void OnResume() { }
	// RVA: 0x3d68b28 VA: 0x7596380b28
	private Void _OnFormulaClicked(IWorkshopFormula formula) { }
	// RVA: 0x3d68cfc VA: 0x7596380cfc
	public Void OnFilterBuildingButtonPressed() { }
	// RVA: 0x3d68db8 VA: 0x7596380db8
	public Void OnFilterEliteButtonPressed() { }
	// RVA: 0x3d68e78 VA: 0x7596380e78
	public Void OnFilterSkillButtonPressed() { }
	// RVA: 0x3d68f38 VA: 0x7596380f38
	public Void OnFilterAscButtonPressed() { }
	// RVA: 0x3d68ff8 VA: 0x7596380ff8
	public Void OnFilterFurnitureButtonPressed() { }
	// RVA: 0x3d690b8 VA: 0x75963810b8
	public Void OnRarityFilterGroupBtnPressed() { }
	// RVA: 0x3d69174 VA: 0x7596381174
	public Void OnSortRarityButtonPressed() { }
	// RVA: 0x3d69240 VA: 0x7596381240
	public Void OnSortPriceButtonPressed() { }
	// RVA: 0x3d69310 VA: 0x7596381310
	public Void OnSortIdButtonPressed() { }
	// RVA: 0x3d693e0 VA: 0x75963813e0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3d694fc VA: 0x75963814fc
	public Void .ctor() { }
	// RVA: 0x3d69650 VA: 0x7596381650
	private Void <Start>b__9_0(GameObject obj) { }
	// RVA: 0x3d69708 VA: 0x7596381708
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d69710 VA: 0x7596381710
	private Void <>xLuaBaseProxy_OnResume() { }
}
```