# ChaosItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String itemId`

- `ActArchiveTotemType type`

- `Boolean attained`

- `Int32 sortId`

- `String iconId`

- `String name`

- `String usage`

- `String description`

- `ChaosItemModel childItem`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ChaosItemModel : ArchiveItemModel
{
	public String itemId; // 0x30
	public ActArchiveTotemType type; // 0x38
	public Boolean attained; // 0x3c
	public Int32 sortId; // 0x40
	public String iconId; // 0x48
	public String name; // 0x50
	public String usage; // 0x58
	public String description; // 0x60
	public ChaosItemModel childItem; // 0x68
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3041640 VA: 0x7595659640
	public override String GetFuncId() { }
	// RVA: 0x30416a8 VA: 0x75956596a8
	public override String GetDesc() { }
	// RVA: 0x3041710 VA: 0x7595659710
	public Void .ctor() { }
}
```