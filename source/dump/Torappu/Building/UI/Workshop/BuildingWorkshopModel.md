# BuildingWorkshopModel

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `RoomSlotModel m_roomSlotModel`

- `TargetItemInfo m_targetItemInfo`

- `StationaryCharacter m_cachedCharacter`

- `IWorkshopFormula m_currentFormula`

- `WRoomViewModel m_basicRoomModel`

- `BuildingWorkShopFormulaTree m_formulaTree`

- `Boolean <itemProtection>k__BackingField`


## Properties

- `IBasicRoomModel basicRoomModel`

- `String slotId`

- `IWorkshopFormula currentFormula`

- `IWorkshopStationaryCharacter stationaryCharacter`

- `Int32 extraOutcomeProbPercent`

- `Single additionalExtraOutcomeProbPercent`

- `Boolean itemProtection`

- `Int64 gold`


## Methods

- `IBasicRoomModel get_basicRoomModel()`

- `String get_slotId()`

- `IWorkshopFormula get_currentFormula()`

- `Void set_currentFormula(IWorkshopFormula)`

- `IWorkshopStationaryCharacter get_stationaryCharacter()`

- `Int32 get_extraOutcomeProbPercent()`

- `Single get_additionalExtraOutcomeProbPercent()`

- `Void LoadCurrentCharacter()`

- `Int32 MaxWorkCount(Int32, out)`

- `Int32 _MaxCountWithGold()`

- `Int32 _MaxCountWithMood(Int32)`

- `Boolean get_itemProtection()`

- `Void set_itemProtection(Boolean)`

- `Int64 get_gold()`

- `Int64 _GetSingleMoodCost(Formula)`

- `Int64 _GetMoodBuffByFormula(Formula)`

- `Boolean _CheckSingleIngredient(IFormulaItem, Int32)`

- `Int32 GetMoodCostByCount(Int32, out)`

- `Int32 GetGoldCostByCount(Int32)`

- `Boolean _CheckGoldFreeByFormula(Formula)`

- `Int32 _GetLeftCount(Int32, Formula)`

- `WorkshopCheckResult CheckAsFormula(IWorkshopFormula, Int32, IWorkshopStationaryCharacter)`

