# TRoomGroupViewModel

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `Int32 maxTradingRoom`

- `String selectedSlotId`


## Methods

- `Int32 GetRoomNum()`

- `BasicRoomInfoModel GetRoomInfo(Int32)`

- `String GetSelectedSlotId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class TRoomGroupViewModel : IBasicRoomGroupModel, IHotfixable
{
	public Int32 maxTradingRoom; // 0x10
	public ListDict`2 rooms; // 0x18
	public String selectedSlotId; // 0x20
	private static DelegateBridge __Hotfix0_GetRoomNum; // 0x0
	private static DelegateBridge __Hotfix0_GetRoomInfo; // 0x8
	private static DelegateBridge __Hotfix0_GetSelectedSlotId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d829f8 VA: 0x759639a9f8
	public Int32 GetRoomNum() { }
	// RVA: 0x3d82a78 VA: 0x759639aa78
	public BasicRoomInfoModel GetRoomInfo(Int32 index) { }
	// RVA: 0x3d82b84 VA: 0x759639ab84
	public String GetSelectedSlotId() { }
	// RVA: 0x3d81bcc VA: 0x7596399bcc
	public Void .ctor() { }
}
```