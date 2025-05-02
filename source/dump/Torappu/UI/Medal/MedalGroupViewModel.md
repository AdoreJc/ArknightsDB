# MedalGroupViewModel

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalCount m_medalCount`

- `MedalExpireStatus m_expireStatus`

- `String typeId`

- `MedalGroupData data`


## Properties

- `String groupId`

- `Int32 totalCount`

- `Int32 availCount`

- `Int32 sortId`


## Methods

- `String get_groupId()`

- `Int32 get_totalCount()`

- `Int64 GetLastGetTime()`

- `Int32 get_availCount()`

- `Boolean ContainsAchievedMedal()`

- `Boolean ContainsNotAchievedMedal()`

- `Boolean ContainsMedalToDisplay()`

- `Void AddMedal(MedalCommonViewModel)`

- `Int32 get_sortId()`

- `Void SetMedalCount(MedalCount)`

- `Void UpdateGroupExpireStatus(Int64)`

- `Boolean IsPermExpired()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalGroupViewModel : IHotfixable
{
	public const String DEFAULT_GROUP; // 0x0
	private MedalCount m_medalCount; // 0x10
	private MedalExpireStatus m_expireStatus; // 0x1c
	public String typeId; // 0x28
	public MedalGroupData data; // 0x30
	public List`1 medalList; // 0x38
	private static DelegateBridge __Hotfix0_get_groupId; // 0x0
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x8
	private static DelegateBridge __Hotfix0_GetLastGetTime; // 0x10
	private static DelegateBridge __Hotfix0_get_availCount; // 0x18
	private static DelegateBridge __Hotfix0_ContainsAchievedMedal; // 0x20
	private static DelegateBridge __Hotfix0_ContainsNotAchievedMedal; // 0x28
	private static DelegateBridge __Hotfix0_ContainsMedalToDisplay; // 0x30
	private static DelegateBridge __Hotfix0_AddMedal; // 0x38
	private static DelegateBridge __Hotfix0_get_sortId; // 0x40
	private static DelegateBridge __Hotfix0_SetMedalCount; // 0x48
	private static DelegateBridge __Hotfix0_UpdateGroupExpireStatus; // 0x50
	private static DelegateBridge __Hotfix0_IsPermExpired; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public String groupId { get; }
	public Int32 totalCount { get; }
	public Int32 availCount { get; }
	public Int32 sortId { get; }

	// RVA: 0x27a3e64 VA: 0x7594dbbe64
	public String get_groupId() { }
	// RVA: 0x27ab2a8 VA: 0x7594dc32a8
	public Int32 get_totalCount() { }
	// RVA: 0x27ab334 VA: 0x7594dc3334
	public Int64 GetLastGetTime() { }
	// RVA: 0x27aa8f0 VA: 0x7594dc28f0
	public Int32 get_availCount() { }
	// RVA: 0x27ab430 VA: 0x7594dc3430
	public Boolean ContainsAchievedMedal() { }
	// RVA: 0x27ab4dc VA: 0x7594dc34dc
	public Boolean ContainsNotAchievedMedal() { }
	// RVA: 0x27ab574 VA: 0x7594dc3574
	public Boolean ContainsMedalToDisplay() { }
	// RVA: 0x27ab078 VA: 0x7594dc3078
	public Void AddMedal(MedalCommonViewModel viewModel) { }
	// RVA: 0x27ab620 VA: 0x7594dc3620
	public Int32 get_sortId() { }
	// RVA: 0x27ab698 VA: 0x7594dc3698
	public Void SetMedalCount(MedalCount medalCount) { }
	// RVA: 0x27ab720 VA: 0x7594dc3720
	public Void UpdateGroupExpireStatus(Int64 curTs) { }
	// RVA: 0x27ab7dc VA: 0x7594dc37dc
	public Boolean IsPermExpired() { }
	// RVA: 0x27aaa64 VA: 0x7594dc2a64
	public Void .ctor() { }
}
```