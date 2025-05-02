# StoryItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `StoryArchiveResItemData storyItemData`

- `String storyId`

- `Int32 sortId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class StoryItemModel : ArchiveItemModel
{
	public StoryArchiveResItemData storyItemData; // 0x30
	public String storyId; // 0x38
	public Int32 sortId; // 0x40
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3081144 VA: 0x7595699144
	public override String GetFuncId() { }
	// RVA: 0x30811ac VA: 0x75956991ac
	public override String GetDesc() { }
	// RVA: 0x3081240 VA: 0x7595699240
	public Void .ctor() { }
}
```