# RoguelikeChatController

**Namespace:** `Torappu.UI.Roguelike.Chat`


## Fields

- `AVGChatBoxController _chatController`

- `ScrollRect _scrollType`

- `RoguelikeChatDialogComp _dialogPrefab`

- `RoguelikeChatSimpleComp _titlePrefab`

- `RoguelikeChatSimpleComp _divPrefab`

- `RoguelikeChatSimpleComp _endPrefab`

- `RoguelikeChatSimpleComp _loadingPrefab`

- `PlayOptions m_playOptions`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `IEnumerator Play(PlayOptions)`

- `Void InterruptPlaying()`

- `Void SetPauseIfPlaying(Boolean)`

- `Void Log(LogOptions)`

- `ChatItemOptions _CreateDialogItem(Command)`

- `ChatItemOptions _CreateTitleItem(Command)`

- `ChatItemOptions _CreateDivItem(Command)`

- `IChatDelayView _CreatePreDelayView()`

- `Void _InterruptPlayingImpl()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Chat
public class RoguelikeChatController : MonoBehaviour, IHotfixable
{
	private const Single MOVE_DUR; // 0x0
	private AVGChatBoxController _chatController; // 0x18
	private ScrollRect _scrollType; // 0x20
	private RoguelikeChatDialogComp _dialogPrefab; // 0x28
	private RoguelikeChatSimpleComp _titlePrefab; // 0x30
	private RoguelikeChatSimpleComp _divPrefab; // 0x38
	private RoguelikeChatSimpleComp _endPrefab; // 0x40
	private RoguelikeChatSimpleComp _loadingPrefab; // 0x48
	private ListDict`2 m_cmdHandlers; // 0x50
	private PlayOptions m_playOptions; // 0x58
	private Boolean m_isInited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Play; // 0x8
	private static DelegateBridge __Hotfix0_InterruptPlaying; // 0x10
	private static DelegateBridge __Hotfix0_SetPauseIfPlaying; // 0x18
	private static DelegateBridge __Hotfix0_Log; // 0x20
	private static DelegateBridge __Hotfix0__CreateDialogItem; // 0x28
	private static DelegateBridge __Hotfix0__CreateTitleItem; // 0x30
	private static DelegateBridge __Hotfix0__CreateDivItem; // 0x38
	private static DelegateBridge __Hotfix0__CreatePreDelayView; // 0x40
	private static DelegateBridge __Hotfix0__BaseCommandHandler; // 0x48
	private static DelegateBridge __Hotfix0__PlayModeCommandHandler; // 0x50
	private static DelegateBridge __Hotfix0__InterruptPlayingImpl; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2bba6c0 VA: 0x75951d26c0
	private Void _InitIfNot() { }
	// RVA: 0x2bba8dc VA: 0x75951d28dc
	public IEnumerator Play(PlayOptions options) { }
	// RVA: 0x2bba9ec VA: 0x75951d29ec
	public Void InterruptPlaying() { }
	// RVA: 0x2bbaae0 VA: 0x75951d2ae0
	public Void SetPauseIfPlaying(Boolean isPaused) { }
	// RVA: 0x2bbab74 VA: 0x75951d2b74
	public Void Log(LogOptions options) { }
	// RVA: 0x2bbae7c VA: 0x75951d2e7c
	private ChatItemOptions _CreateDialogItem(Command command) { }
	// RVA: 0x2bbb180 VA: 0x75951d3180
	private ChatItemOptions _CreateTitleItem(Command command) { }
	// RVA: 0x2bbb280 VA: 0x75951d3280
	private ChatItemOptions _CreateDivItem(Command command) { }
	// RVA: 0x2bbb380 VA: 0x75951d3380
	private IChatDelayView _CreatePreDelayView() { }
	// RVA: 0x2bbb41c VA: 0x75951d341c
	private IList`1 _BaseCommandHandler(IList`1 commands) { }
	// RVA: 0x2bbb8d0 VA: 0x75951d38d0
	private IList`1 _PlayModeCommandHandler(IList`1 commands) { }
	// RVA: 0x2bbaa5c VA: 0x75951d2a5c
	private Void _InterruptPlayingImpl() { }
	// RVA: 0x2bbba78 VA: 0x75951d3a78
	public Void .ctor() { }
}
```