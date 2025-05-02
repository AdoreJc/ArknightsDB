# FireworkPuzzleResultModel

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `FireworkNpcModel m_npcModel`

- `FireworkPlateModel <plateModel>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`

- `Boolean <showReward>k__BackingField`


## Properties

- `FireworkPlateModel plateModel`

- `Int32 enterSeqNum`

- `Boolean showReward`


## Methods

- `FireworkPlateModel get_plateModel()`

- `Void set_plateModel(FireworkPlateModel)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `Boolean get_showReward()`

- `Void set_showReward(Boolean)`

- `Void MarkEnter()`

- `Void LoadData(String, FireworkPlateModel, Boolean)`

- `FireworkNpcDialogModel RandomDialog()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleResultModel : IHotfixable
{
	private FireworkNpcModel m_npcModel; // 0x10
	private FireworkPlateModel <plateModel>k__BackingField; // 0x18
	private Int32 <enterSeqNum>k__BackingField; // 0x20
	private Boolean <showReward>k__BackingField; // 0x24
	private static DelegateBridge __Hotfix0_get_plateModel; // 0x0
	private static DelegateBridge __Hotfix0_set_plateModel; // 0x8
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x10
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x18
	private static DelegateBridge __Hotfix0_get_showReward; // 0x20
	private static DelegateBridge __Hotfix0_set_showReward; // 0x28
	private static DelegateBridge __Hotfix0_MarkEnter; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_RandomDialog; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public FireworkPlateModel plateModel { get; set; }
	public Int32 enterSeqNum { get; set; }
	public Boolean showReward { get; set; }

	// RVA: 0x28fed28 VA: 0x7594f16d28
	public FireworkPlateModel get_plateModel() { }
	// RVA: 0x28fed90 VA: 0x7594f16d90
	private Void set_plateModel(FireworkPlateModel value) { }
	// RVA: 0x28fee14 VA: 0x7594f16e14
	public Int32 get_enterSeqNum() { }
	// RVA: 0x28fee7c VA: 0x7594f16e7c
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x28feef8 VA: 0x7594f16ef8
	public Boolean get_showReward() { }
	// RVA: 0x28fef60 VA: 0x7594f16f60
	private Void set_showReward(Boolean value) { }
	// RVA: 0x28fefe0 VA: 0x7594f16fe0
	public Void MarkEnter() { }
	// RVA: 0x28ff054 VA: 0x7594f17054
	public Void LoadData(String actId, FireworkPlateModel cachePlateModel, Boolean isFirstComplete) { }
	// RVA: 0x28ff114 VA: 0x7594f17114
	public FireworkNpcDialogModel RandomDialog() { }
	// RVA: 0x28ff190 VA: 0x7594f17190
	public Void .ctor() { }
}
```