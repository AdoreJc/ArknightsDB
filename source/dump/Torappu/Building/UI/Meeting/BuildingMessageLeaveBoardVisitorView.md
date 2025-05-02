# BuildingMessageLeaveBoardVisitorView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `GameObject _panelNoVisitor`

- `TickFunctionTimer m_emojiAudioTimer`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(BuildingMessageLeaveBoardModel)`

- `Void _RendVisitorViewForPlayer(BuildingPayloadGetMessageBoardContentResponse)`

- `Void _PlayNewVisitorAudio()`

- `Void _PlayEmojiAudio()`

- `Void _RendVisitorViewForVisitor(BuildingPayloadGetOthersMessageBoardContentResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMessageLeaveBoardVisitorView : MonoBehaviour, IHotfixable
{
	private BuildingMessageLeaveBoardVisitorItemHolderView[] _thisWeekVisitorHolders; // 0x18
	private BuildingMessageLeaveBoardVisitorItemHolderView[] _lastWeekVisitorHolders; // 0x20
	private GameObject _panelNoVisitor; // 0x28
	public Action`1 onClickAvatar; // 0x30
	private TickFunctionTimer m_emojiAudioTimer; // 0x38
	private Boolean m_isInited; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RendVisitorViewForPlayer; // 0x10
	private static DelegateBridge __Hotfix0__PlayNewVisitorAudio; // 0x18
	private static DelegateBridge __Hotfix0__PlayEmojiAudio; // 0x20
	private static DelegateBridge __Hotfix0__RendVisitorViewForVisitor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3dc9a2c VA: 0x75963e1a2c
	private Void _InitIfNot() { }
	// RVA: 0x3dc39f4 VA: 0x75963db9f4
	public Void Render(BuildingMessageLeaveBoardModel model) { }
	// RVA: 0x3dc9b80 VA: 0x75963e1b80
	private Void _RendVisitorViewForPlayer(BuildingPayloadGetMessageBoardContentResponse response) { }
	// RVA: 0x3dca2d4 VA: 0x75963e22d4
	private Void _PlayNewVisitorAudio() { }
	// RVA: 0x3dca37c VA: 0x75963e237c
	private Void _PlayEmojiAudio() { }
	// RVA: 0x3dc9ed4 VA: 0x75963e1ed4
	private Void _RendVisitorViewForVisitor(BuildingPayloadGetOthersMessageBoardContentResponse response) { }
	// RVA: 0x3dca424 VA: 0x75963e2424
	public Void .ctor() { }
}
```