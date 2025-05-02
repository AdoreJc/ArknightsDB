# SHomeStateBean

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `SRoomGroupViewProperty roomGroupProperty`

- `SRoomViewProperty selectedRoomProperty`


## Properties

- `String selectedSlotId`


## Methods

- `Void Tick()`

- `String get_selectedSlotId()`

- `Void SetSelectedSlot(String)`

- `Void InitData()`

- `Void UpdateData()`

- `Void EditChangeFormula(SStockViewModel, ShopFormula)`

- `Void EditChangeCount(SStockViewModel, Int32)`

- `Void CancelEdit(Int32)`

- `Boolean CheckConfirmEdit(Int32, out)`

- `Boolean CheckIfCanHarvest()`

- `Void _OnCountDownTimeout()`

- `Boolean _CheckTabTrackPoint(PlayerBuildingShop)`

- `Void _UpdateStocks(SRoomViewModel)`

- `Void _UpdateEditInfo(Int32)`

- `Void _ResetEdit(Int32[])`

- `Void _UpdateCountDowns()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class SHomeStateBean : IStateBean, IHotfixable
{
	private readonly Int32[] ALL_STOCK_INDEXES; // 0x10
	public SRoomGroupViewProperty roomGroupProperty; // 0x18
	public SRoomViewProperty selectedRoomProperty; // 0x20
	public SStockViewProperty[] stockSlotProperties; // 0x28
	private CountDownTask[] m_countDowns; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Tick; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedSlotId; // 0x10
	private static DelegateBridge __Hotfix0_SetSelectedSlot; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x20
	private static DelegateBridge __Hotfix0_UpdateData; // 0x28
	private static DelegateBridge __Hotfix0_EditChangeFormula; // 0x30
	private static DelegateBridge __Hotfix0_EditChangeCount; // 0x38
	private static DelegateBridge __Hotfix0_CancelEdit; // 0x40
	private static DelegateBridge __Hotfix0_CheckConfirmEdit; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfCanHarvest; // 0x50
	private static DelegateBridge __Hotfix0__OnCountDownTimeout; // 0x58
	private static DelegateBridge __Hotfix0__CheckTabTrackPoint; // 0x60
	private static DelegateBridge __Hotfix0__UpdateStocks; // 0x68
	private static DelegateBridge __Hotfix0__UpdateEditInfo; // 0x70
	private static DelegateBridge __Hotfix0__ResetEdit; // 0x78
	private static DelegateBridge __Hotfix0__UpdateCountDowns; // 0x80

	public String selectedSlotId { get; }

	// RVA: 0x3db8c14 VA: 0x75963d0c14
	public Void .ctor() { }
	// RVA: 0x3db8e70 VA: 0x75963d0e70
	public Void Tick() { }
	// RVA: 0x3db8f2c VA: 0x75963d0f2c
	public String get_selectedSlotId() { }
	// RVA: 0x3db8fd8 VA: 0x75963d0fd8
	public Void SetSelectedSlot(String slotId) { }
	// RVA: 0x3db9620 VA: 0x75963d1620
	public Void InitData() { }
	// RVA: 0x3db9c88 VA: 0x75963d1c88
	public Void UpdateData() { }
	// RVA: 0x3db9f00 VA: 0x75963d1f00
	public Void EditChangeFormula(SStockViewModel stockModel, ShopFormula formula) { }
	// RVA: 0x3dba3cc VA: 0x75963d23cc
	public Void EditChangeCount(SStockViewModel stockModel, Int32 delta) { }
	// RVA: 0x3dba4cc VA: 0x75963d24cc
	public Void CancelEdit(Int32 stockIndex) { }
	// RVA: 0x3dba584 VA: 0x75963d2584
	public Boolean CheckConfirmEdit(Int32 stockIndex, out String errorInfo) { }
	// RVA: 0x3dba888 VA: 0x75963d2888
	public Boolean CheckIfCanHarvest() { }
	// RVA: 0x3dba92c VA: 0x75963d292c
	private Void _OnCountDownTimeout() { }
	// RVA: 0x3db9b28 VA: 0x75963d1b28
	private Boolean _CheckTabTrackPoint(PlayerBuildingShop shop) { }
	// RVA: 0x3db92b4 VA: 0x75963d12b4
	private Void _UpdateStocks(SRoomViewModel selectedRoom) { }
	// RVA: 0x3dba0f4 VA: 0x75963d20f4
	private Void _UpdateEditInfo(Int32 stockIndex) { }
	// RVA: 0x3db915c VA: 0x75963d115c
	private Void _ResetEdit(Int32[] indexes) { }
	// RVA: 0x3db94c8 VA: 0x75963d14c8
	private Void _UpdateCountDowns() { }
}
```