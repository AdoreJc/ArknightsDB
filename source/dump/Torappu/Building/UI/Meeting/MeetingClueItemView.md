# MeetingClueItemView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Text _nameLabel`

- `Text _originLabel`

- `Text _bonusLabel`

- `GameObject _bonusLabelRoot`

- `GameObject _removeButtonRoot`

- `MeetingClueRestTimeLabel _restTimeLabel`

- `Image _clueImage`

- `GameObject _inSlotPanel`

- `GameObject _selectPanel`

- `IMeetingClue m_clue`


## Methods

- `Void add_onClueClicked(Action`2)`

- `Void remove_onClueClicked(Action`2)`

- `Void add_onClueRemoveClicked(Action`2)`

- `Void remove_onClueRemoveClicked(Action`2)`

- `Void add_onClueUnequipClicked(Action`2)`

- `Void remove_onClueUnequipClicked(Action`2)`

- `Void Setup(IMeetingClue, Boolean, Boolean, Boolean, Int32)`

- `Void _RefreshRestTime()`

- `Void OnDestroy()`

- `Void OnPressed()`

- `Void OnRemovePressed()`

- `Void OnUnequipPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingClueItemView : MonoBehaviour
{
	private Text _nameLabel; // 0x18
	private Text _originLabel; // 0x20
	private Text _bonusLabel; // 0x28
	private GameObject _bonusLabelRoot; // 0x30
	private GameObject _removeButtonRoot; // 0x38
	private MeetingClueRestTimeLabel _restTimeLabel; // 0x40
	private Image _clueImage; // 0x48
	private MeetingClueProducerView[] _producerViews; // 0x50
	private GameObject _inSlotPanel; // 0x58
	private GameObject _selectPanel; // 0x60
	private IMeetingClue m_clue; // 0x68
	private Action`2 onClueClicked; // 0x70
	private Action`2 onClueRemoveClicked; // 0x78
	private Action`2 onClueUnequipClicked; // 0x80


	// RVA: 0x3df600c VA: 0x759640e00c
	public Void add_onClueClicked(Action`2 value) { }
	// RVA: 0x3df5f5c VA: 0x759640df5c
	public Void remove_onClueClicked(Action`2 value) { }
	// RVA: 0x3df616c VA: 0x759640e16c
	public Void add_onClueRemoveClicked(Action`2 value) { }
	// RVA: 0x3df60bc VA: 0x759640e0bc
	public Void remove_onClueRemoveClicked(Action`2 value) { }
	// RVA: 0x3df62cc VA: 0x759640e2cc
	public Void add_onClueUnequipClicked(Action`2 value) { }
	// RVA: 0x3df621c VA: 0x759640e21c
	public Void remove_onClueUnequipClicked(Action`2 value) { }
	// RVA: 0x3df5870 VA: 0x759640d870
	public Void Setup(IMeetingClue clue, Boolean showBonusLabel, Boolean showRemoveButton, Boolean selected, Int32 overrideBonus) { }
	// RVA: 0x3df6750 VA: 0x759640e750
	private Void _RefreshRestTime() { }
	// RVA: 0x3df68b8 VA: 0x759640e8b8
	private Void OnDestroy() { }
	// RVA: 0x3df68f0 VA: 0x759640e8f0
	public Void OnPressed() { }
	// RVA: 0x3df6914 VA: 0x759640e914
	public Void OnRemovePressed() { }
	// RVA: 0x3df6938 VA: 0x759640e938
	public Void OnUnequipPressed() { }
	// RVA: 0x3df695c VA: 0x759640e95c
	public Void .ctor() { }
}
```