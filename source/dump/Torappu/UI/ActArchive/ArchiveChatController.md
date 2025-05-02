# ArchiveChatController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveChatListDataBinder _chatDataBinder`

- `ArchiveChatRecordListDataBinder _charRecordDataBinder`

- `Image _imgBkg`

- `Image _imgTitle`


## Methods

- `Void set_onChatItemClicked(Action`3)`

- `Void OnItemClick(String, ChatSwitchDirection)`

- `Void <>xLuaBaseProxy_OnItemClick(String)`

- `Void <>xLuaBaseProxy_Init(ActArchiveProxy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChatController : ActArchiveController
{
	private ArchiveChatListDataBinder _chatDataBinder; // 0x38
	private ArchiveChatRecordListDataBinder _charRecordDataBinder; // 0x40
	private Image _imgBkg; // 0x48
	private Image _imgTitle; // 0x50
	private Action`3 <onChatItemClicked>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onChatItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onChatItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x10
	private static DelegateBridge __Hotfix1_OnItemClick; // 0x18
	private static DelegateBridge __Hotfix0_InitAndAchieveDataBinders; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`3 onChatItemClicked { get; set; }

	// RVA: 0x3042da0 VA: 0x759565ada0
	private Action`3 get_onChatItemClicked() { }
	// RVA: 0x3042e08 VA: 0x759565ae08
	public Void set_onChatItemClicked(Action`3 value) { }
	// RVA: 0x3042e8c VA: 0x759565ae8c
	public override Void OnItemClick(String funcId) { }
	// RVA: 0x3042f10 VA: 0x759565af10
	public Void OnItemClick(String funcId, ChatSwitchDirection directionMoveTo) { }
	// RVA: 0x3042fd8 VA: 0x759565afd8
	public List`1 InitAndAchieveDataBinders() { }
	// RVA: 0x3043268 VA: 0x759565b268
	public override Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x304345c VA: 0x759565b45c
	public Void .ctor() { }
	// RVA: 0x30434cc VA: 0x759565b4cc
	private Void <>xLuaBaseProxy_OnItemClick(String P0) { }
	// RVA: 0x30434d4 VA: 0x759565b4d4
	private Void <>xLuaBaseProxy_Init(ActArchiveProxy P0) { }
}
```