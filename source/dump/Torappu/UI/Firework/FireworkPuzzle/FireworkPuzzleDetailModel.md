# FireworkPuzzleDetailModel

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `String m_puzzleId`

- `PlateContentModel m_solvePlateModel`

- `FireworkNpcModel m_npcModel`

- `FireworkPlateGroupModel m_plateGroupModel`

- `PuzzleStatus m_puzzleStatus`

- `Int32 m_totalHintCount`

- `UIItemViewModel m_rewardItemModel`

- `Int32 <enterSeqNum>k__BackingField`

- `Int32 <hintSuccSeqNum>k__BackingField`

- `Int32 <hintFailSeqNum>k__BackingField`

- `String <actId>k__BackingField`


## Properties

- `Int32 enterSeqNum`

- `Int32 hintSuccSeqNum`

- `Int32 hintFailSeqNum`

- `String actId`

- `String puzzleId`

- `FireworkPlateGroupModel plateGroupModel`

- `String idleSpineName`

- `FireworkPlateModel plateModel`

- `Int32 availHintCount`

- `UIItemViewModel rewardItemModel`

- `Boolean isPuzzleComplete`


## Methods

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `Int32 get_hintSuccSeqNum()`

- `Void set_hintSuccSeqNum(Int32)`

- `Int32 get_hintFailSeqNum()`

- `Void set_hintFailSeqNum(Int32)`

- `String get_actId()`

- `Void set_actId(String)`

- `String get_puzzleId()`

- `FireworkPlateGroupModel get_plateGroupModel()`

- `String get_idleSpineName()`

- `FireworkPlateModel get_plateModel()`

- `Int32 get_availHintCount()`

- `UIItemViewModel get_rewardItemModel()`

- `Boolean get_isPuzzleComplete()`

- `Void MarkEnter()`

- `Void MarkHintSucc()`

- `Void MarkHintFail()`

- `Void LoadData(String, String, Act38SideServerPuzzleInfo, PlateContent)`

- `PlayerAct38SidePuzzle _GetPlayerPuzzleData(String, String)`

- `FireworkNpcDialogModel RandomDialogByType(NpcDialogType, FireworkNpcDialogModel)`

- `Boolean CheckPlateSuccess()`

- `Boolean TryGetNextDialogType(Boolean, Boolean, Boolean, Boolean, Boolean, out)`

- `FireworkPlateModel GenPlateModel()`

- `Void UpdateHintList()`

