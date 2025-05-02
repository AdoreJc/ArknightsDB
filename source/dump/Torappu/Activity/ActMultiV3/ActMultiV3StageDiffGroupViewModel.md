# ActMultiV3StageDiffGroupViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3StageModeGroupViewModel specialModeGroup`

- `ActMultiV3StageModeGroupViewModel normalModeGroup`

- `ActMultiV3MapDiffType diffType`

- `String diffName`


## Methods

- `Void LoadData(ActMultiV3MapDiffType, ActMultiV3Data)`

- `Void AddStageListItemViewModel(ActMultiV3StageItemViewModel)`

- `Void Sort()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageDiffGroupViewModel : IHotfixable
{
	public ActMultiV3StageModeGroupViewModel specialModeGroup; // 0x10
	public ActMultiV3StageModeGroupViewModel normalModeGroup; // 0x18
	public ActMultiV3MapDiffType diffType; // 0x20
	public String diffName; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_AddStageListItemViewModel; // 0x8
	private static DelegateBridge __Hotfix0_Sort; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31518fc VA: 0x75957698fc
	public Void LoadData(ActMultiV3MapDiffType diffType, ActMultiV3Data actData) { }
	// RVA: 0x3151ad0 VA: 0x7595769ad0
	public Void AddStageListItemViewModel(ActMultiV3StageItemViewModel itemViewModel) { }
	// RVA: 0x3151b80 VA: 0x7595769b80
	public Void Sort() { }
	// RVA: 0x3151bfc VA: 0x7595769bfc
	public Void .ctor() { }
}
```