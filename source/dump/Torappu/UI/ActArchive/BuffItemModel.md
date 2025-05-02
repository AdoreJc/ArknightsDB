# BuffItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String buffId`

- `Int32 sortId`

- `Int32 groupId`

- `String name`

- `String iconId`

- `String usage`

- `String description`

- `String color`

- `Boolean locked`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class BuffItemModel : ArchiveItemModel
{
	public String buffId; // 0x30
	public Int32 sortId; // 0x38
	public Int32 groupId; // 0x3c
	public String name; // 0x40
	public String iconId; // 0x48
	public String usage; // 0x50
	public String description; // 0x58
	public String color; // 0x60
	public Boolean locked; // 0x68
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3039384 VA: 0x7595651384
	public override String GetFuncId() { }
	// RVA: 0x30393ec VA: 0x75956513ec
	public override String GetDesc() { }
	// RVA: 0x3039454 VA: 0x7595651454
	public Void .ctor() { }
}
```