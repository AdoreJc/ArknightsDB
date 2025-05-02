# MeetingClueStorageView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `ToggleButtonGroup _sourceToggleGroup`

- `ToggleButtonGroup _categoryToggleGroup`

- `MeetingClueAdapter _clueAdapter`

- `Text _noClueHint`

- `IMeetingSession m_session`

- `SourceFilterState m_sourceFilterState`

- `Int32 m_categoryFilter`


## Methods

- `Void Setup(IMeetingSession, Int32, Action`2, Action`2, Action`2)`

- `Boolean _ClueFilterPredicate(IMeetingClue)`

- `Void RefreshClueCountLabel()`

- `Void RefreshClueList(Boolean)`

- `Void _SetupClueList(Predicate`1)`

- `Void _OnSourceTogglePressed(Int32)`

- `Void _OnCategoryTogglePressed(Int32)`

- `Void OnDestroy()`

- `Void _OnCluePressed(IMeetingClue, MeetingClueItemView)`

- `Void _OnClueRemovePressed(IMeetingClue, MeetingClueItemView)`

- `Void _OnClueUnequipPressed(IMeetingClue, MeetingClueItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingClueStorageView : MonoBehaviour
{
	private ToggleButtonGroup _sourceToggleGroup; // 0x18
	private ToggleButtonGroup _categoryToggleGroup; // 0x20
	private MeetingClueAdapter _clueAdapter; // 0x28
	private Text[] _localClueCountLabels; // 0x30
	private Text _noClueHint; // 0x38
	private IMeetingSession m_session; // 0x40
	private Action`2 m_clickCallback; // 0x48
	private Action`2 m_removeClickCallback; // 0x50
	private Action`2 m_unequipClickCallback; // 0x58
	private SourceFilterState m_sourceFilterState; // 0x60
	private Int32 m_categoryFilter; // 0x64


	// RVA: 0x3dfb2e4 VA: 0x75964132e4
	public Void Setup(IMeetingSession session, Int32 category, Action`2 clickCallback, Action`2 removeClickCallback, Action`2 unequipClickCallback) { }
	// RVA: 0x3dfbf64 VA: 0x7596413f64
	private Boolean _ClueFilterPredicate(IMeetingClue clue) { }
	// RVA: 0x3dfbb90 VA: 0x7596413b90
	public Void RefreshClueCountLabel() { }
	// RVA: 0x3dfc118 VA: 0x7596414118
	public Void RefreshClueList(Boolean rebuild) { }
	// RVA: 0x3dfb6bc VA: 0x75964136bc
	private Void _SetupClueList(Predicate`1 pred) { }
	// RVA: 0x3dfc1b8 VA: 0x75964141b8
	private Void _OnSourceTogglePressed(Int32 index) { }
	// RVA: 0x3dfc250 VA: 0x7596414250
	private Void _OnCategoryTogglePressed(Int32 index) { }
	// RVA: 0x3dfc2e8 VA: 0x75964142e8
	private Void OnDestroy() { }
	// RVA: 0x3dfc4e8 VA: 0x75964144e8
	private Void _OnCluePressed(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3dfc504 VA: 0x7596414504
	private Void _OnClueRemovePressed(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3dfc520 VA: 0x7596414520
	private Void _OnClueUnequipPressed(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3dfc53c VA: 0x759641453c
	public Void .ctor() { }
}
```