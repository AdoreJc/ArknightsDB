# BuildingLaborViewModel

**Namespace:** `Torappu.Building`


## Fields

- `Int64 m_laborRecoverPoint`

- `DateTime m_lastServiceTime`

- `Int32 m_lastServiceLabor`

- `Double m_lastProcessPoint`

- `CountDownTask m_countDown`

- `Int32 <maxLabor>k__BackingField`

- `Single <buffSpeed>k__BackingField`

- `Int32 <currentLabor>k__BackingField`


## Properties

- `Int32 maxLabor`

- `Single buffSpeed`

- `Boolean isLaborFull`

- `Int64 remainSeconds`

- `Single totalRemainSeconds`

- `Single progress`

- `Int32 currentLabor`


## Methods

- `Int32 get_maxLabor()`

- `Void set_maxLabor(Int32)`

- `Single get_buffSpeed()`

- `Void set_buffSpeed(Single)`

- `Boolean get_isLaborFull()`

- `Int64 get_remainSeconds()`

- `Single get_totalRemainSeconds()`

- `Single get_progress()`

- `Int32 get_currentLabor()`

- `Void set_currentLabor(Int32)`

- `Void Tick()`

- `Void LoadData()`

- `Void _UpdateStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingLaborViewModel : IHotfixable
{
	private Int64 m_laborRecoverPoint; // 0x10
	private DateTime m_lastServiceTime; // 0x18
	private Int32 m_lastServiceLabor; // 0x20
	private Double m_lastProcessPoint; // 0x28
	private CountDownTask m_countDown; // 0x30
	private Int32 <maxLabor>k__BackingField; // 0x38
	private Single <buffSpeed>k__BackingField; // 0x3c
	private Int32 <currentLabor>k__BackingField; // 0x40
	public Action`1 onValueTick; // 0x48
	public Action`1 onValueChanged; // 0x50
	private static DelegateBridge __Hotfix0_get_maxLabor; // 0x0
	private static DelegateBridge __Hotfix0_set_maxLabor; // 0x8
	private static DelegateBridge __Hotfix0_get_buffSpeed; // 0x10
	private static DelegateBridge __Hotfix0_set_buffSpeed; // 0x18
	private static DelegateBridge __Hotfix0_get_isLaborFull; // 0x20
	private static DelegateBridge __Hotfix0_get_remainSeconds; // 0x28
	private static DelegateBridge __Hotfix0_get_totalRemainSeconds; // 0x30
	private static DelegateBridge __Hotfix0_get_progress; // 0x38
	private static DelegateBridge __Hotfix0_get_currentLabor; // 0x40
	private static DelegateBridge __Hotfix0_set_currentLabor; // 0x48
	private static DelegateBridge __Hotfix0_Tick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0__UpdateStatus; // 0x68

	public Int32 maxLabor { get; set; }
	public Single buffSpeed { get; set; }
	public Boolean isLaborFull { get; }
	public Int64 remainSeconds { get; }
	public Single totalRemainSeconds { get; }
	public Single progress { get; }
	public Int32 currentLabor { get; set; }

	// RVA: 0x3788d54 VA: 0x7595da0d54
	public Int32 get_maxLabor() { }
	// RVA: 0x3788dbc VA: 0x7595da0dbc
	private Void set_maxLabor(Int32 value) { }
	// RVA: 0x3788e38 VA: 0x7595da0e38
	public Single get_buffSpeed() { }
	// RVA: 0x3788ea0 VA: 0x7595da0ea0
	private Void set_buffSpeed(Single value) { }
	// RVA: 0x3788f1c VA: 0x7595da0f1c
	public Boolean get_isLaborFull() { }
	// RVA: 0x3789004 VA: 0x7595da1004
	public Int64 get_remainSeconds() { }
	// RVA: 0x3789078 VA: 0x7595da1078
	public Single get_totalRemainSeconds() { }
	// RVA: 0x37891c4 VA: 0x7595da11c4
	public Single get_progress() { }
	// RVA: 0x3788f9c VA: 0x7595da0f9c
	public Int32 get_currentLabor() { }
	// RVA: 0x3789284 VA: 0x7595da1284
	private Void set_currentLabor(Int32 value) { }
	// RVA: 0x3789300 VA: 0x7595da1300
	public Void Tick() { }
	// RVA: 0x3789374 VA: 0x7595da1374
	public Void .ctor() { }
	// RVA: 0x37894f4 VA: 0x7595da14f4
	public Void LoadData() { }
	// RVA: 0x3789708 VA: 0x7595da1708
	private Void _UpdateStatus() { }
	// RVA: 0x378996c VA: 0x7595da196c
	private Void <.ctor>b__28_0(TickValue _) { }
	// RVA: 0x378998c VA: 0x7595da198c
	private Void <.ctor>b__28_1() { }
}
```