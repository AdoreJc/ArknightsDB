# RoomSlotGraph

**Namespace:** `Torappu.Building`


## Methods

- `Void LoadData(List`1)`

- `Boolean IsEmpty()`

- `Void Clear()`

- `Void _LoadDataInternal(List`1)`

- `Void _TryMakeConnection(RoomSlotModel, RoomSlotModel, Direction)`

- `Boolean _IsRoomConnected(RoomSlotModel, RoomSlotModel, Direction)`

- `Void _AddEdge(String, String, Direction)`

- `Void QueryConnection(String, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class RoomSlotGraph : IHotfixable
{
	private IDictionary`2 m_graph; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetConnectedSlots; // 0x8
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x10
	private static DelegateBridge __Hotfix0_Clear; // 0x18
	private static DelegateBridge __Hotfix0__LoadDataInternal; // 0x20
	private static DelegateBridge __Hotfix0__TryMakeConnection; // 0x28
	private static DelegateBridge __Hotfix0__IsRoomConnected; // 0x30
	private static DelegateBridge __Hotfix0__AddEdge; // 0x38
	private static DelegateBridge __Hotfix0_QueryConnection; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x378e8a4 VA: 0x7595da68a4
	public Void LoadData(List`1 layout) { }
	// RVA: 0x37918f0 VA: 0x7595da98f0
	public List`1 GetConnectedSlots(String slotId) { }
	// RVA: 0x37919fc VA: 0x7595da99fc
	public Boolean IsEmpty() { }
	// RVA: 0x378e7c8 VA: 0x7595da67c8
	public Void Clear() { }
	// RVA: 0x379164c VA: 0x7595da964c
	private Void _LoadDataInternal(List`1 layout) { }
	// RVA: 0x3791a7c VA: 0x7595da9a7c
	private Void _TryMakeConnection(RoomSlotModel slot, RoomSlotModel nextSlot, Direction type) { }
	// RVA: 0x3791b98 VA: 0x7595da9b98
	private Boolean _IsRoomConnected(RoomSlotModel a, RoomSlotModel b, Direction type) { }
	// RVA: 0x3791c78 VA: 0x7595da9c78
	private Void _AddEdge(String fromSlot, String toSlot, Direction type) { }
	// RVA: 0x3791ee0 VA: 0x7595da9ee0
	public Void QueryConnection(String slotId, Action`1 action) { }
	// RVA: 0x3790de8 VA: 0x7595da8de8
	public Void .ctor() { }
}
```