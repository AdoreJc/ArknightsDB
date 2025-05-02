# SandboxV2DungeonCrossDayModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <topicId>k__BackingField`

- `Boolean <isSettleDate>k__BackingField`

- `SandboxV2DungeonCrossDayViewStatus <viewStatus>k__BackingField`

- `Boolean <showSupplyPanel>k__BackingField`

- `SandboxV2DungeonCrossDaySettleCalcModel <settleCalcModel>k__BackingField`

- `SandboxV2DungeonCrossDayDailyModel <dailyModel>k__BackingField`

- `SandboxV2DungeonCrossDaySupplyModel <supplyModel>k__BackingField`


## Properties

- `String topicId`

- `Boolean isSettleDate`

- `SandboxV2DungeonCrossDayViewStatus viewStatus`

- `Boolean showSupplyPanel`

- `SandboxV2DungeonCrossDaySettleCalcModel settleCalcModel`

- `SandboxV2DungeonCrossDayDailyModel dailyModel`

- `SandboxV2DungeonCrossDaySupplyModel supplyModel`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `Boolean get_isSettleDate()`

- `Void set_isSettleDate(Boolean)`

- `SandboxV2DungeonCrossDayViewStatus get_viewStatus()`

- `Void set_viewStatus(SandboxV2DungeonCrossDayViewStatus)`

- `Boolean get_showSupplyPanel()`

- `Void set_showSupplyPanel(Boolean)`

- `SandboxV2DungeonCrossDaySettleCalcModel get_settleCalcModel()`

- `Void set_settleCalcModel(SandboxV2DungeonCrossDaySettleCalcModel)`

- `SandboxV2DungeonCrossDayDailyModel get_dailyModel()`

- `Void set_dailyModel(SandboxV2DungeonCrossDayDailyModel)`

- `SandboxV2DungeonCrossDaySupplyModel get_supplyModel()`

- `Void set_supplyModel(SandboxV2DungeonCrossDaySupplyModel)`

- `Void LoadData(String, Boolean)`

- `Void RefreshData()`

- `Void RefreshViewStatus(SandboxV2DungeonCrossDayViewStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCrossDayModel : IHotfixable
{
	private String <topicId>k__BackingField; // 0x10
	private Boolean <isSettleDate>k__BackingField; // 0x18
	private SandboxV2DungeonCrossDayViewStatus <viewStatus>k__BackingField; // 0x1c
	private Boolean <showSupplyPanel>k__BackingField; // 0x20
	private SandboxV2DungeonCrossDaySettleCalcModel <settleCalcModel>k__BackingField; // 0x28
	private SandboxV2DungeonCrossDayDailyModel <dailyModel>k__BackingField; // 0x30
	private SandboxV2DungeonCrossDaySupplyModel <supplyModel>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_isSettleDate; // 0x10
	private static DelegateBridge __Hotfix0_set_isSettleDate; // 0x18
	private static DelegateBridge __Hotfix0_get_viewStatus; // 0x20
	private static DelegateBridge __Hotfix0_set_viewStatus; // 0x28
	private static DelegateBridge __Hotfix0_get_showSupplyPanel; // 0x30
	private static DelegateBridge __Hotfix0_set_showSupplyPanel; // 0x38
	private static DelegateBridge __Hotfix0_get_settleCalcModel; // 0x40
	private static DelegateBridge __Hotfix0_set_settleCalcModel; // 0x48
	private static DelegateBridge __Hotfix0_get_dailyModel; // 0x50
	private static DelegateBridge __Hotfix0_set_dailyModel; // 0x58
	private static DelegateBridge __Hotfix0_get_supplyModel; // 0x60
	private static DelegateBridge __Hotfix0_set_supplyModel; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x70
	private static DelegateBridge __Hotfix0_RefreshData; // 0x78
	private static DelegateBridge __Hotfix0_RefreshViewStatus; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public String topicId { get; set; }
	public Boolean isSettleDate { get; set; }
	public SandboxV2DungeonCrossDayViewStatus viewStatus { get; set; }
	public Boolean showSupplyPanel { get; set; }
	public SandboxV2DungeonCrossDaySettleCalcModel settleCalcModel { get; set; }
	public SandboxV2DungeonCrossDayDailyModel dailyModel { get; set; }
	public SandboxV2DungeonCrossDaySupplyModel supplyModel { get; set; }

	// RVA: 0x25235b0 VA: 0x7594b3b5b0
	public String get_topicId() { }
	// RVA: 0x25238d0 VA: 0x7594b3b8d0
	private Void set_topicId(String value) { }
	// RVA: 0x2523618 VA: 0x7594b3b618
	public Boolean get_isSettleDate() { }
	// RVA: 0x2523954 VA: 0x7594b3b954
	private Void set_isSettleDate(Boolean value) { }
	// RVA: 0x25239d4 VA: 0x7594b3b9d4
	public SandboxV2DungeonCrossDayViewStatus get_viewStatus() { }
	// RVA: 0x2523a3c VA: 0x7594b3ba3c
	private Void set_viewStatus(SandboxV2DungeonCrossDayViewStatus value) { }
	// RVA: 0x2523ab8 VA: 0x7594b3bab8
	public Boolean get_showSupplyPanel() { }
	// RVA: 0x2523b20 VA: 0x7594b3bb20
	private Void set_showSupplyPanel(Boolean value) { }
	// RVA: 0x25236fc VA: 0x7594b3b6fc
	public SandboxV2DungeonCrossDaySettleCalcModel get_settleCalcModel() { }
	// RVA: 0x2523ba0 VA: 0x7594b3bba0
	private Void set_settleCalcModel(SandboxV2DungeonCrossDaySettleCalcModel value) { }
	// RVA: 0x2523c24 VA: 0x7594b3bc24
	public SandboxV2DungeonCrossDayDailyModel get_dailyModel() { }
	// RVA: 0x2523c8c VA: 0x7594b3bc8c
	private Void set_dailyModel(SandboxV2DungeonCrossDayDailyModel value) { }
	// RVA: 0x2523d10 VA: 0x7594b3bd10
	public SandboxV2DungeonCrossDaySupplyModel get_supplyModel() { }
	// RVA: 0x2523d78 VA: 0x7594b3bd78
	private Void set_supplyModel(SandboxV2DungeonCrossDaySupplyModel value) { }
	// RVA: 0x2522f20 VA: 0x7594b3af20
	public Void LoadData(String topic, Boolean needShowSettleCalc) { }
	// RVA: 0x2523288 VA: 0x7594b3b288
	public Void RefreshData() { }
	// RVA: 0x2523530 VA: 0x7594b3b530
	public Void RefreshViewStatus(SandboxV2DungeonCrossDayViewStatus status) { }
	// RVA: 0x2524cf8 VA: 0x7594b3ccf8
	public Void .ctor() { }
}
```