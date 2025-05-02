# CharacterRepoCardGroupViewModel

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `CharacterCardGroupViewModel m_cardGroup`

- `Int32 m_unfinishedCharStageCount`

- `Boolean disableLockAndInSquad`


## Properties

- `CharacterCardGroupViewModel cardGroup`

- `Int32 unfinishedCharStageCnt`


## Methods

- `CharacterCardGroupViewModel get_cardGroup()`

- `Int32 get_unfinishedCharStageCnt()`

- `Void set_unfinishedCharStageCnt(Int32)`

- `CharacterHandbookStageStatus GetStageStatus(Int32)`

- `Void OverrideCharListSort(List`1, CharacterSortType, Action`2)`

- `Int32 _CompareByHandbookStageUp(CharacterCardViewModel, CharacterCardViewModel)`

- `Int32 _CompareByHandbookStageDown(CharacterCardViewModel, CharacterCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class CharacterRepoCardGroupViewModel
{
	private CharacterCardGroupViewModel m_cardGroup; // 0x10
	private Int32 m_unfinishedCharStageCount; // 0x18
	private Comparison`1 m_cachedDefaultComparison; // 0x20
	public Dictionary`2 charStageStatusDict; // 0x28
	public Boolean disableLockAndInSquad; // 0x30

	public CharacterCardGroupViewModel cardGroup { get; }
	public Int32 unfinishedCharStageCnt { get; set; }

	// RVA: 0x2cfb55c VA: 0x759531355c
	public CharacterCardGroupViewModel get_cardGroup() { }
	// RVA: 0x2cfb564 VA: 0x7595313564
	public Int32 get_unfinishedCharStageCnt() { }
	// RVA: 0x2cfb56c VA: 0x759531356c
	public Void set_unfinishedCharStageCnt(Int32 value) { }
	// RVA: 0x2cf90dc VA: 0x75953110dc
	public CharacterHandbookStageStatus GetStageStatus(Int32 instId) { }
	// RVA: 0x2cfb574 VA: 0x7595313574
	public Void OverrideCharListSort(List`1 charList, CharacterSortType sortType, Action`2 selfCharListSort) { }
	// RVA: 0x2cfb708 VA: 0x7595313708
	private Int32 _CompareByHandbookStageUp(CharacterCardViewModel a, CharacterCardViewModel b) { }
	// RVA: 0x2cfb7e8 VA: 0x75953137e8
	private Int32 _CompareByHandbookStageDown(CharacterCardViewModel a, CharacterCardViewModel b) { }
	// RVA: 0x2cfb8c8 VA: 0x75953138c8
	public Void .ctor() { }
}
```