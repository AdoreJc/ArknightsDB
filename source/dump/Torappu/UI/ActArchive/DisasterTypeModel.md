# DisasterTypeModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Int32 unlockLevel`

- `String typeSmallIconId`

- `String typeBigActiveIconId`

- `String typeBigInactiveIconId`

- `String disasterTypeId`

- `String archiveId`

- `String name`

- `String desc`

- `Int32 sortId`


## Properties

- `Boolean isAttained`

- `Boolean hasNewMark`


## Methods

- `Boolean get_isAttained()`

- `Boolean get_hasNewMark()`

- `Void ConsumeNewMark()`

- `DisasterItemModel GetCurrentMaxUnlockItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class DisasterTypeModel : IHotfixable
{
	public List`1 disasterLevels; // 0x10
	public Int32 unlockLevel; // 0x18
	public String typeSmallIconId; // 0x20
	public String typeBigActiveIconId; // 0x28
	public String typeBigInactiveIconId; // 0x30
	public String disasterTypeId; // 0x38
	public String archiveId; // 0x40
	public String name; // 0x48
	public String desc; // 0x50
	public Int32 sortId; // 0x58
	private static DelegateBridge __Hotfix0_get_isAttained; // 0x0
	private static DelegateBridge __Hotfix0_get_hasNewMark; // 0x8
	private static DelegateBridge __Hotfix0_ConsumeNewMark; // 0x10
	private static DelegateBridge __Hotfix0_GetCurrentMaxUnlockItem; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isAttained { get; }
	public Boolean hasNewMark { get; }

	// RVA: 0x3048704 VA: 0x7595660704
	public Boolean get_isAttained() { }
	// RVA: 0x3049814 VA: 0x7595661814
	public Boolean get_hasNewMark() { }
	// RVA: 0x3049f58 VA: 0x7595661f58
	public Void ConsumeNewMark() { }
	// RVA: 0x304a050 VA: 0x7595662050
	public DisasterItemModel GetCurrentMaxUnlockItem() { }
	// RVA: 0x304a0dc VA: 0x75956620dc
	public Void .ctor() { }
}
```