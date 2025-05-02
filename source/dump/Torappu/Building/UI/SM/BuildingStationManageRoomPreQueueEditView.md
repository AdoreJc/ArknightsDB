# BuildingStationManageRoomPreQueueEditView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `BuildingStationManagePreQueueView _queueView`

- `Text _textQueueName`

- `GameObject _applyPreQueueAvail`

- `GameObject _applyPreQueueLocked`

- `Int32 m_indexInQueueList`

- `Boolean m_isQueueAvail`


## Methods

- `Void Render(StationManageEditRoomQueueStructModel, Int32)`

- `Void EventOnClickApplyQueue()`

- `Void EventOnClickDeleteQueue()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingStationManageRoomPreQueueEditView : MonoBehaviour, IHotfixable
{
	private BuildingStationManagePreQueueView _queueView; // 0x18
	private Text _textQueueName; // 0x20
	private GameObject _applyPreQueueAvail; // 0x28
	private GameObject _applyPreQueueLocked; // 0x30
	public Action`1 onApplyQueueClicked; // 0x38
	public Action`1 onDeleteQueueClicked; // 0x40
	public Action`2 onPreQueueCharClicked; // 0x48
	private Int32 m_indexInQueueList; // 0x50
	private Boolean m_isQueueAvail; // 0x54
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClickApplyQueue; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClickDeleteQueue; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3db27dc VA: 0x75963ca7dc
	public Void Render(StationManageEditRoomQueueStructModel queueStructModel, Int32 indexInList) { }
	// RVA: 0x3db295c VA: 0x75963ca95c
	public Void EventOnClickApplyQueue() { }
	// RVA: 0x3db29e4 VA: 0x75963ca9e4
	public Void EventOnClickDeleteQueue() { }
	// RVA: 0x3db2a6c VA: 0x75963caa6c
	public Void .ctor() { }
}
```