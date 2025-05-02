# VecBreakDefenseBattleFinishViewModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `VecBreakDefenseStageViewModel stageViewModel`

- `Boolean showDialog`

- `String dialogText`

- `String toastText`

- `Boolean battlePassed`


## Properties

- `String actId`

- `String stageId`


## Methods

- `String get_actId()`

- `String get_stageId()`

- `Void LoadData()`

- `Boolean _CheckIfOpenDialog()`

- `Boolean _CheckIfCharInDefend(DefendCharModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseBattleFinishViewModel : IHotfixable
{
	public VecBreakDefenseStageViewModel stageViewModel; // 0x10
	public Boolean showDialog; // 0x18
	public List`1 newSquad; // 0x20
	public String dialogText; // 0x28
	public String toastText; // 0x30
	public Boolean battlePassed; // 0x38
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_stageId; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0__CheckIfOpenDialog; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfCharInDefend; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String actId { get; }
	public String stageId { get; }

	// RVA: 0x22c91e8 VA: 0x75948e11e8
	public String get_actId() { }
	// RVA: 0x22c925c VA: 0x75948e125c
	public String get_stageId() { }
	// RVA: 0x22c8ab4 VA: 0x75948e0ab4
	public Void LoadData() { }
	// RVA: 0x22c9f08 VA: 0x75948e1f08
	private Boolean _CheckIfOpenDialog() { }
	// RVA: 0x22ca114 VA: 0x75948e2114
	private Boolean _CheckIfCharInDefend(DefendCharModel squadChar) { }
	// RVA: 0x22c93b8 VA: 0x75948e13b8
	public Void .ctor() { }
}
```