# PowerRoomViewModel

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Int32 totalPower`

- `Int32 providedPower`

- `Single baseBuffSpeed`

- `Single specBuffSpeed`


## Methods

- `Void LoadData(RoomSlotModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class PowerRoomViewModel : IHotfixable
{
	public Int32 totalPower; // 0x10
	public Int32 providedPower; // 0x14
	public Single baseBuffSpeed; // 0x18
	public Single specBuffSpeed; // 0x1c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3e1f6b8 VA: 0x75964376b8
	public Void LoadData(RoomSlotModel slotModel) { }
	// RVA: 0x3e1f8b4 VA: 0x75964378b4
	public Void .ctor() { }
}
```