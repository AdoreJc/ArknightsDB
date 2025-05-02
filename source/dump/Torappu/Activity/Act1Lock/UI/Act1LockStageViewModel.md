# Act1LockStageViewModel

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `String stageId`

- `StageAdditionData additionData`

- `StageViewModel normalStageViewModel`

- `Int32 assistCount`

- `Boolean useSpAssist`


## Properties

- `Int32 interlockCount`

- `Int32 totalApCost`


## Methods

- `Int32 get_interlockCount()`

- `Int32 get_totalApCost()`

- `Void LoadStageData(String)`

- `Void RefreshData()`

- `Void _UpdateInterLockData()`

- `Void _UpdateFinalStageData()`

- `Void _UpdateInterlockList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockStageViewModel : IHotfixable
{
	public String stageId; // 0x10
	public StageAdditionData additionData; // 0x18
	public StageViewModel normalStageViewModel; // 0x20
	public Int32 assistCount; // 0x28
	public Boolean useSpAssist; // 0x2c
	public List`1 interlockSquadList; // 0x30
	private static DelegateBridge __Hotfix0_get_interlockCount; // 0x0
	private static DelegateBridge __Hotfix0_get_totalApCost; // 0x8
	private static DelegateBridge __Hotfix0_LoadStageData; // 0x10
	private static DelegateBridge __Hotfix0_RefreshData; // 0x18
	private static DelegateBridge __Hotfix0__UpdateInterLockData; // 0x20
	private static DelegateBridge __Hotfix0__UpdateFinalStageData; // 0x28
	private static DelegateBridge __Hotfix0__UpdateInterlockList; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 interlockCount { get; }
	public Int32 totalApCost { get; }

	// RVA: 0x33da2cc VA: 0x75959f22cc
	public Int32 get_interlockCount() { }
	// RVA: 0x33da3d0 VA: 0x75959f23d0
	public Int32 get_totalApCost() { }
	// RVA: 0x33da0ac VA: 0x75959f20ac
	public Void LoadStageData(String stageid) { }
	// RVA: 0x33d9bac VA: 0x75959f1bac
	public Void RefreshData() { }
	// RVA: 0x33da464 VA: 0x75959f2464
	private Void _UpdateInterLockData() { }
	// RVA: 0x33da578 VA: 0x75959f2578
	private Void _UpdateFinalStageData() { }
	// RVA: 0x33da940 VA: 0x75959f2940
	private Void _UpdateInterlockList() { }
	// RVA: 0x33d9ffc VA: 0x75959f1ffc
	public Void .ctor() { }
}
```