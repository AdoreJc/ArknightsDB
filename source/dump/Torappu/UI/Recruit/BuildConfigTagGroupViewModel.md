# BuildConfigTagGroupViewModel

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `BuildConfigTagViewModel specialTag`

- `SpecialRecruitPool m_recruitTagData`

- `Int32 m_currentOrder`


## Properties

- `Int32 selectTagCount`

- `SpecialRecruitPool getRecruitTagDataBySearch`


## Methods

- `Int32 get_selectTagCount()`

- `SpecialRecruitPool get_getRecruitTagDataBySearch()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class BuildConfigTagGroupViewModel
{
	public BuildConfigTagViewModel[] tags; // 0x10
	public BuildConfigTagViewModel specialTag; // 0x18
	private SpecialRecruitPool m_recruitTagData; // 0x20
	private Int32 m_currentOrder; // 0x28

	public Int32 selectTagCount { get; }
	public SpecialRecruitPool getRecruitTagDataBySearch { get; }

	// RVA: 0x26fd7ec VA: 0x7594d157ec
	public Int32 get_selectTagCount() { }
	// RVA: 0x26fd850 VA: 0x7594d15850
	public SpecialRecruitPool get_getRecruitTagDataBySearch() { }
	// RVA: 0x26fd994 VA: 0x7594d15994
	public Void .ctor() { }
}
```