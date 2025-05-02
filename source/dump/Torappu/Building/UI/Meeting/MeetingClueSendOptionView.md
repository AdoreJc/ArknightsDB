# MeetingClueSendOptionView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `ToggleButtonGroup _categoryToggleGroup`

- `MeetingClueAdapter _clueAdapter`

- `GameObject _emptyHint`

- `IMeetingSession m_session`

- `Int32 m_categoryFilter`


## Methods

- `Void SetSelectedClue(IMeetingClue)`

- `Void Setup(IMeetingSession, Int32, Action`2)`

- `Boolean _ClueFilterPredicate(IMeetingClue)`

- `Void RefreshClueList()`

- `Void _SetupClueList(Predicate`1)`

- `Void _OnCategoryTogglePressed(Int32)`

- `Void OnDestroy()`

- `Void _OnCluePressed(IMeetingClue, MeetingClueItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingClueSendOptionView : MonoBehaviour
{
	private ToggleButtonGroup _categoryToggleGroup; // 0x18
	private MeetingClueAdapter _clueAdapter; // 0x20
	private GameObject _emptyHint; // 0x28
	private IMeetingSession m_session; // 0x30
	private Action`2 m_clickCallback; // 0x38
	private Int32 m_categoryFilter; // 0x40


	// RVA: 0x3dfa254 VA: 0x7596412254
	public Void SetSelectedClue(IMeetingClue clue) { }
	// RVA: 0x3dfa284 VA: 0x7596412284
	public Void Setup(IMeetingSession session, Int32 category, Action`2 clickCallback) { }
	// RVA: 0x3dfaa8c VA: 0x7596412a8c
	private Boolean _ClueFilterPredicate(IMeetingClue clue) { }
	// RVA: 0x3dfac18 VA: 0x7596412c18
	public Void RefreshClueList() { }
	// RVA: 0x3dfa694 VA: 0x7596412694
	private Void _SetupClueList(Predicate`1 pred) { }
	// RVA: 0x3dfac98 VA: 0x7596412c98
	private Void _OnCategoryTogglePressed(Int32 index) { }
	// RVA: 0x3dfad30 VA: 0x7596412d30
	private Void OnDestroy() { }
	// RVA: 0x3dfae30 VA: 0x7596412e30
	private Void _OnCluePressed(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3dfae4c VA: 0x7596412e4c
	public Void .ctor() { }
}
```