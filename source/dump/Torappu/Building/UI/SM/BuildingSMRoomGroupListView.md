# BuildingSMRoomGroupListView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `UIRecycleLayoutGroup _content`

- `BuildingSMRoomGroupTitleView _titlePrefab`

- `BuildingSMRoomItemView _roomPrefab`

- `Adapter m_adapter`


## Methods

- `Void Render(List`1)`

- `Void _RebuildVirtualViews(List`1)`

- `Boolean _RefreshRoomStatus(List`1)`

- `Color _GetTitleColor(RoomType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingSMRoomGroupListView : MonoBehaviour, IHotfixable
{
	private UIRecycleLayoutGroup _content; // 0x18
	private BuildingSMRoomGroupTitleView _titlePrefab; // 0x20
	private BuildingSMRoomItemView _roomPrefab; // 0x28
	private RoomColor[] _roomColors; // 0x30
	private List`1 m_viewList; // 0x38
	private Adapter m_adapter; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RebuildVirtualViews; // 0x8
	private static DelegateBridge __Hotfix0__RefreshRoomStatus; // 0x10
	private static DelegateBridge __Hotfix0__GetTitleColor; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3dac968 VA: 0x75963c4968
	public Void Render(List`1 roomGroups) { }
	// RVA: 0x3dacdac VA: 0x75963c4dac
	private Void _RebuildVirtualViews(List`1 roomGroups) { }
	// RVA: 0x3daca2c VA: 0x75963c4a2c
	private Boolean _RefreshRoomStatus(List`1 roomGroups) { }
	// RVA: 0x3dad470 VA: 0x75963c5470
	private Color _GetTitleColor(RoomType roomType) { }
	// RVA: 0x3dad9b4 VA: 0x75963c59b4
	public Void .ctor() { }
}
```