# ChatCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ChatProperty chat`


## Methods

- `Void SetSelectedChatItem(String, Boolean, ChatSwitchDirection)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ChatCompInfo : ActArchiveCompInfo
{
	public ChatProperty chat; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedChatItem; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x30


	// RVA: 0x30459f4 VA: 0x759565d9f4
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3045a7c VA: 0x759565da7c
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3045bb0 VA: 0x759565dbb0
	public Void SetSelectedChatItem(String chatId, Boolean isInit, ChatSwitchDirection directionMoveTo) { }
	// RVA: 0x3045e28 VA: 0x759565de28
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3045ee0 VA: 0x759565dee0
	public override Void NotifyUpdate() { }
	// RVA: 0x3045f88 VA: 0x759565df88
	public override Boolean IsValid() { }
	// RVA: 0x3046014 VA: 0x759565e014
	public override Boolean HasNewItem() { }
	// RVA: 0x3046158 VA: 0x759565e158
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```