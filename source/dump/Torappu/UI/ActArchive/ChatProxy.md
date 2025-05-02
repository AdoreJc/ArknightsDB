# ChatProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnChatItemClicked(ActArchiveType, String, ChatSwitchDirection)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ChatProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnChatItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x300aab4 VA: 0x7595622ab4
	protected override String get_compType() { }
	// RVA: 0x300ab30 VA: 0x7595622b30
	protected override String GetPrefabPath() { }
	// RVA: 0x300abb8 VA: 0x7595622bb8
	protected override Void InitComp() { }
	// RVA: 0x300ae70 VA: 0x7595622e70
	private Void _OnChatItemClicked(ActArchiveType type, String chatId, ChatSwitchDirection directionMoveTo) { }
	// RVA: 0x300afa4 VA: 0x7595622fa4
	public Void .ctor() { }
}
```