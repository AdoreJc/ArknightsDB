# MeetingFloatStateCornerView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `CharacterView _charView0`

- `CharacterView _charView1`

- `Text _storageClueNumber`

- `Text _storageClueCapacity`

- `Image _progressBar`

- `GameObject _progressBarRoot`

- `Single _updateInterval`

- `IMeetingSession m_session`

- `Single m_timer`

- `Boolean m_storageFull`

- `Boolean m_needUpdateProgress`

- `RoomSlotModel m_roomSlotModel`


## Methods

- `Void Setup(IMeetingSession, RoomSlotModel)`

- `Void _RefreshStorageClueNumber()`

- `Void _SetupCharacterView(IMeetingStationaryCharacter, CharacterView)`

- `Void _UpdateProgressBar()`

- `Void Update()`

- `Void OnBGButtonPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingFloatStateCornerView : MonoBehaviour
{
	private CharacterView _charView0; // 0x18
	private CharacterView _charView1; // 0x20
	private Text _storageClueNumber; // 0x28
	private Text _storageClueCapacity; // 0x30
	private Image _progressBar; // 0x38
	private GameObject _progressBarRoot; // 0x40
	private Single _updateInterval; // 0x48
	private IMeetingSession m_session; // 0x50
	private Single m_timer; // 0x58
	private Boolean m_storageFull; // 0x5c
	private Boolean m_needUpdateProgress; // 0x5d
	private RoomSlotModel m_roomSlotModel; // 0x60


	// RVA: 0x3dfc544 VA: 0x7596414544
	public Void Setup(IMeetingSession session, RoomSlotModel roomSlotModel) { }
	// RVA: 0x3dfca4c VA: 0x7596414a4c
	private Void _RefreshStorageClueNumber() { }
	// RVA: 0x3dfc940 VA: 0x7596414940
	private Void _SetupCharacterView(IMeetingStationaryCharacter character, CharacterView view) { }
	// RVA: 0x3dfcd94 VA: 0x7596414d94
	private Void _UpdateProgressBar() { }
	// RVA: 0x3dfd1b0 VA: 0x75964151b0
	private Void Update() { }
	// RVA: 0x3dfd200 VA: 0x7596415200
	public Void OnBGButtonPressed() { }
	// RVA: 0x3dfd36c VA: 0x759641536c
	public Void .ctor() { }
}
```