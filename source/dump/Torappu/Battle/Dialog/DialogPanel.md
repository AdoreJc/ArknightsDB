# DialogPanel

**Namespace:** `Torappu.Battle.Dialog`


## Fields

- `Button _skipButton`

- `Text _charNameText`

- `CanvasGroup _charNameRoot`

- `Transform _contentLeftMount`

- `Transform _contentRightMount`

- `GameObject _blockMask`

- `EventTrigger _mask`

- `AVGTypeWriterText _contentTypeWriter`

- `GameObject _contentDeco`

- `UIAtlasImage _avatarEmpty`

- `Image _avatar`

- `Transform _avatarLeftMount`

- `Transform _avatarRightMount`

- `Single _fadeDuration`

- `Single _fadeInDuration`

- `Single _fadeOutDuration`

- `DialogDecisionButton _optButtonPrefab`

- `CanvasGroup _optButtonRoot`

- `DialogPlaybackPanel _playbackPanel`

- `AnimationWrapper _entryAnimationWrapper`

- `Ease _entryEase`

- `AnimationWrapper _decisionAnimationWrapper`

- `Transform _pluginRoot`

- `CanvasGroup _dialogContent`

- `Single _fastActionDialog`

- `AlphaSplitImageHolder m_characterImgHolderF`

- `AlphaSplitImageHolder m_characterImgHolderB`

- `Coroutine m_mainCoroutine`

- `DialogViewData m_viewData`

- `Int32 <taskCnt>k__BackingField`

- `Boolean m_pluginInited`

- `Action onSkipClicked`

- `Action onMaskClicked`


## Properties

- `DialogViewData viewData`

- `Int32 taskCnt`

- `DialogPlaybackPanel playbackPanel`


## Methods

- `DialogViewData get_viewData()`

- `Int32 get_taskCnt()`

- `Void set_taskCnt(Int32)`

- `DialogPlaybackPanel get_playbackPanel()`

- `Void _AttachPluginExecutors()`

- `Void _InitPluginIfNot()`

- `Void _PrepareMainUI()`

- `IEnumerator _UpdateCommandData(Int32, Boolean)`

- `IEnumerator _RenderView()`

- `Void _RenderDefault()`

- `IEnumerator _DoFadeIn()`

- `IEnumerator _DoFadeOut()`

- `Void _RenderOptions()`

- `Void _RenderName()`

- `Void _RenderLogPanel()`

- `Void _RenderSkipButton()`

- `Boolean _EndProcess()`

- `Void _CompleteTweens()`

- `Void _RenderAvatar()`

- `Void _FadeGraphic(Graphic, Single)`

- `Void _FadeCanvasGroup(CanvasGroup, Single)`

- `Void _RenderContent()`

- `Boolean _CommandIs(String)`

- `Void _OnTypeEnd()`

- `Void _EnableGraphic(String, Boolean, Boolean)`

- `Void OnSkipClicked()`

- `Void OnMaskClicked()`

- `Void OnDisplayLogClicked()`

- `Void _DoUpdateNextCommandAndUpdateView(Boolean)`

- `Boolean _ExecuteUIOperation(Command)`

- `Boolean _ExecuteDelay(Command)`

- `Boolean _ExecuteHeader(Command)`

- `Boolean _ExecuteDialog(Command)`

- `Boolean _ExecuteDecision(Command)`

- `Boolean _ExecuteEnd(Command)`

- `Void _OnExecuteCommand(Command)`

- `Void Update()`

- `Void OnDestroy()`

- `Void <_FadeGraphic>b__72_0()`

- `Void <_FadeCanvasGroup>b__73_0()`

- `BattleDialogType <>xLuaBaseProxy_get_type()`

- `Void <>xLuaBaseProxy_Init()`

