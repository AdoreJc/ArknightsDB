# SiracusaChatController

**Namespace:** `Torappu.UI.SiracusaMap.Chat`


## Fields

- `AVGChatBoxController _chatController`

- `ScrollRect _scrollType`

- `SiracusaChatDialogComp _dialogSelfPrefab`

- `SiracusaChatDialogComp _dialogOtherPrefab`

- `SiracusaChatNarrationComp _narrationPrefab`

- `SiracusaChatDialogComp _voiceWithinPrefab`

- `SiracusaChatDecisionComp _decisionPrefab`

- `SiracusaChatObtainComp _obtainPrefab`

- `SiracusaChatEndComp _endPrefab`

- `RoguelikeChatSimpleComp _loadingPrefab`

- `CanvasGroup _skipBtnCanvasGroup`

- `Boolean m_isInited`

- `SiracusaData m_data`

- `Boolean m_cachedIsCharCommentLike`

- `String m_cachedStoryId`

- `Boolean m_cachedIsReplay`

- `Boolean m_alreadySkip`

- `IBridge m_bridge`

- `FadeSwitchTween m_fadeSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void BindBridge(IBridge)`

- `Void SkipEvent()`

- `ChatItemOptions _CreateDialogItem(Command)`

- `ChatItemOptions _CreateNarrationItem(Command)`

- `ChatItemOptions _CreateVoiceWithinItem(Command)`

- `ChatItemOptions _CreateDecisionItem(Command)`

- `ChatItemOptions _CreateObtainItem(Command)`

- `IChatDelayView _CreatePreDelayView()`

- `Void _Play()`

- `Void _Skip()`

- `Void _Replay()`

- `Void _SetPauseIfPlaying(Boolean)`

- `Void _ClearPlaying()`

- `Void _InterruptPlaying()`

- `String _InsertFetcher(String)`

- `Void _OnOptionSelected(String)`

- `Void _OnItemObtained(String)`

- `Void _OnPlayComplete()`

- `Sprite _LoadSiracusaAvatar(String)`

- `Void _ShowSkipButton(Boolean)`

