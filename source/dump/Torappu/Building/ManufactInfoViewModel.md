# ManufactInfoViewModel

**Namespace:** `Torappu.Building`


## Fields

- `ManufactSnapshot serviceSnapshot`

- `Single baseSpeed`

- `Single buffSpeed`

- `Single baseBuffSpeed`

- `Single specBuffSpeed`

- `Single secPerItem`

- `Int32 maxProductWeight`

- `Int64 mpCostPerHourBase`

- `Int64 mpCostPerHourBaseBuff`

- `Int64 mpCostPerHourSpecBuff`

- `ManufactFormula formula`

- `Boolean isWorking`

- `Int32 maxChars`

- `Int32 finalMaxChars`

- `Int32 stationedNum`


## Properties

- `Int64 totalSavedSeconds`


## Methods

- `Void LoadData(RoomSlotModel, PlayerBuildingManufacture)`

- `Int64 get_totalSavedSeconds()`

- `ManufactSnapshot CurrentSnapshot(Int32)`

- `ManufactSnapshot _CreateSnapshot(DateTime, Int32)`

- `Boolean CheckIfCanHarvest()`

- `Boolean CheckIfOverloaded()`

- `ManufactSnapshot UpdateCountDownForManufact(Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class ManufactInfoViewModel : IHotfixable
{
	public ManufactSnapshot serviceSnapshot; // 0x10
	public Single baseSpeed; // 0x50
	public Single buffSpeed; // 0x54
	public Single baseBuffSpeed; // 0x58
	public Single specBuffSpeed; // 0x5c
	public Single secPerItem; // 0x60
	public Int32 maxProductWeight; // 0x64
	public Int64 mpCostPerHourBase; // 0x68
	public Int64 mpCostPerHourBaseBuff; // 0x70
	public Int64 mpCostPerHourSpecBuff; // 0x78
	public ManufactFormula formula; // 0x80
	public Boolean isWorking; // 0x88
	public Int32 maxChars; // 0x8c
	public Int32 finalMaxChars; // 0x90
	public BuildingCharModel[] chars; // 0x98
	public Int32 stationedNum; // 0xa0
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_get_totalSavedSeconds; // 0x8
	private static DelegateBridge __Hotfix0_CurrentSnapshot; // 0x10
	private static DelegateBridge __Hotfix0__CreateSnapshot; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfCanHarvest; // 0x20
	private static DelegateBridge __Hotfix0_CheckIfOverloaded; // 0x28
	private static DelegateBridge __Hotfix0_UpdateCountDownForManufact; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int64 totalSavedSeconds { get; }

	// RVA: 0x3798698 VA: 0x7595db0698
	public Void LoadData(RoomSlotModel slotModel, PlayerBuildingManufacture playerData) { }
	// RVA: 0x3798fac VA: 0x7595db0fac
	public Int64 get_totalSavedSeconds() { }
	// RVA: 0x3799160 VA: 0x7595db1160
	public ManufactSnapshot CurrentSnapshot(Int32 additionalBasePoint) { }
	// RVA: 0x3799238 VA: 0x7595db1238
	private ManufactSnapshot _CreateSnapshot(DateTime targetTime, Int32 addBasePoint) { }
	// RVA: 0x379981c VA: 0x7595db181c
	public Boolean CheckIfCanHarvest() { }
	// RVA: 0x37998a8 VA: 0x7595db18a8
	public Boolean CheckIfOverloaded() { }
	// RVA: 0x37999b8 VA: 0x7595db19b8
	public ManufactSnapshot UpdateCountDownForManufact(Action`2 countdownHandler) { }
	// RVA: 0x3799b2c VA: 0x7595db1b2c
	public Void .ctor() { }
}
```