- `Void _UpdatePuzzleData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleDetailModel : IHotfixable
{
	private String m_puzzleId; // 0x10
	private PlateContentModel m_solvePlateModel; // 0x18
	private FireworkNpcModel m_npcModel; // 0x20
	private FireworkPlateGroupModel m_plateGroupModel; // 0x28
	private PuzzleStatus m_puzzleStatus; // 0x30
	private List`1 m_hintList; // 0x38
	private Int32 m_totalHintCount; // 0x40
	private UIItemViewModel m_rewardItemModel; // 0x48
	private Int32 <enterSeqNum>k__BackingField; // 0x50
	private Int32 <hintSuccSeqNum>k__BackingField; // 0x54
	private Int32 <hintFailSeqNum>k__BackingField; // 0x58
	private String <actId>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x0
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x8
	private static DelegateBridge __Hotfix0_get_hintSuccSeqNum; // 0x10
	private static DelegateBridge __Hotfix0_set_hintSuccSeqNum; // 0x18
	private static DelegateBridge __Hotfix0_get_hintFailSeqNum; // 0x20
	private static DelegateBridge __Hotfix0_set_hintFailSeqNum; // 0x28
	private static DelegateBridge __Hotfix0_get_actId; // 0x30
	private static DelegateBridge __Hotfix0_set_actId; // 0x38
	private static DelegateBridge __Hotfix0_get_puzzleId; // 0x40
	private static DelegateBridge __Hotfix0_get_plateGroupModel; // 0x48
	private static DelegateBridge __Hotfix0_get_idleSpineName; // 0x50
	private static DelegateBridge __Hotfix0_get_plateModel; // 0x58
	private static DelegateBridge __Hotfix0_get_availHintCount; // 0x60
	private static DelegateBridge __Hotfix0_get_rewardItemModel; // 0x68
	private static DelegateBridge __Hotfix0_get_isPuzzleComplete; // 0x70
	private static DelegateBridge __Hotfix0_MarkEnter; // 0x78
	private static DelegateBridge __Hotfix0_MarkHintSucc; // 0x80
	private static DelegateBridge __Hotfix0_MarkHintFail; // 0x88
	private static DelegateBridge __Hotfix0_LoadData; // 0x90
	private static DelegateBridge __Hotfix0__GetPlayerPuzzleData; // 0x98
	private static DelegateBridge __Hotfix0_RandomDialogByType; // 0xa0
	private static DelegateBridge __Hotfix0_CheckPlateSuccess; // 0xa8
	private static DelegateBridge __Hotfix0_TryGetNextDialogType; // 0xb0
	private static DelegateBridge __Hotfix0_GenPlateModel; // 0xb8
	private static DelegateBridge __Hotfix0_UpdateHintList; // 0xc0
	private static DelegateBridge __Hotfix0__UpdatePuzzleData; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public Int32 enterSeqNum { get; set; }
	public Int32 hintSuccSeqNum { get; set; }
	public Int32 hintFailSeqNum { get; set; }
	public String actId { get; set; }
	public String puzzleId { get; }
	public FireworkPlateGroupModel plateGroupModel { get; }
	public String idleSpineName { get; }
	public FireworkPlateModel plateModel { get; }
	public Int32 availHintCount { get; }
	public UIItemViewModel rewardItemModel { get; }
	public Boolean isPuzzleComplete { get; }

	// RVA: 0x28f9410 VA: 0x7594f11410
	public Int32 get_enterSeqNum() { }
	// RVA: 0x28f9478 VA: 0x7594f11478
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x28f94f4 VA: 0x7594f114f4
	public Int32 get_hintSuccSeqNum() { }
	// RVA: 0x28f955c VA: 0x7594f1155c
	private Void set_hintSuccSeqNum(Int32 value) { }
	// RVA: 0x28f95d8 VA: 0x7594f115d8
	public Int32 get_hintFailSeqNum() { }
	// RVA: 0x28f9640 VA: 0x7594f11640
	private Void set_hintFailSeqNum(Int32 value) { }
	// RVA: 0x28f96bc VA: 0x7594f116bc
	public String get_actId() { }
	// RVA: 0x28f9724 VA: 0x7594f11724
	private Void set_actId(String value) { }
	// RVA: 0x28f97a8 VA: 0x7594f117a8
	public String get_puzzleId() { }
	// RVA: 0x28f9810 VA: 0x7594f11810
	public FireworkPlateGroupModel get_plateGroupModel() { }
	// RVA: 0x28f9878 VA: 0x7594f11878
	public String get_idleSpineName() { }
	// RVA: 0x28f98e8 VA: 0x7594f118e8
	public FireworkPlateModel get_plateModel() { }
	// RVA: 0x28f995c VA: 0x7594f1195c
	public Int32 get_availHintCount() { }
	// RVA: 0x28f99fc VA: 0x7594f119fc
	public UIItemViewModel get_rewardItemModel() { }
	// RVA: 0x28f9a64 VA: 0x7594f11a64
	public Boolean get_isPuzzleComplete() { }
	// RVA: 0x28f9ad4 VA: 0x7594f11ad4
	public Void MarkEnter() { }
	// RVA: 0x28f9b48 VA: 0x7594f11b48
	public Void MarkHintSucc() { }
	// RVA: 0x28f9bbc VA: 0x7594f11bbc
	public Void MarkHintFail() { }
	// RVA: 0x28f9c30 VA: 0x7594f11c30
	public Void LoadData(String actId, String puzzleId, Act38SideServerPuzzleInfo puzzleInfo, PlateContent solvePlateData) { }
	// RVA: 0x28f9eec VA: 0x7594f11eec
	private PlayerAct38SidePuzzle _GetPlayerPuzzleData(String actId, String puzzleId) { }
	// RVA: 0x28fa050 VA: 0x7594f12050
	public FireworkNpcDialogModel RandomDialogByType(NpcDialogType dialogType, FireworkNpcDialogModel lastDialog) { }
	// RVA: 0x28fa0e4 VA: 0x7594f120e4
	public Boolean CheckPlateSuccess() { }
	// RVA: 0x28fa194 VA: 0x7594f12194
	public Boolean TryGetNextDialogType(Boolean hasEnterOp, Boolean hasAddOp, Boolean hasRemoveOp, Boolean hasHintSuccOp, Boolean hasHintFailOp, out NpcDialogType dialogType) { }
	// RVA: 0x28fa2c4 VA: 0x7594f122c4
	public FireworkPlateModel GenPlateModel() { }
	// RVA: 0x28fa3ac VA: 0x7594f123ac
	public Void UpdateHintList() { }
	// RVA: 0x28f9e38 VA: 0x7594f11e38
	private Void _UpdatePuzzleData() { }
	// RVA: 0x28fa450 VA: 0x7594f12450
	public Void .ctor() { }
}
```