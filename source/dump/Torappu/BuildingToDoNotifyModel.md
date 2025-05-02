# BuildingToDoNotifyModel

**Namespace:** `Torappu`


## Fields

- `Int32 m_emerCount`

- `Int32 m_normalCount`


## Methods

- `Int32 CountOfNotifications(BuildingToDoCategory)`

- `Void AdjustSelections(ref, ref)`

- `Void LoadData()`

- `Void _LoadEmergency()`

- `Void _LoadNormal()`

- `Void _AddNewProductNormalNotification(ref)`

- `Void _AddNewOrderNormalNotification(ref)`

- `Void _AddCharTiredNormalNotification(ref)`

- `Void _AddNewFavorMaxNotification(ref)`

- `Void _AddHireRefreshCountNormalNotification(ref)`

- `Void _AddBatchBtnNormalNotification(ref)`

- `Void _AddMessageBoardNotification(ref, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuildingToDoNotifyModel : IHotfixable
{
	private ListDict`2 m_notifications; // 0x10
	private Int32 m_emerCount; // 0x18
	private Int32 m_normalCount; // 0x1c
	private static DelegateBridge __Hotfix0_GetNotifications; // 0x0
	private static DelegateBridge __Hotfix0_CountOfNotifications; // 0x8
	private static DelegateBridge __Hotfix0_AdjustSelections; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0__LoadEmergency; // 0x20
	private static DelegateBridge __Hotfix0__LoadNormal; // 0x28
	private static DelegateBridge __Hotfix0__AddNewProductNormalNotification; // 0x30
	private static DelegateBridge __Hotfix0__AddNewOrderNormalNotification; // 0x38
	private static DelegateBridge __Hotfix0__AddCharTiredNormalNotification; // 0x40
	private static DelegateBridge __Hotfix0__AddNewFavorMaxNotification; // 0x48
	private static DelegateBridge __Hotfix0__AddHireRefreshCountNormalNotification; // 0x50
	private static DelegateBridge __Hotfix0__AddBatchBtnNormalNotification; // 0x58
	private static DelegateBridge __Hotfix0__AddMessageBoardNotification; // 0x60
	private static DelegateBridge __Hotfix0__CreateNotifyIfExists; // 0x68
	private static DelegateBridge __Hotfix0__AddToListSecured; // 0x70
	private static DelegateBridge __Hotfix0__CreateNewFavorModel; // 0x78
	private static DelegateBridge __Hotfix0__NewFavorAddSlots; // 0x80
	private static DelegateBridge __Hotfix0__CheckIfRoomSlotBuilt; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x2d0d2c0 VA: 0x75953252c0
	public List`1 GetNotifications(BuildingToDoCategory category) { }
	// RVA: 0x2d0d360 VA: 0x7595325360
	public Int32 CountOfNotifications(BuildingToDoCategory category) { }
	// RVA: 0x2d0d3fc VA: 0x75953253fc
	public Void AdjustSelections(ref BuildingToDoCategory selectedCategory, ref BuildingToDoType selectedType) { }
	// RVA: 0x2d0d594 VA: 0x7595325594
	public Void LoadData() { }
	// RVA: 0x2d0d640 VA: 0x7595325640
	private Void _LoadEmergency() { }
	// RVA: 0x2d0dc5c VA: 0x7595325c5c
	private Void _LoadNormal() { }
	// RVA: 0x2d0e3c8 VA: 0x75953263c8
	private Void _AddNewProductNormalNotification(ref List`1 normalList) { }
	// RVA: 0x2d0e5ac VA: 0x75953265ac
	private Void _AddNewOrderNormalNotification(ref List`1 normalList) { }
	// RVA: 0x2d0ede8 VA: 0x7595326de8
	private Void _AddCharTiredNormalNotification(ref List`1 normalList) { }
	// RVA: 0x2d0e790 VA: 0x7595326790
	private Void _AddNewFavorMaxNotification(ref List`1 normalList) { }
	// RVA: 0x2d0f1c4 VA: 0x75953271c4
	private Void _AddHireRefreshCountNormalNotification(ref List`1 normalList) { }
	// RVA: 0x2d0e974 VA: 0x7595326974
	private Void _AddBatchBtnNormalNotification(ref List`1 normalList) { }
	// RVA: 0x2d0efcc VA: 0x7595326fcc
	private Void _AddMessageBoardNotification(ref List`1 normalList, String meetingSlotId) { }
	// RVA: 0x2d0e2dc VA: 0x75953262dc
	private static BuildingToDoNotifyItemModel _CreateNotifyIfExists(Func`1 funcCreate, Func`1 funcAddSlot, Boolean slotCanBeEmpty) { }
	// RVA: 0x VA: 0x0
	private static Void _AddToListSecured(Type val, ref List`1 refList) { }
	// RVA: 0x2d0f3b8 VA: 0x75953273b8
	private static BuildingToDoNotifyItemModel _CreateNewFavorModel() { }
	// RVA: 0x2d0f710 VA: 0x7595327710
	private static NotifyContext _NewFavorAddSlots() { }
	// RVA: 0x2d0fff8 VA: 0x7595327ff8
	private static Boolean _CheckIfRoomSlotBuilt(String slotId) { }
	// RVA: 0x2d100f4 VA: 0x75953280f4
	public Void .ctor() { }
}
```