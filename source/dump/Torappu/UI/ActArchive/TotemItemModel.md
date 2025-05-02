# TotemItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String itemId`

- `ActArchiveTotemType type`

- `RoguelikeArchiveItemUnlockStatus status`

- `RoguelikeTotemColorType color`

- `Int32 sortId`

- `String name`

- `String usage`

- `String description`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class TotemItemModel : ArchiveItemModel
{
	public String itemId; // 0x30
	public ActArchiveTotemType type; // 0x38
	public RoguelikeArchiveItemUnlockStatus status; // 0x3c
	public RoguelikeTotemColorType color; // 0x40
	public Int32 sortId; // 0x44
	public String name; // 0x48
	public String usage; // 0x50
	public String description; // 0x58
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x308bee0 VA: 0x75956a3ee0
	public override String GetFuncId() { }
	// RVA: 0x308bf48 VA: 0x75956a3f48
	public override String GetDesc() { }
	// RVA: 0x308bfb0 VA: 0x75956a3fb0
	public Void .ctor() { }
}
```