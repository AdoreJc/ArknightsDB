# LogItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String chapterId`

- `String displayId`

- `String chapterName`

- `ChapterIconType chapterIcon`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class LogItemModel : ArchiveItemModel
{
	public List`1 logItemData; // 0x30
	public String chapterId; // 0x38
	public String displayId; // 0x40
	public String chapterName; // 0x48
	public ChapterIconType chapterIcon; // 0x50
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x305b34c VA: 0x759567334c
	public override String GetFuncId() { }
	// RVA: 0x305b3b4 VA: 0x75956733b4
	public override String GetDesc() { }
	// RVA: 0x305b41c VA: 0x759567341c
	public Void .ctor() { }
}
```