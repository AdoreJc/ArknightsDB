# CapsuleItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String capsuleId`

- `Int32 sortId`

- `String name`

- `String usage`

- `String description`

- `String englishName`

- `RoguelikeArchiveItemUnlockStatus status`


## Methods

- `Int32 CompareTo(CapsuleItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class CapsuleItemModel : ArchiveItemModel
{
	public String capsuleId; // 0x30
	public Int32 sortId; // 0x38
	public String name; // 0x40
	public String usage; // 0x48
	public String description; // 0x50
	public String englishName; // 0x58
	public RoguelikeArchiveItemUnlockStatus status; // 0x60
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x303bd74 VA: 0x7595653d74
	public override String GetFuncId() { }
	// RVA: 0x303bddc VA: 0x7595653ddc
	public override String GetDesc() { }
	// RVA: 0x303be44 VA: 0x7595653e44
	public Int32 CompareTo(CapsuleItemModel value) { }
	// RVA: 0x303bed0 VA: 0x7595653ed0
	public Void .ctor() { }
}
```