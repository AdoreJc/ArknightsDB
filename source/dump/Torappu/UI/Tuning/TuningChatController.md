# TuningChatController

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `AVGChatBoxController _chatController`

- `TuningChatDialogComp _dialogPrefab`

- `TuningChatSimpleComp _linePrefab`

- `TuningChatTitleComp _titlePrefab`

- `TuningChatSimpleComp _startPrefab`

- `TuningChatSimpleComp _successPrefab`

- `TuningChatSimpleComp _endPrefab`

- `TuningChatPredelayComp _loadingPrefab`

- `Text _scaleFactorFetcher`

- `PlayOptions m_playOptions`

- `UIPageFinder m_pageFinder`

- `Int32 m_cachedUnhandledIndex`

- `Boolean m_isInited`

- `TuningChatCoroutineHandler m_coroutineHandler`


## Methods

- `Void _InitIfNot()`

- `Void Play(PlayOptions)`

- `Void Skip()`

- `Void ResetPlay()`

- `Void _SkipImpl(PlayOptions)`

- `Void _PlayImpl(PlayOptions, Action`3, Boolean)`

- `ChatItemOptions _CreateDialogItem(Command)`

- `ChatItemOptions _CreateTitleItem(Command)`

- `ChatItemOptions _CreateDivItem(Command)`

- `ChatItemOptions _CreateNarItem(Command)`

- `Void _PlayRecordFilter(IList`1, List`1, List`1)`

- `Void _SkipRecordFilter(IList`1, List`1, List`1)`

- `IChatDelayView _CreatePreDelayView()`

- `Void HandleNarration(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatController : MonoBehaviour, IHotfixable
{
	public static String NARRATION_STYLE_SKIP; // 0x0
	public static String NARRATION_STYLE_NEXT; // 0x8
	public static String NARRATION_STYLE_SUBMIT; // 0x10
	public static String NARRATION_STYLE_FINISH; // 0x18
	public static String DIALOG_STYLE_ASK; // 0x20
	public static String DIALOG_STYLE_ANSWER; // 0x28
	private const String DIV_STYLE_LINE; // 0x0
	private const String DIV_STYLE_START; // 0x0
	private const String DIV_STYLE_SUCCESS; // 0x0
	private const Single MOVE_DUR; // 0x0
	private AVGChatBoxController _chatController; // 0x18
	private TuningChatDialogComp _dialogPrefab; // 0x20
	private TuningChatSimpleComp _linePrefab; // 0x28
	private TuningChatTitleComp _titlePrefab; // 0x30
	private TuningChatSimpleComp _startPrefab; // 0x38
	private TuningChatSimpleComp _successPrefab; // 0x40
	private TuningChatSimpleComp _endPrefab; // 0x48
	private TuningChatPredelayComp _loadingPrefab; // 0x50
	private Text _scaleFactorFetcher; // 0x58
	private ListDict`2 m_cmdHandlers; // 0x60
	private PlayOptions m_playOptions; // 0x68
	private UIPageFinder m_pageFinder; // 0x98
	private ListDict`2 m_narMetas; // 0xa8
	private Int32 m_cachedUnhandledIndex; // 0xb0
	private Boolean m_isInited; // 0xb4
	private TuningChatCoroutineHandler m_coroutineHandler; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_Play; // 0x38
	private static DelegateBridge __Hotfix0_Skip; // 0x40
	private static DelegateBridge __Hotfix0_ResetPlay; // 0x48
	private static DelegateBridge __Hotfix0__SkipImpl; // 0x50
	private static DelegateBridge __Hotfix0__PlayImpl; // 0x58
	private static DelegateBridge __Hotfix0__BaseCommandHandler; // 0x60
	private static DelegateBridge __Hotfix0__PlayModeCommandHandler; // 0x68
	private static DelegateBridge __Hotfix0__CreateDialogItem; // 0x70
	private static DelegateBridge __Hotfix0__CreateTitleItem; // 0x78
	private static DelegateBridge __Hotfix0__CreateDivItem; // 0x80
	private static DelegateBridge __Hotfix0__CreateNarItem; // 0x88
	private static DelegateBridge __Hotfix0__PlayRecordFilter; // 0x90
	private static DelegateBridge __Hotfix0__SkipRecordFilter; // 0x98
	private static DelegateBridge __Hotfix0__CreatePreDelayView; // 0xa0
	private static DelegateBridge __Hotfix0_HandleNarration; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0


	// RVA: 0x2314670 VA: 0x759492c670
	private Void _InitIfNot() { }
	// RVA: 0x231495c VA: 0x759492c95c
	public Void Play(PlayOptions options) { }
	// RVA: 0x2314d20 VA: 0x759492cd20
	public Void Skip() { }
	// RVA: 0x2314fa0 VA: 0x759492cfa0
	public Void ResetPlay() { }
	// RVA: 0x2314e88 VA: 0x759492ce88
	private Void _SkipImpl(PlayOptions options) { }
	// RVA: 0x2314ae8 VA: 0x759492cae8
	private Void _PlayImpl(PlayOptions options, Action`3 filter, Boolean fromScratch) { }
	// RVA: 0x23150d8 VA: 0x759492d0d8
	private IList`1 _BaseCommandHandler(IList`1 commands) { }
	// RVA: 0x231559c VA: 0x759492d59c
	private IList`1 _PlayModeCommandHandler(IList`1 commands) { }
	// RVA: 0x231573c VA: 0x759492d73c
	private ChatItemOptions _CreateDialogItem(Command command) { }
	// RVA: 0x2315a18 VA: 0x759492da18
	private ChatItemOptions _CreateTitleItem(Command command) { }
	// RVA: 0x2315b78 VA: 0x759492db78
	private ChatItemOptions _CreateDivItem(Command command) { }
	// RVA: 0x2315d84 VA: 0x759492dd84
	private ChatItemOptions _CreateNarItem(Command command) { }
	// RVA: 0x231639c VA: 0x759492e39c
	private Void _PlayRecordFilter(IList`1 inputItems, List`1 outputRecords, List`1 outputPlayables) { }
	// RVA: 0x23165e0 VA: 0x759492e5e0
	private Void _SkipRecordFilter(IList`1 inputItems, List`1 outputRecords, List`1 outputPlayables) { }
	// RVA: 0x231502c VA: 0x759492d02c
	private IChatDelayView _CreatePreDelayView() { }
	// RVA: 0x2316a00 VA: 0x759492ea00
	public Void HandleNarration(Int32 index) { }
	// RVA: 0x2316afc VA: 0x759492eafc
	public Void .ctor() { }
	// RVA: 0x2316cdc VA: 0x759492ecdc
	private static Void .cctor() { }
}
```