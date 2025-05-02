# MeetingViewModel

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Int32 creditFromAssist`

- `Int32 creditFromAssistMax`

- `Int32 creditFromDorm`

- `Int32 creditFromDormMax`

- `Int32 creditFromVisit`

- `Int32 creditFromVisitMax`

- `Int32 totalCredit`

- `Int32 totalCreditMax`

- `Boolean hasCreditSettled`

- `Int32 visitNum`

- `RoomSlotModel slotModel`


## Methods

- `Boolean CheckIfCanSettleCredit(out)`

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class MeetingViewModel
{
	public Int32 creditFromAssist; // 0x10
	public Int32 creditFromAssistMax; // 0x14
	public Int32 creditFromDorm; // 0x18
	public Int32 creditFromDormMax; // 0x1c
	public Int32 creditFromVisit; // 0x20
	public Int32 creditFromVisitMax; // 0x24
	public Int32 totalCredit; // 0x28
	public Int32 totalCreditMax; // 0x2c
	public Boolean hasCreditSettled; // 0x30
	public Int32 visitNum; // 0x34
	public RoomSlotModel slotModel; // 0x38


	// RVA: 0x3e16b8c VA: 0x759642eb8c
	public Boolean CheckIfCanSettleCredit(out String errorAlert) { }
	// RVA: 0x3e16c60 VA: 0x759642ec60
	public Void LoadData() { }
	// RVA: 0x3e16c64 VA: 0x759642ec64
	public Void .ctor() { }
}
```