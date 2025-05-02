# MeetingClueSlotView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Int32 _slotIndex`

- `GameObject _emptyPanel`

- `GameObject _cluePanel`

- `GameObject _selectObject`

- `GameObject _unselectObject`

- `Image _clueImage`

- `Image _clueIcon`

- `MeetingClueRestTimeLabel _restTimeLabel`

- `GameObject _trackPoint`

- `IMeetingClue m_clue`


## Properties

- `Int32 slotIndex`


## Methods

- `Void Setup(IMeetingClue, Action`1, String, Boolean, Boolean)`

- `Void _RefreshRestTimeLabel()`

- `Void SetSelected(Boolean)`

- `Int32 get_slotIndex()`

- `Void OnPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingClueSlotView : MonoBehaviour
{
	private Int32 _slotIndex; // 0x18
	private GameObject _emptyPanel; // 0x20
	private GameObject _cluePanel; // 0x28
	private GameObject _selectObject; // 0x30
	private GameObject _unselectObject; // 0x38
	private Text[] _numberLabels; // 0x40
	private Image _clueImage; // 0x48
	private Image _clueIcon; // 0x50
	private MeetingClueRestTimeLabel _restTimeLabel; // 0x58
	private GameObject _trackPoint; // 0x60
	private Action`1 m_clicked; // 0x68
	private IMeetingClue m_clue; // 0x70

	public Int32 slotIndex { get; }

	// RVA: 0x3dfae54 VA: 0x7596412e54
	public Void Setup(IMeetingClue clue, Action`1 clicked, String iconHubPath, Boolean keepSelection, Boolean showTrackPoint) { }
	// RVA: 0x3dfb14c VA: 0x759641314c
	private Void _RefreshRestTimeLabel() { }
	// RVA: 0x3dfb110 VA: 0x7596413110
	public Void SetSelected(Boolean selected) { }
	// RVA: 0x3dfb2b4 VA: 0x75964132b4
	public Int32 get_slotIndex() { }
	// RVA: 0x3dfb2bc VA: 0x75964132bc
	public Void OnPressed() { }
	// RVA: 0x3dfb2dc VA: 0x75964132dc
	public Void .ctor() { }
}
```