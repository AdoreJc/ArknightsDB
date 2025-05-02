# BuildingStationSelectConfirmRoomItemView

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `Text _textRoomCode`

- `Text _textRoomIndex`

- `Image _imageRoomBkg`

- `Image _imageRoomDeco`

- `Image _imageRoomIcon`

- `GameObject _roomTargetHolder`

- `Text _textRoomTarget`

- `GameObject _iconRoomStop`

- `GameObject _objCur`

- `BuildingStationSelectConfirmRoomCharCardAdapter _charAdapter`

- `RoomSlotModel m_currentRoomSlot`

- `ChangedRoomViewModel m_cachedRoomModel`

- `SpriteHub m_profHub`


## Properties

- `BuildingCharSelectRoomConfig roomConfig`


## Methods

- `BuildingCharSelectRoomConfig get_roomConfig()`

- `Void Render(ChangedRoomViewModel, Boolean)`

- `Void _ProcessStationChangedChars(List`1)`

- `Void _ProcessAssistChangedChars(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectConfirmRoomItemView : MonoBehaviour, IHotfixable
{
	private Text _textRoomCode; // 0x18
	private Text _textRoomIndex; // 0x20
	private Image _imageRoomBkg; // 0x28
	private Image _imageRoomDeco; // 0x30
	private Image _imageRoomIcon; // 0x38
	private GameObject _roomTargetHolder; // 0x40
	private Text _textRoomTarget; // 0x48
	private GameObject _iconRoomStop; // 0x50
	private GameObject _objCur; // 0x58
	private BuildingStationSelectConfirmRoomCharCardAdapter _charAdapter; // 0x60
	private List`1 m_charViewModels; // 0x68
	private RoomSlotModel m_currentRoomSlot; // 0x70
	private ChangedRoomViewModel m_cachedRoomModel; // 0x78
	private SpriteHub m_profHub; // 0x80
	private static DelegateBridge __Hotfix0_get_roomConfig; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__ProcessStationChangedChars; // 0x10
	private static DelegateBridge __Hotfix0__ProcessAssistChangedChars; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public BuildingCharSelectRoomConfig roomConfig { get; }

	// RVA: 0x3d9da74 VA: 0x75963b5a74
	public BuildingCharSelectRoomConfig get_roomConfig() { }
	// RVA: 0x3d9db0c VA: 0x75963b5b0c
	public Void Render(ChangedRoomViewModel changedModel, Boolean isCur) { }
	// RVA: 0x3d9e164 VA: 0x75963b6164
	private Void _ProcessStationChangedChars(List`1 changedChars) { }
	// RVA: 0x3d9e7d0 VA: 0x75963b67d0
	private Void _ProcessAssistChangedChars(List`1 changedChars) { }
	// RVA: 0x3d9ed38 VA: 0x75963b6d38
	public Void .ctor() { }
}
```