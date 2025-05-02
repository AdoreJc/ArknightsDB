# CarvingHomeEntryItemViewModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingChallengeStatus status`

- `String id`

- `String name`

- `String desc`

- `Int32 bestRecord`

- `Int32 roundCount`

- `String prefabId`

- `String iconId`

- `Int32 sortId`

- `Int64 openTs`

- `DateTime openTime`

- `Boolean isStageLocked`

- `Boolean isNewUnlock`


## Properties

- `Boolean isLocked`


## Methods

- `Boolean get_isLocked()`

- `Int32 CompareTo(Object)`

- `Void CalcStatus(Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingHomeEntryItemViewModel : IComparable, IHotfixable
{
	public CarvingChallengeStatus status; // 0x10
	public String id; // 0x18
	public String name; // 0x20
	public String desc; // 0x28
	public Int32 bestRecord; // 0x30
	public Int32 roundCount; // 0x34
	public String prefabId; // 0x38
	public String iconId; // 0x40
	public Int32 sortId; // 0x48
	public Int64 openTs; // 0x50
	public DateTime openTime; // 0x58
	public Boolean isStageLocked; // 0x60
	public Boolean isNewUnlock; // 0x61
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge __Hotfix0_CalcStatus; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isLocked { get; }

	// RVA: 0x2d92c48 VA: 0x75953aac48
	public Boolean get_isLocked() { }
	// RVA: 0x2d964e4 VA: 0x75953ae4e4
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2d965e0 VA: 0x75953ae5e0
	public Void CalcStatus(Int64 currTs) { }
	// RVA: 0x2d96698 VA: 0x75953ae698
	public Void .ctor() { }
}
```