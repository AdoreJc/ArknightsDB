# ChatItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String chatId`

- `Int32 sortId`

- `String name`

- `String subName`

- `String description`

- `String flavorDescription`

- `Int32 chatSum`

- `String year`

- `String month`

- `String descIndex`

- `Int32 unlockedNum`

- `String chatColor`

- `Boolean canUnlock`

- `Int64 startTime`

- `Int64 endTime`

- `Int64 fullStoredTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ChatItemModel : ArchiveItemModel
{
	public String chatId; // 0x30
	public Int32 sortId; // 0x38
	public String name; // 0x40
	public String subName; // 0x48
	public String description; // 0x50
	public String flavorDescription; // 0x58
	public List`1 chatCharList; // 0x60
	public List`1 unlockedItems; // 0x68
	public Int32 chatSum; // 0x70
	public String year; // 0x78
	public String month; // 0x80
	public String descIndex; // 0x88
	public Int32 unlockedNum; // 0x90
	public String chatColor; // 0x98
	public Boolean canUnlock; // 0xa0
	public Int64 startTime; // 0xa8
	public Int64 endTime; // 0xb0
	public Int64 fullStoredTime; // 0xb8
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x304493c VA: 0x759565c93c
	public override String GetFuncId() { }
	// RVA: 0x30449a4 VA: 0x759565c9a4
	public override String GetDesc() { }
	// RVA: 0x3044a0c VA: 0x759565ca0c
	public Void .ctor() { }
}
```