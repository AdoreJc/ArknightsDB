# SRoomGroupViewModel

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `Int32 maxShopRoom`

- `String selectedSlotId`


## Methods

- `Int32 GetRoomNum()`

- `BasicRoomInfoModel GetRoomInfo(Int32)`

- `String GetSelectedSlotId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class SRoomGroupViewModel : IBasicRoomGroupModel, IHotfixable
{
	public Int32 maxShopRoom; // 0x10
	public ListDict`2 rooms; // 0x18
	public String selectedSlotId; // 0x20
	private static DelegateBridge __Hotfix0_GetRoomNum; // 0x0
	private static DelegateBridge __Hotfix0_GetRoomInfo; // 0x8
	private static DelegateBridge __Hotfix0_GetSelectedSlotId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3dbab7c VA: 0x75963d2b7c
	public Int32 GetRoomNum() { }
	// RVA: 0x3dbabfc VA: 0x75963d2bfc
	public BasicRoomInfoModel GetRoomInfo(Int32 index) { }
	// RVA: 0x3dbad24 VA: 0x75963d2d24
	public String GetSelectedSlotId() { }
	// RVA: 0x3dbad8c VA: 0x75963d2d8c
	public Void .ctor() { }
}
```