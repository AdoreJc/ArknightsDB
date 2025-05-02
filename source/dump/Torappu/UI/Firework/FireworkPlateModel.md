# FireworkPlateModel

**Namespace:** `Torappu.UI.Firework`


## Fields

- `PlateContentModel availablePlateContentModel`

- `PlateContentModel filledPlateContentModel`

- `Int32 filledPlateRank`

- `Int32 plateRowCount`

- `Boolean judgeSucceed`

- `Boolean isSucceed`

- `Int32 loadSequenceNum`


## Methods

- `Void LoadData(LoadParam)`

- `Void ReloadSlots(IList`1)`

- `FireworkPlateSlotType GetSlotType(GridPosition)`

- `Boolean IsAllEquipPlateValid()`

- `Boolean IsLastPlateValid(PlateContentModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework
public class FireworkPlateModel : IHotfixable
{
	public PlateContentModel availablePlateContentModel; // 0x10
	public PlateContentModel filledPlateContentModel; // 0x18
	public Int32 filledPlateRank; // 0x20
	public Int32 plateRowCount; // 0x24
	public Boolean judgeSucceed; // 0x28
	public Boolean isSucceed; // 0x29
	public Int32 loadSequenceNum; // 0x2c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_ReloadSlots; // 0x8
	private static DelegateBridge __Hotfix0_GetSlotType; // 0x10
	private static DelegateBridge __Hotfix0_IsAllEquipPlateValid; // 0x18
	private static DelegateBridge __Hotfix0_IsLastPlateValid; // 0x20
	private static DelegateBridge __Hotfix0_IterAllGrids; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x28ee0d4 VA: 0x7594f060d4
	public Void LoadData(LoadParam loadParam) { }
	// RVA: 0x28eec4c VA: 0x7594f06c4c
	public Void ReloadSlots(IList`1 filledPlatePieceList) { }
	// RVA: 0x28ebbc4 VA: 0x7594f03bc4
	public FireworkPlateSlotType GetSlotType(GridPosition slotPos) { }
	// RVA: 0x28ef2a0 VA: 0x7594f072a0
	public Boolean IsAllEquipPlateValid() { }
	// RVA: 0x28ef16c VA: 0x7594f0716c
	public Boolean IsLastPlateValid(PlateContentModel lastFilledPlate) { }
	// RVA: 0x28f0e94 VA: 0x7594f08e94
	public IEnumerable`1 IterAllGrids() { }
	// RVA: 0x28ee004 VA: 0x7594f06004
	public Void .ctor() { }
}
```