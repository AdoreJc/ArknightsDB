# BuildingSMRoomItemView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `Image _imgBkg`

- `SimpleLayoutContent _charLayout`

- `GameObject _panelActive`

- `GameObject _panelInactive`

- `GameObject _panelUpgrading`

- `GameObject _panelHotspot`

- `UIColorGraphic _mainColorComp`

- `GameObject _selectedFrame`

- `Text _textName`

- `GameObject _textIndexHolder`

- `Text _textRoomIndex`

- `GameObject _stopWorkIcon`

- `Text _roomTargetName`

- `BuildingRoomLevelView _commonLevelView`

- `TwoStateToggle _useQueueBtn`

- `TwoStateToggle _setQueueBtn`

- `Single _preferHeight`

- `UIAnimationLocation _anim`

- `Sprite m_levelIcon`

- `CharAdapter m_charAdapter`

- `StationRoomStructModel m_roomModel`

- `RoomType m_cachedRoomType`

- `Boolean m_isSelected`

- `Boolean m_isEditDormLockMode`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `Tween m_charTween`


## Methods

- `Void Render(Params)`

- `Void EventOnRoomClicked()`

- `Void EventOnUseQueueClicked()`

- `Void EventOnUseQueueNotAvailClicked()`

- `Void EventOnEditQueueClicked()`

- `Void OnCharClicked(BuildingCharModel, Object)`

- `Void _UpdateRoomStyle(RoomType)`

- `RoomStyle _PickRoomStyle(RoomType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingSMRoomItemView : MonoBehaviour, IHotfixable
{
	private Image _imgBkg; // 0x18
	private SimpleLayoutContent _charLayout; // 0x20
	private GameObject _panelActive; // 0x28
	private GameObject _panelInactive; // 0x30
	private GameObject _panelUpgrading; // 0x38
	private GameObject _panelHotspot; // 0x40
	private UIColorGraphic _mainColorComp; // 0x48
	private GameObject _selectedFrame; // 0x50
	private Text _textName; // 0x58
	private GameObject _textIndexHolder; // 0x60
	private Text _textRoomIndex; // 0x68
	private GameObject _stopWorkIcon; // 0x70
	private Text _roomTargetName; // 0x78
	private BuildingRoomLevelView _commonLevelView; // 0x80
	private TwoStateToggle _useQueueBtn; // 0x88
	private TwoStateToggle _setQueueBtn; // 0x90
	private RoomStyle[] _roomStyles; // 0x98
	private Single _preferHeight; // 0xa0
	private UIAnimationLocation _anim; // 0xa8
	private Sprite m_levelIcon; // 0xb8
	private CharAdapter m_charAdapter; // 0xc0
	private StationRoomStructModel m_roomModel; // 0xc8
	private RoomType m_cachedRoomType; // 0x120
	private Boolean m_isSelected; // 0x124
	private StationCharStructModel[] m_chars; // 0x128
	private Boolean m_isEditDormLockMode; // 0x130
	private Boolean m_isInited; // 0x131
	private UIStateFinder m_stateFinder; // 0x138
	private Tween m_charTween; // 0x148
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnRoomClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnUseQueueClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnUseQueueNotAvailClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnEditQueueClicked; // 0x20
	private static DelegateBridge __Hotfix0_OnCharClicked; // 0x28
	private static DelegateBridge __Hotfix0__UpdateRoomStyle; // 0x30
	private static DelegateBridge __Hotfix0__PickRoomStyle; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3daedf4 VA: 0x75963c6df4
	public Void Render(Params param) { }
	// RVA: 0x3daf440 VA: 0x75963c7440
	public Void EventOnRoomClicked() { }
	// RVA: 0x3daf56c VA: 0x75963c756c
	public Void EventOnUseQueueClicked() { }
	// RVA: 0x3daf698 VA: 0x75963c7698
	public Void EventOnUseQueueNotAvailClicked() { }
	// RVA: 0x3daf73c VA: 0x75963c773c
	public Void EventOnEditQueueClicked() { }
	// RVA: 0x3daf868 VA: 0x75963c7868
	public Void OnCharClicked(BuildingCharModel target, Object param) { }
	// RVA: 0x3daf328 VA: 0x75963c7328
	private Void _UpdateRoomStyle(RoomType roomId) { }
	// RVA: 0x3dafa5c VA: 0x75963c7a5c
	private RoomStyle _PickRoomStyle(RoomType roomId) { }
	// RVA: 0x3dafbcc VA: 0x75963c7bcc
	public Void .ctor() { }
}
```