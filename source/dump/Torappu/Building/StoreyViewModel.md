# StoreyViewModel

**Namespace:** `Torappu.Building`


## Fields

- `String id`

- `String name`

- `Boolean isUnlocked`

- `Int32 requireLevel`

- `Int32 yOffset`

- `Boolean isUnderground`


## Methods

- `Void UpdateData(RoomSlotModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class StoreyViewModel : IHotfixable
{
	public String id; // 0x10
	public String name; // 0x18
	public Boolean isUnlocked; // 0x20
	public Int32 requireLevel; // 0x24
	public Int32 yOffset; // 0x28
	public Boolean isUnderground; // 0x2c
	private static DelegateBridge __Hotfix0_UpdateData; // 0x0
	private static DelegateBridge __Hotfix0_LoadViewModels; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x37951f0 VA: 0x7595dad1f0
	public Void UpdateData(RoomSlotModel controlSlot) { }
	// RVA: 0x3795290 VA: 0x7595dad290
	public static ListDict`2 LoadViewModels(RoomSlotModel controlSlotModel, LayoutData layoutData) { }
	// RVA: 0x3795570 VA: 0x7595dad570
	public Void .ctor() { }
}
```