- `Void _NormalRecordFilter(IList`1, List`1, List`1)`

- `Void _SkipRecordFilter(IList`1, List`1, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap.Chat
public class SiracusaChatController : DataBinder`1, IHotfixable
{
	private const Single MOVE_DUR; // 0x0
	private const MovementType SCORLL_MOVEMENT_TYPE; // 0x0
	private AVGChatBoxController _chatController; // 0x20
	private ScrollRect _scrollType; // 0x28
	private SiracusaChatDialogComp _dialogSelfPrefab; // 0x30
	private SiracusaChatDialogComp _dialogOtherPrefab; // 0x38
	private SiracusaChatNarrationComp _narrationPrefab; // 0x40
	private SiracusaChatDialogComp _voiceWithinPrefab; // 0x48
	private SiracusaChatDecisionComp _decisionPrefab; // 0x50
	private SiracusaChatObtainComp _obtainPrefab; // 0x58
	private SiracusaChatEndComp _endPrefab; // 0x60
	private RoguelikeChatSimpleComp _loadingPrefab; // 0x68
	private CanvasGroup _skipBtnCanvasGroup; // 0x70
	private Boolean m_isInited; // 0x78
	private ListDict`2 m_cmdHandlers; // 0x80
	private SiracusaData m_data; // 0x88
	private readonly Dictionary`2 m_playingOptions; // 0x90
	private readonly Dictionary`2 m_playingDecisions; // 0x98
	private readonly Dictionary`2 m_playingObtains; // 0xa0
	private HashSet`1 m_cachedSelectedOptions; // 0xa8
	private HashSet`1 m_cachedObtainedItems; // 0xb0
	private Boolean m_cachedIsCharCommentLike; // 0xb8
	private String m_cachedStoryId; // 0xc0
	private Boolean m_cachedIsReplay; // 0xc8
	private Boolean m_alreadySkip; // 0xc9
	private IBridge m_bridge; // 0xd0
	private FadeSwitchTween m_fadeSwitchTween; // 0xd8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_BindBridge; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_SkipEvent; // 0x18
	private static DelegateBridge __Hotfix0__CreateDialogItem; // 0x20
	private static DelegateBridge __Hotfix0__CreateNarrationItem; // 0x28
	private static DelegateBridge __Hotfix0__CreateVoiceWithinItem; // 0x30
	private static DelegateBridge __Hotfix0__CreateDecisionItem; // 0x38
	private static DelegateBridge __Hotfix0__CreateObtainItem; // 0x40
	private static DelegateBridge __Hotfix0__CreatePreDelayView; // 0x48
	private static DelegateBridge __Hotfix0__BaseCommandHandler; // 0x50
	private static DelegateBridge __Hotfix0__MainCommandHandler; // 0x58
	private static DelegateBridge __Hotfix0__Play; // 0x60
	private static DelegateBridge __Hotfix0__Skip; // 0x68
	private static DelegateBridge __Hotfix0__Replay; // 0x70
	private static DelegateBridge __Hotfix0__SetPauseIfPlaying; // 0x78
	private static DelegateBridge __Hotfix0__ClearPlaying; // 0x80
	private static DelegateBridge __Hotfix0__InterruptPlaying; // 0x88
	private static DelegateBridge __Hotfix0__InsertFetcher; // 0x90
	private static DelegateBridge __Hotfix0__OnOptionSelected; // 0x98
	private static DelegateBridge __Hotfix0__OnItemObtained; // 0xa0
	private static DelegateBridge __Hotfix0__OnPlayComplete; // 0xa8
	private static DelegateBridge __Hotfix0__LoadSiracusaAvatar; // 0xb0
	private static DelegateBridge __Hotfix0_CheckIfOptionCanSelect; // 0xb8
	private static DelegateBridge __Hotfix0__ShowSkipButton; // 0xc0
	private static DelegateBridge __Hotfix0__NormalRecordFilter; // 0xc8
	private static DelegateBridge __Hotfix0__SkipRecordFilter; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8


	// RVA: 0x2422dd0 VA: 0x7594a3add0
	private Void _InitIfNot() { }
	// RVA: 0x2423138 VA: 0x7594a3b138
	public Void BindBridge(IBridge bridge) { }
	// RVA: 0x24231bc VA: 0x7594a3b1bc
	public override Void OnValueChanged(SiracusaMapChatProperty property) { }
	// RVA: 0x2423e04 VA: 0x7594a3be04
	public Void SkipEvent() { }
	// RVA: 0x24241e8 VA: 0x7594a3c1e8
	private ChatItemOptions _CreateDialogItem(Command command) { }
	// RVA: 0x2424684 VA: 0x7594a3c684
	private ChatItemOptions _CreateNarrationItem(Command command) { }
	// RVA: 0x24248ec VA: 0x7594a3c8ec
	private ChatItemOptions _CreateVoiceWithinItem(Command command) { }
	// RVA: 0x2424c38 VA: 0x7594a3cc38
	private ChatItemOptions _CreateDecisionItem(Command command) { }
	// RVA: 0x2425588 VA: 0x7594a3d588
	private ChatItemOptions _CreateObtainItem(Command command) { }
	// RVA: 0x2425a00 VA: 0x7594a3da00
	private IChatDelayView _CreatePreDelayView() { }
	// RVA: 0x2425aa0 VA: 0x7594a3daa0
	private IList`1 _BaseCommandHandler(IList`1 commands) { }
	// RVA: 0x2425f54 VA: 0x7594a3df54
	private IList`1 _MainCommandHandler(IList`1 commands) { }
	// RVA: 0x24239dc VA: 0x7594a3b9dc
	private Void _Play() { }
	// RVA: 0x2423ea8 VA: 0x7594a3bea8
	private Void _Skip() { }
	// RVA: 0x2423744 VA: 0x7594a3b744
	private Void _Replay() { }
	// RVA: 0x24260f4 VA: 0x7594a3e0f4
	private Void _SetPauseIfPlaying(Boolean isPaused) { }
	// RVA: 0x2423570 VA: 0x7594a3b570
	private Void _ClearPlaying() { }
	// RVA: 0x2423664 VA: 0x7594a3b664
	private Void _InterruptPlaying() { }
	// RVA: 0x2426180 VA: 0x7594a3e180
	private String _InsertFetcher(String optionId) { }
	// RVA: 0x2426268 VA: 0x7594a3e268
	private Void _OnOptionSelected(String optionId) { }
	// RVA: 0x2426364 VA: 0x7594a3e364
	private Void _OnItemObtained(String itemId) { }
	// RVA: 0x2426464 VA: 0x7594a3e464
	private Void _OnPlayComplete() { }
	// RVA: 0x2426560 VA: 0x7594a3e560
	private Sprite _LoadSiracusaAvatar(String avatarId) { }
	// RVA: 0x2423ce8 VA: 0x7594a3bce8
	public static Boolean CheckIfOptionCanSelect(HashSet`1 selectedOptionSet, HashSet`1 obtainItemSet, Boolean isCharCommentLike, String optionId, Boolean needCommentLike, String requiredCardId) { }
	// RVA: 0x2426664 VA: 0x7594a3e664
	private Void _ShowSkipButton(Boolean show) { }
	// RVA: 0x24266f0 VA: 0x7594a3e6f0
	private Void _NormalRecordFilter(IList`1 inputItems, List`1 outputRecords, List`1 outputPlayables) { }
	// RVA: 0x2426bd0 VA: 0x7594a3ebd0
	private Void _SkipRecordFilter(IList`1 inputItems, List`1 outputRecords, List`1 outputPlayables) { }
	// RVA: 0x2427090 VA: 0x7594a3f090
	public Void .ctor() { }
}
```