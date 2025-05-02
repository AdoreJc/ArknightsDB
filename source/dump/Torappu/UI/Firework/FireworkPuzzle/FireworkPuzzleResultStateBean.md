# FireworkPuzzleResultStateBean

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `FireworkPuzzleResultProp m_prop`

- `FireworkPlateModel <cachePlateModel>k__BackingField`

- `Boolean <isFirstComplete>k__BackingField`


## Properties

- `FireworkPlateModel cachePlateModel`

- `Boolean isFirstComplete`

- `FireworkPuzzleResultProp prop`


## Methods

- `FireworkPlateModel get_cachePlateModel()`

- `Void set_cachePlateModel(FireworkPlateModel)`

- `Boolean get_isFirstComplete()`

- `Void set_isFirstComplete(Boolean)`

- `Void set_rewardList(List`1)`

- `FireworkPuzzleResultProp get_prop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleResultStateBean : IStateBean, IHotfixable
{
	private FireworkPuzzleResultProp m_prop; // 0x10
	private FireworkPlateModel <cachePlateModel>k__BackingField; // 0x18
	private Boolean <isFirstComplete>k__BackingField; // 0x20
	private List`1 <rewardList>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_cachePlateModel; // 0x0
	private static DelegateBridge __Hotfix0_set_cachePlateModel; // 0x8
	private static DelegateBridge __Hotfix0_get_isFirstComplete; // 0x10
	private static DelegateBridge __Hotfix0_set_isFirstComplete; // 0x18
	private static DelegateBridge __Hotfix0_get_rewardList; // 0x20
	private static DelegateBridge __Hotfix0_set_rewardList; // 0x28
	private static DelegateBridge __Hotfix0_get_prop; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public FireworkPlateModel cachePlateModel { get; set; }
	public Boolean isFirstComplete { get; set; }
	public List`1 rewardList { get; set; }
	public FireworkPuzzleResultProp prop { get; }

	// RVA: 0x28ff2ac VA: 0x7594f172ac
	public FireworkPlateModel get_cachePlateModel() { }
	// RVA: 0x28ff314 VA: 0x7594f17314
	public Void set_cachePlateModel(FireworkPlateModel value) { }
	// RVA: 0x28ff398 VA: 0x7594f17398
	public Boolean get_isFirstComplete() { }
	// RVA: 0x28ff400 VA: 0x7594f17400
	public Void set_isFirstComplete(Boolean value) { }
	// RVA: 0x28ff480 VA: 0x7594f17480
	public List`1 get_rewardList() { }
	// RVA: 0x28ff4e8 VA: 0x7594f174e8
	public Void set_rewardList(List`1 value) { }
	// RVA: 0x28ff56c VA: 0x7594f1756c
	public FireworkPuzzleResultProp get_prop() { }
	// RVA: 0x28ff5d4 VA: 0x7594f175d4
	public Void .ctor() { }
}
```