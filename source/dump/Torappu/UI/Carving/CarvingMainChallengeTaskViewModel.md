# CarvingMainChallengeTaskViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Boolean <isActiveTask>k__BackingField`

- `Boolean <isTaskSuccess>k__BackingField`

- `Int32 <playerCoin>k__BackingField`

- `String <materialName>k__BackingField`

- `String <materialIconId>k__BackingField`

- `Int32 <materialNum>k__BackingField`

- `Int32 <passTaskCoin>k__BackingField`

- `String <taskDesc>k__BackingField`


## Properties

- `Boolean isActiveTask`

- `Boolean isTaskSuccess`

- `Int32 playerCoin`

- `String materialName`

- `String materialIconId`

- `Int32 materialNum`

- `Int32 passTaskCoin`

- `String taskDesc`


## Methods

- `Boolean get_isActiveTask()`

- `Void set_isActiveTask(Boolean)`

- `Boolean get_isTaskSuccess()`

- `Void set_isTaskSuccess(Boolean)`

- `Int32 get_playerCoin()`

- `Void set_playerCoin(Int32)`

- `String get_materialName()`

- `Void set_materialName(String)`

- `String get_materialIconId()`

- `Void set_materialIconId(String)`

- `Int32 get_materialNum()`

- `Void set_materialNum(Int32)`

- `Int32 get_passTaskCoin()`

- `Void set_passTaskCoin(Int32)`

- `String get_taskDesc()`

- `Void set_taskDesc(String)`

- `Void UpdateData(String)`

- `Void SetTaskFinishState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainChallengeTaskViewModel : IHotfixable
{
	private Boolean <isActiveTask>k__BackingField; // 0x10
	private Boolean <isTaskSuccess>k__BackingField; // 0x11
	private Int32 <playerCoin>k__BackingField; // 0x14
	private String <materialName>k__BackingField; // 0x18
	private String <materialIconId>k__BackingField; // 0x20
	private Int32 <materialNum>k__BackingField; // 0x28
	private Int32 <passTaskCoin>k__BackingField; // 0x2c
	private String <taskDesc>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_isActiveTask; // 0x0
	private static DelegateBridge __Hotfix0_set_isActiveTask; // 0x8
	private static DelegateBridge __Hotfix0_get_isTaskSuccess; // 0x10
	private static DelegateBridge __Hotfix0_set_isTaskSuccess; // 0x18
	private static DelegateBridge __Hotfix0_get_playerCoin; // 0x20
	private static DelegateBridge __Hotfix0_set_playerCoin; // 0x28
	private static DelegateBridge __Hotfix0_get_materialName; // 0x30
	private static DelegateBridge __Hotfix0_set_materialName; // 0x38
	private static DelegateBridge __Hotfix0_get_materialIconId; // 0x40
	private static DelegateBridge __Hotfix0_set_materialIconId; // 0x48
	private static DelegateBridge __Hotfix0_get_materialNum; // 0x50
	private static DelegateBridge __Hotfix0_set_materialNum; // 0x58
	private static DelegateBridge __Hotfix0_get_passTaskCoin; // 0x60
	private static DelegateBridge __Hotfix0_set_passTaskCoin; // 0x68
	private static DelegateBridge __Hotfix0_get_taskDesc; // 0x70
	private static DelegateBridge __Hotfix0_set_taskDesc; // 0x78
	private static DelegateBridge __Hotfix0_UpdateData; // 0x80
	private static DelegateBridge __Hotfix0_SetTaskFinishState; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Boolean isActiveTask { get; set; }
	public Boolean isTaskSuccess { get; set; }
	public Int32 playerCoin { get; set; }
	public String materialName { get; set; }
	public String materialIconId { get; set; }
	public Int32 materialNum { get; set; }
	public Int32 passTaskCoin { get; set; }
	public String taskDesc { get; set; }

	// RVA: 0x2dae558 VA: 0x75953c6558
	public Boolean get_isActiveTask() { }
	// RVA: 0x2daf058 VA: 0x75953c7058
	private Void set_isActiveTask(Boolean value) { }
	// RVA: 0x2daeef8 VA: 0x75953c6ef8
	public Boolean get_isTaskSuccess() { }
	// RVA: 0x2daf0d8 VA: 0x75953c70d8
	private Void set_isTaskSuccess(Boolean value) { }
	// RVA: 0x2dae4f0 VA: 0x75953c64f0
	public Int32 get_playerCoin() { }
	// RVA: 0x2daf158 VA: 0x75953c7158
	private Void set_playerCoin(Int32 value) { }
	// RVA: 0x2dae760 VA: 0x75953c6760
	public String get_materialName() { }
	// RVA: 0x2daf1d4 VA: 0x75953c71d4
	private Void set_materialName(String value) { }
	// RVA: 0x2dae628 VA: 0x75953c6628
	public String get_materialIconId() { }
	// RVA: 0x2daf258 VA: 0x75953c7258
	private Void set_materialIconId(String value) { }
	// RVA: 0x2dae6f8 VA: 0x75953c66f8
	public Int32 get_materialNum() { }
	// RVA: 0x2daf2dc VA: 0x75953c72dc
	private Void set_materialNum(Int32 value) { }
	// RVA: 0x2dae5c0 VA: 0x75953c65c0
	public Int32 get_passTaskCoin() { }
	// RVA: 0x2daf358 VA: 0x75953c7358
	private Void set_passTaskCoin(Int32 value) { }
	// RVA: 0x2dae690 VA: 0x75953c6690
	public String get_taskDesc() { }
	// RVA: 0x2daf3d4 VA: 0x75953c73d4
	private Void set_taskDesc(String value) { }
	// RVA: 0x2daf458 VA: 0x75953c7458
	public Void UpdateData(String actId) { }
	// RVA: 0x2daf69c VA: 0x75953c769c
	public Void SetTaskFinishState(Boolean isTaskFinished) { }
	// RVA: 0x2daf71c VA: 0x75953c771c
	public Void .ctor() { }
}
```