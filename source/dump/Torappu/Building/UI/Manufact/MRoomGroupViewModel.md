# MRoomGroupViewModel

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `Int32 maxManufactNum`

- `String selectedSlotId`


## Methods

- `Int32 GetRoomNum()`

- `BasicRoomInfoModel GetRoomInfo(Int32)`

- `String GetSelectedSlotId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class MRoomGroupViewModel : IBasicRoomGroupModel, IHotfixable
{
	public Int32 maxManufactNum; // 0x10
	public ListDict`2 rooms; // 0x18
	public String selectedSlotId; // 0x20
	private static DelegateBridge __Hotfix0_GetRoomNum; // 0x0
	private static DelegateBridge __Hotfix0_GetRoomInfo; // 0x8
	private static DelegateBridge __Hotfix0_GetSelectedSlotId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3e04934 VA: 0x759641c934
	public Int32 GetRoomNum() { }
	// RVA: 0x3e049b4 VA: 0x759641c9b4
	public BasicRoomInfoModel GetRoomInfo(Int32 index) { }
	// RVA: 0x3e04ae0 VA: 0x759641cae0
	public String GetSelectedSlotId() { }
	// RVA: 0x3e04b48 VA: 0x759641cb48
	public Void .ctor() { }
}
```