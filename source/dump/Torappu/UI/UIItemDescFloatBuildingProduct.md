# UIItemDescFloatBuildingProduct

**Namespace:** `Torappu.UI`


## Fields

- `Text _roomName`

- `Button _gotoButton`

- `Button _lockButton`

- `GameObject _ableTips`

- `String m_lockInfoCache`

- `RoomType m_roomTypeCache`

- `Boolean m_enableDropRoute`

- `Boolean m_isEnabled`

- `UIItemViewModel m_cacheViewModel`


## Methods

- `Void set_onRoomClicked(Action`2)`

- `Void Render(RoomType, String, Boolean, UIItemViewModel)`

- `Void EventOnLockBtnClicked()`

- `Void EventOnGotoBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemDescFloatBuildingProduct : MonoBehaviour, IHotfixable
{
	private Text _roomName; // 0x18
	private Button _gotoButton; // 0x20
	private Button _lockButton; // 0x28
	private GameObject _ableTips; // 0x30
	private String m_lockInfoCache; // 0x38
	private RoomType m_roomTypeCache; // 0x40
	private Boolean m_enableDropRoute; // 0x44
	private Boolean m_isEnabled; // 0x45
	private UIItemViewModel m_cacheViewModel; // 0x48
	private Action`2 <onRoomClicked>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onRoomClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onRoomClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnLockBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnGotoBtnClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`2 onRoomClicked { get; set; }

	// RVA: 0x21911e8 VA: 0x75947a91e8
	private Action`2 get_onRoomClicked() { }
	// RVA: 0x2191250 VA: 0x75947a9250
	public Void set_onRoomClicked(Action`2 value) { }
	// RVA: 0x21912d4 VA: 0x75947a92d4
	public Void Render(RoomType roomType, String formulaId, Boolean enableDropRoute, UIItemViewModel itemViewModel) { }
	// RVA: 0x2191698 VA: 0x75947a9698
	public Void EventOnLockBtnClicked() { }
	// RVA: 0x2191708 VA: 0x75947a9708
	public Void EventOnGotoBtnClicked() { }
	// RVA: 0x2191828 VA: 0x75947a9828
	public Void .ctor() { }
}
```