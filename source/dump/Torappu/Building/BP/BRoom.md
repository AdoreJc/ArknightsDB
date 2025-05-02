# BRoom

**Namespace:** `Torappu.Building.BP`


## Fields

- `Text _textName`

- `GameObject _panelArchitectOnly`

- `GameObject _panelNormalOnly`

- `GameObject _canLevelupIcon`

- `BRoomSlot m_roomSlot`

- `RoomSlotModel m_roomSlotModel`

- `Boolean m_inArchitecture`


## Properties

- `BRoomSlot roomSlot`

- `RoomSlotModel roomSlotModel`

- `BLayoutManager layout`


## Methods

- `BRoomSlot get_roomSlot()`

- `RoomSlotModel get_roomSlotModel()`

- `BLayoutManager get_layout()`

- `Void UpdateLevelupIcon()`

- `Void Init(BRoomSlot, RoomSlotModel)`

- `Void UpdateContent(RoomSlotModel)`

- `Boolean ClickRoom()`

- `Void ActiveArchitecture(Boolean)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BRoom : MonoBehaviour, IHotfixable
{
	private Text _textName; // 0x18
	private GameObject _panelArchitectOnly; // 0x20
	private GameObject _panelNormalOnly; // 0x28
	private GameObject _canLevelupIcon; // 0x30
	private BRoomSlot m_roomSlot; // 0x38
	private RoomSlotModel m_roomSlotModel; // 0x40
	private Boolean m_inArchitecture; // 0x48
	private static DelegateBridge __Hotfix0_get_roomSlot; // 0x0
	private static DelegateBridge __Hotfix0_get_roomSlotModel; // 0x8
	private static DelegateBridge __Hotfix0_get_layout; // 0x10
	private static DelegateBridge __Hotfix0_ListenerToPlayerData; // 0x18
	private static DelegateBridge __Hotfix0_UpdateLevelupIcon; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_UpdateContent; // 0x30
	private static DelegateBridge __Hotfix0_ClickRoom; // 0x38
	private static DelegateBridge __Hotfix0_ActiveArchitecture; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge __Hotfix0_OnInit; // 0x50
	private static DelegateBridge __Hotfix0_OnContentChanged; // 0x58
	private static DelegateBridge __Hotfix0_OnRoomClicked; // 0x60
	private static DelegateBridge __Hotfix0_OnRoomDestroy; // 0x68
	private static DelegateBridge __Hotfix0_get_roomName; // 0x70
	private static DelegateBridge __Hotfix0_OnActiveArchitecture; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	protected BRoomSlot roomSlot { get; }
	public RoomSlotModel roomSlotModel { get; }
	protected BLayoutManager layout { get; }
	protected virtual String roomName { get; }

	// RVA: 0x3d17164 VA: 0x759632f164
	protected BRoomSlot get_roomSlot() { }
	// RVA: 0x3d15314 VA: 0x759632d314
	public RoomSlotModel get_roomSlotModel() { }
	// RVA: 0x3d171cc VA: 0x759632f1cc
	protected BLayoutManager get_layout() { }
	// RVA: 0x3d17284 VA: 0x759632f284
	public virtual Action`1 ListenerToPlayerData() { }
	// RVA: 0x3d172e8 VA: 0x759632f2e8
	public Void UpdateLevelupIcon() { }
	// RVA: 0x3d17470 VA: 0x759632f470
	public Void Init(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d175a0 VA: 0x759632f5a0
	public Void UpdateContent(RoomSlotModel slotModel) { }
	// RVA: 0x3d176cc VA: 0x759632f6cc
	public Boolean ClickRoom() { }
	// RVA: 0x3d1773c VA: 0x759632f73c
	public Void ActiveArchitecture(Boolean active) { }
	// RVA: 0x3d177f8 VA: 0x759632f7f8
	private Void OnDestroy() { }
	// RVA: 0x3d17868 VA: 0x759632f868
	protected virtual Void OnInit(BRoomSlot roomSlot, RoomSlotModel slotModel) { }
	// RVA: 0x3d178e8 VA: 0x759632f8e8
	protected virtual Void OnContentChanged(RoomSlotModel slotModel) { }
	// RVA: 0x3d17960 VA: 0x759632f960
	protected virtual Boolean OnRoomClicked() { }
	// RVA: 0x3d179c4 VA: 0x759632f9c4
	protected virtual Void OnRoomDestroy() { }
	// RVA: 0x3d17a28 VA: 0x759632fa28
	protected virtual String get_roomName() { }
	// RVA: 0x3d17ac4 VA: 0x759632fac4
	protected virtual Void OnActiveArchitecture(Boolean active, Func`2 validPred) { }
	// RVA: 0x3d17b64 VA: 0x759632fb64
	public Void .ctor() { }
}
```