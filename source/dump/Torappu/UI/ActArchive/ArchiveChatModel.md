# ArchiveChatModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedChatId`

- `Int32 selectedChatIndex`

- `Boolean isInit`

- `ChatSwitchDirection directionMoveTo`


## Methods

- `String GetDefaultItemId(String)`

- `Void LoadData(String, ActArchiveInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChatModel : IHotfixable
{
	public ListDict`2 chatItems; // 0x10
	public String selectedChatId; // 0x18
	public Int32 selectedChatIndex; // 0x20
	public Boolean isInit; // 0x24
	public ChatSwitchDirection directionMoveTo; // 0x28
	private static DelegateBridge __Hotfix0_GetDefaultItemId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3044a7c VA: 0x759565ca7c
	public String GetDefaultItemId(String archiveId) { }
	// RVA: 0x3044c18 VA: 0x759565cc18
	public Void LoadData(String archiveId, ActArchiveInfo archiveInfo) { }
	// RVA: 0x30457e8 VA: 0x759565d7e8
	public Void .ctor() { }
}
```