# MHomeStateBean

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `MRoomGroupViewProperty roomGroupProperty`

- `MRoomViewPropety selectedRoomProperty`

- `CountDownTask m_countDown`


## Properties

- `String selectedSlotId`


## Methods

- `Void Tick()`

- `String get_selectedSlotId()`

- `Void SetSelectedSlot(String)`

- `Void InitData()`

- `Void UpdateData()`

- `Void EditChangeFormula(ManufactFormula)`

- `Void EditChangeCount(Int32)`

- `Void CancelEdit()`

- `Boolean CheckConfirmEdit(out)`

- `Boolean CheckIfCanHarest()`

- `Boolean CheckIfCanLaborAccel()`

- `Boolean CheckIfRemainTimeEnough(DateTime)`

- `Void _OnCountDownTimeout()`

- `Void _ResetEdit(MRoomViewModel)`

- `Void _UpdateEditInfo()`

- `Void _UpdateNormalInputSlots(MRoomViewModel)`

- `Void _UpdateCountDown()`

- `Void <_UpdateCountDown>b__21_0(Boolean, ManufactSnapshot)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class MHomeStateBean : IStateBean, IHotfixable
{
	public MRoomGroupViewProperty roomGroupProperty; // 0x10
	public MRoomViewPropety selectedRoomProperty; // 0x18
	public MItemInputSlotProperty[] inputSlotProperties; // 0x20
	private CountDownTask m_countDown; // 0x28
	private static DelegateBridge __Hotfix0_Tick; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedSlotId; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedSlot; // 0x10
	private static DelegateBridge __Hotfix0_InitData; // 0x18
	private static DelegateBridge __Hotfix0_UpdateData; // 0x20
	private static DelegateBridge __Hotfix0_EditChangeFormula; // 0x28
	private static DelegateBridge __Hotfix0_EditChangeCount; // 0x30
	private static DelegateBridge __Hotfix0_CancelEdit; // 0x38
	private static DelegateBridge __Hotfix0_CheckConfirmEdit; // 0x40
	private static DelegateBridge __Hotfix0_CheckIfCanHarest; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfCanLaborAccel; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfRemainTimeEnough; // 0x58
	private static DelegateBridge __Hotfix0__OnCountDownTimeout; // 0x60
	private static DelegateBridge __Hotfix0__ResetEdit; // 0x68
	private static DelegateBridge __Hotfix0__UpdateEditInfo; // 0x70
	private static DelegateBridge __Hotfix0__UpdateNormalInputSlots; // 0x78
	private static DelegateBridge __Hotfix0__UpdateCountDown; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public String selectedSlotId { get; }

	// RVA: 0x3e02410 VA: 0x759641a410
	public Void Tick() { }
	// RVA: 0x3e0248c VA: 0x759641a48c
	public String get_selectedSlotId() { }
	// RVA: 0x3e0251c VA: 0x759641a51c
	public Void SetSelectedSlot(String slotId) { }
	// RVA: 0x3e02c64 VA: 0x759641ac64
	public Void InitData() { }
	// RVA: 0x3e0330c VA: 0x759641b30c
	public Void UpdateData() { }
	// RVA: 0x3e03b68 VA: 0x759641bb68
	public Void EditChangeFormula(ManufactFormula formula) { }
	// RVA: 0x3e03c3c VA: 0x759641bc3c
	public Void EditChangeCount(Int32 delta) { }
	// RVA: 0x3e03d08 VA: 0x759641bd08
	public Void CancelEdit() { }
	// RVA: 0x3e03e54 VA: 0x759641be54
	public Boolean CheckConfirmEdit(out String errorInfo) { }
	// RVA: 0x3e04170 VA: 0x759641c170
	public Boolean CheckIfCanHarest() { }
	// RVA: 0x3e04210 VA: 0x759641c210
	public Boolean CheckIfCanLaborAccel() { }
	// RVA: 0x3e042ac VA: 0x759641c2ac
	public Boolean CheckIfRemainTimeEnough(DateTime currentTime) { }
	// RVA: 0x3e04494 VA: 0x759641c494
	private Void _OnCountDownTimeout() { }
	// RVA: 0x3e03dc0 VA: 0x759641bdc0
	private Void _ResetEdit(MRoomViewModel selectedRoom) { }
	// RVA: 0x3e035e0 VA: 0x759641b5e0
	private Void _UpdateEditInfo() { }
	// RVA: 0x3e027b0 VA: 0x759641a7b0
	private Void _UpdateNormalInputSlots(MRoomViewModel selectedModel) { }
	// RVA: 0x3e02b54 VA: 0x759641ab54
	private Void _UpdateCountDown() { }
	// RVA: 0x3e04564 VA: 0x759641c564
	public Void .ctor() { }
	// RVA: 0x3e04720 VA: 0x759641c720
	private Void <_UpdateCountDown>b__21_0(Boolean shouldCountDown, ManufactSnapshot snapshotParam) { }
}
```