- `Void <>xLuaBaseProxy_StartSignal(BattleDialogParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogPanel : DialogExecutorBase
{
	private Button _skipButton; // 0x18
	private Text _charNameText; // 0x20
	private CanvasGroup _charNameRoot; // 0x28
	private Transform _contentLeftMount; // 0x30
	private Transform _contentRightMount; // 0x38
	private GameObject _blockMask; // 0x40
	private EventTrigger _mask; // 0x48
	private AVGTypeWriterText _contentTypeWriter; // 0x50
	private GameObject _contentDeco; // 0x58
	private UIAtlasImage _avatarEmpty; // 0x60
	private Image _avatar; // 0x68
	private Transform _avatarLeftMount; // 0x70
	private Transform _avatarRightMount; // 0x78
	private Single _fadeDuration; // 0x80
	private Single _fadeInDuration; // 0x84
	private Single _fadeOutDuration; // 0x88
	private DialogDecisionButton _optButtonPrefab; // 0x90
	private CanvasGroup _optButtonRoot; // 0x98
	private DialogPlaybackPanel _playbackPanel; // 0xa0
	private AnimationWrapper _entryAnimationWrapper; // 0xa8
	private Ease _entryEase; // 0xb0
	private AnimationWrapper _decisionAnimationWrapper; // 0xb8
	private Transform _pluginRoot; // 0xc0
	private CanvasGroup _dialogContent; // 0xc8
	private Single _fastActionDialog; // 0xd0
	private List`1 _uiOperationTargets; // 0xd8
	private AlphaSplitImageHolder m_characterImgHolderF; // 0xe0
	private AlphaSplitImageHolder m_characterImgHolderB; // 0xe8
	private List`1 m_optButton; // 0xf0
	private Coroutine m_mainCoroutine; // 0xf8
	private DialogViewData m_viewData; // 0x100
	public static readonly List`1 FLOW_COMMAND; // 0x0
	public static readonly List`1 BLOCK_COMMAND; // 0x8
	public static readonly List`1 BLOCK_COMMAND_NOT_SKIPPABLE; // 0x10
	private Int32 <taskCnt>k__BackingField; // 0x108
	public const String EMPTY_CHAR; // 0x0
	private const String DIALOG_ENTRY; // 0x0
	private const String DIALOG_DECISION; // 0x0
	private List`1 m_plugins; // 0x110
	private Boolean m_pluginInited; // 0x118
	public Action onSkipClicked; // 0x120
	public Action onMaskClicked; // 0x128
	public Action`1 onOptSelected; // 0x130
	private Dictionary`2 m_executor; // 0x138
	private static DelegateBridge __Hotfix0_get_viewData; // 0x18
	private static DelegateBridge __Hotfix0_get_taskCnt; // 0x20
	private static DelegateBridge __Hotfix0_set_taskCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_playbackPanel; // 0x30
	private static DelegateBridge __Hotfix0__AttachPluginExecutors; // 0x38
	private static DelegateBridge __Hotfix0__InitPluginIfNot; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48
	private static DelegateBridge __Hotfix0_get_type; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x58
	private static DelegateBridge __Hotfix0__PrepareMainUI; // 0x60
	private static DelegateBridge __Hotfix0_StartSignal; // 0x68
	private static DelegateBridge __Hotfix0__UpdateCommandData; // 0x70
	private static DelegateBridge __Hotfix0__RenderView; // 0x78
	private static DelegateBridge __Hotfix0__RenderDefault; // 0x80
	private static DelegateBridge __Hotfix0__DoFadeIn; // 0x88
	private static DelegateBridge __Hotfix0__DoFadeOut; // 0x90
	private static DelegateBridge __Hotfix0__RenderOptions; // 0x98
	private static DelegateBridge __Hotfix0__RenderName; // 0xa0
	private static DelegateBridge __Hotfix0__RenderLogPanel; // 0xa8
	private static DelegateBridge __Hotfix0__RenderSkipButton; // 0xb0
	private static DelegateBridge __Hotfix0__EndProcess; // 0xb8
	private static DelegateBridge __Hotfix0__CompleteTweens; // 0xc0
	private static DelegateBridge __Hotfix0__RenderAvatar; // 0xc8
	private static DelegateBridge __Hotfix0__FadeGraphic; // 0xd0
	private static DelegateBridge __Hotfix0__FadeCanvasGroup; // 0xd8
	private static DelegateBridge __Hotfix0__RenderContent; // 0xe0
	private static DelegateBridge __Hotfix0__CommandIs; // 0xe8
	private static DelegateBridge __Hotfix0__OnTypeEnd; // 0xf0
	private static DelegateBridge __Hotfix0__EnableGraphic; // 0xf8
	private static DelegateBridge __Hotfix0_OnSkipClicked; // 0x100
	private static DelegateBridge __Hotfix0_OnMaskClicked; // 0x108
	private static DelegateBridge __Hotfix0_OnDisplayLogClicked; // 0x110
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x118
	private static DelegateBridge __Hotfix0__DoUpdateNextCommandAndUpdateView; // 0x120
	private static DelegateBridge __Hotfix0__ExecuteUIOperation; // 0x128
	private static DelegateBridge __Hotfix0__ExecuteDelay; // 0x130
	private static DelegateBridge __Hotfix0__ExecuteHeader; // 0x138
	private static DelegateBridge __Hotfix0__ExecuteDialog; // 0x140
	private static DelegateBridge __Hotfix0__ExecuteDecision; // 0x148
	private static DelegateBridge __Hotfix0__ExecuteEnd; // 0x150
	private static DelegateBridge __Hotfix0__OnExecuteCommand; // 0x158
	private static DelegateBridge __Hotfix0_Update; // 0x160
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x168

	public DialogViewData viewData { get; }
	private Int32 taskCnt { get; set; }
	public DialogPlaybackPanel playbackPanel { get; }
	public override BattleDialogType type { get; }

	// RVA: 0x1d20db0 VA: 0x7594338db0
	public DialogViewData get_viewData() { }
	// RVA: 0x1d20e28 VA: 0x7594338e28
	private Int32 get_taskCnt() { }
	// RVA: 0x1d20ea0 VA: 0x7594338ea0
	private Void set_taskCnt(Int32 value) { }
	// RVA: 0x1d20f2c VA: 0x7594338f2c
	public DialogPlaybackPanel get_playbackPanel() { }
	// RVA: 0x1d20fa4 VA: 0x7594338fa4
	private Void _AttachPluginExecutors() { }
	// RVA: 0x1d21438 VA: 0x7594339438
	private Void _InitPluginIfNot() { }
	// RVA: 0x1d216a4 VA: 0x75943396a4
	public Void .ctor() { }
	// RVA: 0x1d217fc VA: 0x75943397fc
	public override BattleDialogType get_type() { }
	// RVA: 0x1d21874 VA: 0x7594339874
	public override Void Init() { }
	// RVA: 0x1d21af4 VA: 0x7594339af4
	private Void _PrepareMainUI() { }
	// RVA: 0x1d21e38 VA: 0x7594339e38
	public override Void StartSignal(BattleDialogParam param) { }
	// RVA: 0x1d2200c VA: 0x759433a00c
	private IEnumerator _UpdateCommandData(Int32 decision, Boolean isSkip) { }
	// RVA: 0x1d22118 VA: 0x759433a118
	private IEnumerator _RenderView() { }
	// RVA: 0x1d221fc VA: 0x759433a1fc
	private Void _RenderDefault() { }
	// RVA: 0x1d22ff4 VA: 0x759433aff4
	private IEnumerator _DoFadeIn() { }
	// RVA: 0x1d230d8 VA: 0x759433b0d8
	private IEnumerator _DoFadeOut() { }
	// RVA: 0x1d2284c VA: 0x759433a84c
	private Void _RenderOptions() { }
	// RVA: 0x1d22cd8 VA: 0x759433acd8
	private Void _RenderName() { }
	// RVA: 0x1d22e34 VA: 0x759433ae34
	private Void _RenderLogPanel() { }
	// RVA: 0x1d22ee4 VA: 0x759433aee4
	private Void _RenderSkipButton() { }
	// RVA: 0x1d236e0 VA: 0x759433b6e0
	public Boolean _EndProcess() { }
	// RVA: 0x1d23788 VA: 0x759433b788
	private Void _CompleteTweens() { }
	// RVA: 0x1d2229c VA: 0x759433a29c
	private Void _RenderAvatar() { }
	// RVA: 0x1d23554 VA: 0x759433b554
	private Void _FadeGraphic(Graphic slot, Single alpha) { }
	// RVA: 0x1d23264 VA: 0x759433b264
	private Void _FadeCanvasGroup(CanvasGroup slot, Single alpha) { }
	// RVA: 0x1d22604 VA: 0x759433a604
	private Void _RenderContent() { }
	// RVA: 0x1d231bc VA: 0x759433b1bc
	private Boolean _CommandIs(String val) { }
	// RVA: 0x1d23dfc VA: 0x759433bdfc
	private Void _OnTypeEnd() { }
	// RVA: 0x1d23a58 VA: 0x759433ba58
	private Void _EnableGraphic(String target, Boolean enable, Boolean withoutFade) { }
	// RVA: 0x1d24090 VA: 0x759433c090
	public Void OnSkipClicked() { }
	// RVA: 0x1d24140 VA: 0x759433c140
	public Void OnMaskClicked() { }
	// RVA: 0x1d24218 VA: 0x759433c218
	public Void OnDisplayLogClicked() { }
	// RVA: 0x1d243b8 VA: 0x759433c3b8
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x1d21f08 VA: 0x7594339f08
	private Void _DoUpdateNextCommandAndUpdateView(Boolean isSkip) { }
	// RVA: 0x1d24764 VA: 0x759433c764
	private Boolean _ExecuteUIOperation(Command command) { }
	// RVA: 0x1d2488c VA: 0x759433c88c
	private Boolean _ExecuteDelay(Command command) { }
	// RVA: 0x1d24954 VA: 0x759433c954
	private Boolean _ExecuteHeader(Command command) { }
	// RVA: 0x1d249e0 VA: 0x759433c9e0
	private Boolean _ExecuteDialog(Command command) { }
	// RVA: 0x1d24e08 VA: 0x759433ce08
	private Boolean _ExecuteDecision(Command command) { }
	// RVA: 0x1d24ec8 VA: 0x759433cec8
	private Boolean _ExecuteEnd(Command command) { }
	// RVA: 0x1d24f54 VA: 0x759433cf54
	private Void _OnExecuteCommand(Command command) { }
	// RVA: 0x1d25004 VA: 0x759433d004
	private Void Update() { }
	// RVA: 0x1d25120 VA: 0x759433d120
	private Void OnDestroy() { }
	// RVA: 0x1d251c4 VA: 0x759433d1c4
	private static Void .cctor() { }
	// RVA: 0x1d2566c VA: 0x759433d66c
	private Void <_FadeGraphic>b__72_0() { }
	// RVA: 0x1d25688 VA: 0x759433d688
	private Void <_FadeCanvasGroup>b__73_0() { }
	// RVA: 0x1d256a4 VA: 0x759433d6a4
	private BattleDialogType <>xLuaBaseProxy_get_type() { }
	// RVA: 0x1d256a8 VA: 0x759433d6a8
	private Void <>xLuaBaseProxy_Init() { }
	// RVA: 0x1d256ac VA: 0x759433d6ac
	private Void <>xLuaBaseProxy_StartSignal(BattleDialogParam P0) { }
	// RVA: 0x1d256b4 VA: 0x759433d6b4
	private Dictionary`2 <>xLuaBaseProxy_GetExecutors() { }
}
```