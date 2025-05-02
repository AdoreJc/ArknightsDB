# BRoomSlot

**Namespace:** `Torappu.Building.BP`


## Fields

- `RectTransform _roomContainer`

- `GameObject _selectEffect`

- `BUpgradePanel _upgradePanel`

- `Button _tutorialBtnPrefab`

- `BRoom m_room`

- `RectTransform m_rectTransform`

- `Boolean m_isOn`

- `String m_cachedPrefabId`

- `Boolean m_archActiveCache`

- `Button m_dummyTutorialBtn`

- `BLayoutManager <layout>k__BackingField`


## Properties

- `RectTransform rectTrans`

- `Vector2 center`

- `BLayoutManager layout`


## Methods

- `RectTransform get_rectTrans()`

- `Vector2 get_center()`

- `BLayoutManager get_layout()`

- `Void set_layout(BLayoutManager)`

- `BRoom BLayoutManager_GetRoom()`

- `Void Init(RoomSlotModel, BLayoutManager)`

- `Boolean OverrideRoomClickedNormalMode()`

- `Void OnRoomClick(PointerEventData)`

- `Void ActiveArchitecture(Boolean)`

- `Button AVGOnly_RegisterTutorialBtn()`

- `Void _UpdateContent(RoomSlotModel)`

- `Void _SetOnInternal(Boolean)`

- `Void _SetupUpdatePanel(RoomSlotModel)`

- `Void _OnUpgradeComplete()`

- `Void _ClearRoom()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BRoomSlot : AbstractRoomSlot
{
	private const String NAME_DUMMY_TUTORIAL_BTN; // 0x0
	private RectTransform _roomContainer; // 0x20
	private GameObject _selectEffect; // 0x28
	private BUpgradePanel _upgradePanel; // 0x30
	private Button _tutorialBtnPrefab; // 0x38
	private BRoom m_room; // 0x40
	private Action`1 m_roomPlayerChangedListener; // 0x48
	private RectTransform m_rectTransform; // 0x50
	private Boolean m_isOn; // 0x58
	private String m_cachedPrefabId; // 0x60
	private Boolean m_archActiveCache; // 0x68
	private Button m_dummyTutorialBtn; // 0x70
	private BLayoutManager <layout>k__BackingField; // 0x78

	public override Boolean isOn { get; set; }
	public RectTransform rectTrans { get; }
	public Vector2 center { get; }
	public BLayoutManager layout { get; set; }

	// RVA: 0x3d17bd4 VA: 0x759632fbd4
	public override Boolean get_isOn() { }
	// RVA: 0x3d17bdc VA: 0x759632fbdc
	public override Void set_isOn(Boolean value) { }
	// RVA: 0x3d14b80 VA: 0x759632cb80
	public RectTransform get_rectTrans() { }
	// RVA: 0x3d17c38 VA: 0x759632fc38
	public Vector2 get_center() { }
	// RVA: 0x3d17c94 VA: 0x759632fc94
	public BLayoutManager get_layout() { }
	// RVA: 0x3d17c9c VA: 0x759632fc9c
	private Void set_layout(BLayoutManager value) { }
	// RVA: 0x3d17ca4 VA: 0x759632fca4
	public BRoom BLayoutManager_GetRoom() { }
	// RVA: 0x3d1502c VA: 0x759632d02c
	public Void Init(RoomSlotModel model, BLayoutManager layout) { }
	// RVA: 0x3d180fc VA: 0x75963300fc
	public override Void OnContentChange(RoomSlotModel model) { }
	// RVA: 0x3d181ac VA: 0x75963301ac
	public override Void OnPostLayoutContentChanged() { }
	// RVA: 0x3d146c0 VA: 0x759632c6c0
	public Boolean OverrideRoomClickedNormalMode() { }
	// RVA: 0x3d18238 VA: 0x7596330238
	public Void OnRoomClick(PointerEventData eventData) { }
	// RVA: 0x3d13d2c VA: 0x759632bd2c
	public Void ActiveArchitecture(Boolean active) { }
	// RVA: 0x3d18254 VA: 0x7596330254
	public Button AVGOnly_RegisterTutorialBtn() { }
	// RVA: 0x3d1845c VA: 0x759633045c
	protected override Void OnInit() { }
	// RVA: 0x3d185a4 VA: 0x75963305a4
	protected virtual Void OnSelect() { }
	// RVA: 0x3d185a8 VA: 0x75963305a8
	protected virtual Void OnDeselect() { }
	// RVA: 0x3d185ac VA: 0x75963305ac
	protected virtual Void OnDestroy() { }
	// RVA: 0x3d17cac VA: 0x759632fcac
	private Void _UpdateContent(RoomSlotModel model) { }
	// RVA: 0x3d17be4 VA: 0x759632fbe4
	private Void _SetOnInternal(Boolean isOn) { }
	// RVA: 0x3d1869c VA: 0x759633069c
	private Void _SetupUpdatePanel(RoomSlotModel slotModel) { }
	// RVA: 0x3d18a40 VA: 0x7596330a40
	public Void _OnUpgradeComplete() { }
	// RVA: 0x3d185b0 VA: 0x75963305b0
	private Void _ClearRoom() { }
	// RVA: 0x3d18a6c VA: 0x7596330a6c
	public Void .ctor() { }
}
```