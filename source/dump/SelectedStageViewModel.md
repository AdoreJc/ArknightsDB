# SelectedStageViewModel

**Namespace:** ` `


## Fields

- `SpecialStageType stageSelectType`


## Properties

- `StageViewModel selectedStageNormal`

- `StageViewModel selectedStageHard`

- `StageViewModel selectedStageViewModel`


## Methods

- `StageViewModel get_selectedStageNormal()`

- `StageViewModel get_selectedStageHard()`

- `StageViewModel get_selectedStageViewModel()`

- `Void RegisterStageViewModel(SpecialStageType, StageViewModel)`

- `StageViewModel GetStageViewModel(SpecialStageType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SelectedStageViewModel
{
	private EnumIntDictionary`2 m_stageDict; // 0x10
	public SpecialStageType stageSelectType; // 0x18

	public StageViewModel selectedStageNormal { get; }
	public StageViewModel selectedStageHard { get; }
	public StageViewModel selectedStageViewModel { get; }

	// RVA: 0x2fca08c VA: 0x75955e208c
	public StageViewModel get_selectedStageNormal() { }
	// RVA: 0x2fca26c VA: 0x75955e226c
	public StageViewModel get_selectedStageHard() { }
	// RVA: 0x2fca87c VA: 0x75955e287c
	public StageViewModel get_selectedStageViewModel() { }
	// RVA: 0x2fca11c VA: 0x75955e211c
	public Void RegisterStageViewModel(SpecialStageType stageType, StageViewModel stageViewModel) { }
	// RVA: 0x2fca548 VA: 0x75955e2548
	public StageViewModel GetStageViewModel(SpecialStageType stageType) { }
	// RVA: 0x2fca094 VA: 0x75955e2094
	public Void .ctor() { }
}
```