- `Void _WorkAsSynthesis(Formula, Int32, Action`1)`

- `Void _WorkAsDecomposition(FurnitureDestructFormula, Int32, Action`1)`

- `Void WorkAsFormula(IWorkshopFormula, Int32, IWorkshopStationaryCharacter, Action`1)`

- `Void RefreshModel()`

- `Void ClearFormulaCache()`

- `Void ClearTargetItemInfoAndRebuildTree()`

- `IWorkshopFormula FindFormulaByItemId(String)`

- `Void _CreateFormulaTreeByCurrent()`

- `Void UpdateFormulaTreeToIngredient(String)`

- `Void UpdateFormulaTreeToParent(String)`

- `IWorkshopFormula GetParentFormula()`

- `Boolean CheckIsNodeCanShowJumpBtn(String)`

- `Boolean CheckIfIngredientCanProcess(String)`

- `Boolean CheckIfHaveTargetAmount()`

- `Int32 CalcCurrentRequiredCount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopModel : IWorkshopSession, IHotfixable
{
	private const String ALL_FORMULA_KEY; // 0x0
	private const Int32 MAX_COUNT; // 0x0
	private RoomSlotModel m_roomSlotModel; // 0x10
	private TargetItemInfo m_targetItemInfo; // 0x18
	private StationaryCharacter m_cachedCharacter; // 0x20
	private List`1 m_formulaCache; // 0x28
	private IWorkshopFormula m_currentFormula; // 0x30
	private WRoomViewModel m_basicRoomModel; // 0x38
	private BuildingWorkShopFormulaTree m_formulaTree; // 0x40
	private Stack`1 m_backStack; // 0x48
	private Boolean <itemProtection>k__BackingField; // 0x50
	private Dictionary`2 m_cachedIngredientFormulaDict; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge _c__Hotfix1_ctor; // 0x8
	private static DelegateBridge __Hotfix0_get_basicRoomModel; // 0x10
	private static DelegateBridge __Hotfix0_get_slotId; // 0x18
	private static DelegateBridge __Hotfix0_get_formulas; // 0x20
	private static DelegateBridge __Hotfix0_get_currentFormula; // 0x28
	private static DelegateBridge __Hotfix0_set_currentFormula; // 0x30
	private static DelegateBridge __Hotfix0_get_backStack; // 0x38
	private static DelegateBridge __Hotfix0_get_stationaryCharacter; // 0x40
	private static DelegateBridge __Hotfix0_get_extraOutcomeProbPercent; // 0x48
	private static DelegateBridge __Hotfix0_get_additionalExtraOutcomeProbPercent; // 0x50
	private static DelegateBridge __Hotfix0_LoadCurrentCharacter; // 0x58
	private static DelegateBridge __Hotfix0_MaxWorkCount; // 0x60
	private static DelegateBridge __Hotfix0__MaxCountWithGold; // 0x68
	private static DelegateBridge __Hotfix0__MaxCountWithMood; // 0x70
	private static DelegateBridge __Hotfix0_get_itemProtection; // 0x78
	private static DelegateBridge __Hotfix0_set_itemProtection; // 0x80
	private static DelegateBridge __Hotfix0_get_gold; // 0x88
	private static DelegateBridge __Hotfix0__GetSingleMoodCost; // 0x90
	private static DelegateBridge __Hotfix0__GetMoodBuffByFormula; // 0x98
	private static DelegateBridge __Hotfix0_TryGetMoodBuffCost; // 0xa0
	private static DelegateBridge __Hotfix0_TryGetMoodBuffCostRe; // 0xa8
	private static DelegateBridge __Hotfix0_TryGetMoodBuffCostFormula; // 0xb0
	private static DelegateBridge __Hotfix0_TryGetMoodBuffCostForce; // 0xb8
	private static DelegateBridge __Hotfix0_TryGetMoodBuffCostDevide; // 0xc0
	private static DelegateBridge __Hotfix0__CheckSingleIngredient; // 0xc8
	private static DelegateBridge __Hotfix0_GetMoodCostByCount; // 0xd0
	private static DelegateBridge __Hotfix0_GetGoldCostByCount; // 0xd8
	private static DelegateBridge __Hotfix0__CheckGoldFreeByFormula; // 0xe0
	private static DelegateBridge __Hotfix0__GetLeftCount; // 0xe8
	private static DelegateBridge __Hotfix0_CheckAsFormula; // 0xf0
	private static DelegateBridge __Hotfix0__WorkAsSynthesis; // 0xf8
	private static DelegateBridge __Hotfix0__WorkAsDecomposition; // 0x100
	private static DelegateBridge __Hotfix0_WorkAsFormula; // 0x108
	private static DelegateBridge __Hotfix0_RefreshModel; // 0x110
	private static DelegateBridge __Hotfix0_ClearFormulaCache; // 0x118
	private static DelegateBridge __Hotfix0_ClearTargetItemInfoAndRebuildTree; // 0x120
	private static DelegateBridge __Hotfix0_FindFormulaByItemId; // 0x128
	private static DelegateBridge __Hotfix0__CreateFormulaTreeByCurrent; // 0x130
	private static DelegateBridge __Hotfix0_UpdateFormulaTreeToIngredient; // 0x138
	private static DelegateBridge __Hotfix0_UpdateFormulaTreeToParent; // 0x140
	private static DelegateBridge __Hotfix0_GetParentFormula; // 0x148
	private static DelegateBridge __Hotfix0_CheckIsNodeCanShowJumpBtn; // 0x150
	private static DelegateBridge __Hotfix0_CheckIfIngredientCanProcess; // 0x158
	private static DelegateBridge __Hotfix0_CheckIfHaveTargetAmount; // 0x160
	private static DelegateBridge __Hotfix0_CalcCurrentRequiredCount; // 0x168

	public IBasicRoomModel basicRoomModel { get; }
	public String slotId { get; }
	public IEnumerable`1 formulas { get; }
	public IWorkshopFormula currentFormula { get; set; }
	public Stack`1 backStack { get; }
	public IWorkshopStationaryCharacter stationaryCharacter { get; }
	public Int32 extraOutcomeProbPercent { get; }
	public Single additionalExtraOutcomeProbPercent { get; }
	public Boolean itemProtection { get; set; }
	private Int64 gold { get; }

	// RVA: 0x3d5f924 VA: 0x7596377924
	public Void .ctor(RoomSlotModel roomSlotModel, TargetItemInfo targetItemInfo) { }
	// RVA: 0x3d603d0 VA: 0x75963783d0
	private Void .ctor() { }
	// RVA: 0x3d604e4 VA: 0x75963784e4
	public IBasicRoomModel get_basicRoomModel() { }
	// RVA: 0x3d60654 VA: 0x7596378654
	public String get_slotId() { }
	// RVA: 0x3d606c8 VA: 0x75963786c8
	public IEnumerable`1 get_formulas() { }
	// RVA: 0x3d607b8 VA: 0x75963787b8
	public IWorkshopFormula get_currentFormula() { }
	// RVA: 0x3d60078 VA: 0x7596378078
	public Void set_currentFormula(IWorkshopFormula value) { }
	// RVA: 0x3d60820 VA: 0x7596378820
	public Stack`1 get_backStack() { }
	// RVA: 0x3d60888 VA: 0x7596378888
	public IWorkshopStationaryCharacter get_stationaryCharacter() { }
	// RVA: 0x3d608f0 VA: 0x75963788f0
	public Int32 get_extraOutcomeProbPercent() { }
	// RVA: 0x3d60d88 VA: 0x7596378d88
	public Single get_additionalExtraOutcomeProbPercent() { }
	// RVA: 0x3d601b4 VA: 0x75963781b4
	public Void LoadCurrentCharacter() { }
	// RVA: 0x3d61780 VA: 0x7596379780
	public Int32 MaxWorkCount(Int32 curSelectCount, out MaxCountLimitReason limitedReason) { }
	// RVA: 0x3d61ffc VA: 0x7596379ffc
	private Int32 _MaxCountWithGold() { }
	// RVA: 0x3d62294 VA: 0x759637a294
	private Int32 _MaxCountWithMood(Int32 curSelectCount) { }
	// RVA: 0x3d61f94 VA: 0x7596379f94
	public Boolean get_itemProtection() { }
	// RVA: 0x3d62614 VA: 0x759637a614
	public Void set_itemProtection(Boolean value) { }
	// RVA: 0x3d62574 VA: 0x759637a574
	private Int64 get_gold() { }
	// RVA: 0x3d60c14 VA: 0x7596378c14
	private Int64 _GetSingleMoodCost(Formula formula) { }
	// RVA: 0x3d62904 VA: 0x759637a904
	private Int64 _GetMoodBuffByFormula(Formula formula) { }
	// RVA: 0x3d62a78 VA: 0x759637aa78
	private static Boolean TryGetMoodBuffCost(PlayerBuildingWorkshopBuff buff, Formula formula, out Int64 changeVal) { }
	// RVA: 0x3d62b98 VA: 0x759637ab98
	private static Boolean TryGetMoodBuffCostRe(PlayerBuildingWorkshopBuff buff, Formula formula, out Int64 changeVal) { }
	// RVA: 0x3d62cb8 VA: 0x759637acb8
	private static Boolean TryGetMoodBuffCostFormula(PlayerBuildingWorkshopBuff buff, Formula formula, out Int64 changeVal) { }
	// RVA: 0x3d62694 VA: 0x759637a694
	private static Boolean TryGetMoodBuffCostForce(PlayerBuildingWorkshopBuff buff, Formula formula, out Int64 changeVal) { }
	// RVA: 0x3d62798 VA: 0x759637a798
	private static Boolean TryGetMoodBuffCostDevide(PlayerBuildingWorkshopBuff buff, Formula formula, out Int64 changeResultVal) { }
	// RVA: 0x3d62df8 VA: 0x759637adf8
	private Boolean _CheckSingleIngredient(IFormulaItem ingredient, Int32 count) { }
	// RVA: 0x3d62f6c VA: 0x759637af6c
	public Int32 GetMoodCostByCount(Int32 count, out Boolean overload) { }
	// RVA: 0x3d63188 VA: 0x759637b188
	public Int32 GetGoldCostByCount(Int32 count) { }
	// RVA: 0x3d6239c VA: 0x759637a39c
	private Boolean _CheckGoldFreeByFormula(Formula formula) { }
	// RVA: 0x3d63280 VA: 0x759637b280
	private Int32 _GetLeftCount(Int32 count, Formula formula) { }
	// RVA: 0x3d633ac VA: 0x759637b3ac
	public WorkshopCheckResult CheckAsFormula(IWorkshopFormula formula, Int32 count, IWorkshopStationaryCharacter character) { }
	// RVA: 0x3d635b8 VA: 0x759637b5b8
	private Void _WorkAsSynthesis(Formula formula, Int32 count, Action`1 resultHandler) { }
	// RVA: 0x3d638dc VA: 0x759637b8dc
	private Void _WorkAsDecomposition(FurnitureDestructFormula formula, Int32 count, Action`1 resultHandler) { }
	// RVA: 0x3d63c54 VA: 0x759637bc54
	public Void WorkAsFormula(IWorkshopFormula formula, Int32 count, IWorkshopStationaryCharacter character, Action`1 resultHandler) { }
	// RVA: 0x3d63db4 VA: 0x759637bdb4
	public Void RefreshModel() { }
	// RVA: 0x3d63e30 VA: 0x759637be30
	public Void ClearFormulaCache() { }
	// RVA: 0x3d63ec8 VA: 0x759637bec8
	public Void ClearTargetItemInfoAndRebuildTree() { }
	// RVA: 0x3d5fb24 VA: 0x7596377b24
	public IWorkshopFormula FindFormulaByItemId(String itemId) { }
	// RVA: 0x3d63f40 VA: 0x759637bf40
	private Void _CreateFormulaTreeByCurrent() { }
	// RVA: 0x3d6417c VA: 0x759637c17c
	public Void UpdateFormulaTreeToIngredient(String ingredientItemId) { }
	// RVA: 0x3d643b0 VA: 0x759637c3b0
	public Void UpdateFormulaTreeToParent(String curFormulaItemId) { }
	// RVA: 0x3d6446c VA: 0x759637c46c
	public IWorkshopFormula GetParentFormula() { }
	// RVA: 0x3d6453c VA: 0x759637c53c
	public Boolean CheckIsNodeCanShowJumpBtn(String ingredientItemId) { }
	// RVA: 0x3d6473c VA: 0x759637c73c
	public Boolean CheckIfIngredientCanProcess(String ingredientItemId) { }
	// RVA: 0x3d64944 VA: 0x759637c944
	public Boolean CheckIfHaveTargetAmount() { }
	// RVA: 0x3d64a24 VA: 0x759637ca24
	public Int32 CalcCurrentRequiredCount() { }
}
```