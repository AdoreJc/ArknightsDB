# PlaybackPanel

**Namespace:** `Torappu.AVG`


## Fields

- `AVGPlaybackTextView _avgPlaybackTextView`

- `ScrollRect _scrollView`

- `UIRecycleLayoutGroup _content`

- `ContentSizeFitterHelper _fitterHelper`

- `GameObject _closeBtn`

- `CanvasGroup m_canvasGroup`

- `UISwitchTween m_playbackTween`

- `Adapter m_innerAdapter`

- `Boolean m_isProcessingMultiline`

- `StringBuilder m_cachedStrBuilder`

- `Options m_multilineOption`

- `VirtualView m_multilineView`


## Properties

- `Adapter adapter`

- `CanvasGroup canvasGroup`

- `UISwitchTween fadeSwitchTween`

- `Boolean isShown`


## Methods

- `Adapter get_adapter()`

- `Void OnPointerClick(PointerEventData)`

- `Boolean _ExecuteDialog(Command)`

- `Boolean _ExecuteDecision(Command)`

- `Boolean _ExecutePredicate(Command)`

- `Boolean _ExecuteSubtitle(Command)`

- `Boolean _ExecuteAside(Command)`

- `Boolean _ExecuteMultiline(Command)`

- `Void _TryEndMultilineMode()`

- `Boolean _ExecuteSticker(Command)`

- `Boolean _ExecuteAnimText(Command)`

- `Void _ResetLastCurrentIcon()`

- `CanvasGroup get_canvasGroup()`

- `UISwitchTween get_fadeSwitchTween()`

- `Void _UpdateShown(Boolean, Boolean)`

- `Void _ResetScrollSlide()`

- `Boolean get_isShown()`

- `Void set_isShown(Boolean)`

- `Void OnCloseBtnClicked()`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class PlaybackPanel : ExecutorComponent, IPointerClickHandler, IEventSystemHandler
{
	private const String PARAM_NAME_OPTIONS; // 0x0
	private const String COMMAND_NAME_DECISION; // 0x0
	private const String COMMAND_NAME_PREDICATE; // 0x0
	private const String COMMAND_SUBTITLE; // 0x0
	private const String COMMAND_STICKER; // 0x0
	private const String COMMAND_ANIMTEXT; // 0x0
	private AVGPlaybackTextView _avgPlaybackTextView; // 0x50
	private ScrollRect _scrollView; // 0x58
	private UIRecycleLayoutGroup _content; // 0x60
	private ContentSizeFitterHelper _fitterHelper; // 0x68
	private GameObject _closeBtn; // 0x70
	private CanvasGroup m_canvasGroup; // 0x78
	private UISwitchTween m_playbackTween; // 0x80
	private Adapter m_innerAdapter; // 0x88
	private ListDict`2 m_cachedAnimTextContent; // 0x90
	private Boolean m_isProcessingMultiline; // 0x98
	private StringBuilder m_cachedStrBuilder; // 0xa0
	private Options m_multilineOption; // 0xa8
	private VirtualView m_multilineView; // 0xd8
	private static DelegateBridge __Hotfix0_get_adapter; // 0x0
	private static DelegateBridge __Hotfix0_OnPointerClick; // 0x8
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x10
	private static DelegateBridge __Hotfix0_OnReset; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteDialog; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteDecision; // 0x28
	private static DelegateBridge __Hotfix0__ExecutePredicate; // 0x30
	private static DelegateBridge __Hotfix0__ExecuteSubtitle; // 0x38
	private static DelegateBridge __Hotfix0__ExecuteAside; // 0x40
	private static DelegateBridge __Hotfix0__ExecuteMultiline; // 0x48
	private static DelegateBridge __Hotfix0__TryEndMultilineMode; // 0x50
	private static DelegateBridge __Hotfix0__ExecuteSticker; // 0x58
	private static DelegateBridge __Hotfix0__ExecuteAnimText; // 0x60
	private static DelegateBridge __Hotfix0__ResetLastCurrentIcon; // 0x68
	private static DelegateBridge __Hotfix0_get_canvasGroup; // 0x70
	private static DelegateBridge __Hotfix0_get_fadeSwitchTween; // 0x78
	private static DelegateBridge __Hotfix0__UpdateShown; // 0x80
	private static DelegateBridge __Hotfix0__ResetScrollSlide; // 0x88
	private static DelegateBridge __Hotfix0_get_isShown; // 0x90
	private static DelegateBridge __Hotfix0_set_isShown; // 0x98
	private static DelegateBridge __Hotfix0_OnCloseBtnClicked; // 0xa0
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	protected Adapter adapter { get; }
	private CanvasGroup canvasGroup { get; }
	private UISwitchTween fadeSwitchTween { get; }
	public Boolean isShown { get; set; }

	// RVA: 0x3e8a650 VA: 0x75964a2650
	protected Adapter get_adapter() { }
	// RVA: 0x3e8a84c VA: 0x75964a284c
	public Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x3e8a8c4 VA: 0x75964a28c4
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e8ac90 VA: 0x75964a2c90
	public override Void OnReset() { }
	// RVA: 0x3e8af54 VA: 0x75964a2f54
	private Boolean _ExecuteDialog(Command command) { }
	// RVA: 0x3e8b4cc VA: 0x75964a34cc
	private Boolean _ExecuteDecision(Command command) { }
	// RVA: 0x3e8b6e4 VA: 0x75964a36e4
	private Boolean _ExecutePredicate(Command command) { }
	// RVA: 0x3e8b884 VA: 0x75964a3884
	private Boolean _ExecuteSubtitle(Command command) { }
	// RVA: 0x3e8bbac VA: 0x75964a3bac
	private Boolean _ExecuteAside(Command command) { }
	// RVA: 0x3e8bdac VA: 0x75964a3dac
	private Boolean _ExecuteMultiline(Command command) { }
	// RVA: 0x3e8b218 VA: 0x75964a3218
	private Void _TryEndMultilineMode() { }
	// RVA: 0x3e8c1b4 VA: 0x75964a41b4
	private Boolean _ExecuteSticker(Command command) { }
	// RVA: 0x3e8c4d8 VA: 0x75964a44d8
	private Boolean _ExecuteAnimText(Command command) { }
	// RVA: 0x3e8b2a8 VA: 0x75964a32a8
	private Void _ResetLastCurrentIcon() { }
	// RVA: 0x3e8c938 VA: 0x75964a4938
	private CanvasGroup get_canvasGroup() { }
	// RVA: 0x3e8ca10 VA: 0x75964a4a10
	private UISwitchTween get_fadeSwitchTween() { }
	// RVA: 0x3e8ae84 VA: 0x75964a2e84
	private Void _UpdateShown(Boolean value, Boolean force) { }
	// RVA: 0x3e8cb5c VA: 0x75964a4b5c
	private Void _ResetScrollSlide() { }
	// RVA: 0x3e8cae4 VA: 0x75964a4ae4
	public Boolean get_isShown() { }
	// RVA: 0x3e8cbd4 VA: 0x75964a4bd4
	public Void set_isShown(Boolean value) { }
	// RVA: 0x3e8cc58 VA: 0x75964a4c58
	public Void OnCloseBtnClicked() { }
	// RVA: 0x3e8ccf0 VA: 0x75964a4cf0
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e8cd54 VA: 0x75964a4d54
	public Void .ctor() { }
	// RVA: 0x3e8ce18 VA: 0x75964a4e18
	private Void <>xLuaBaseProxy_OnReset() { }
}
```