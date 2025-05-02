# SubtitlePanel

**Namespace:** `Torappu.AVG`


## Fields

- `AVGTypeWriterText _typeWriter`

- `Single _hideDuration`

- `Single _autoWaitBaseTime`

- `Single _autoWaitTimePerText`

- `Ease _hideEase`

- `Text _message`

- `RectTransform _textTransform`

- `Boolean m_hidden`

- `CanvasGroup m_CanvasGroup`


## Properties

- `Boolean isHidden`

- `Boolean isTyping`


## Methods

- `Boolean get_isHidden()`

- `Void set_isHidden(Boolean)`

- `Boolean get_isTyping()`

- `Void Awake()`

- `Boolean _ExecuteSubtitle(Command)`

- `Void _OnTypeWriterEnd()`

- `Void _SetTypeWriterDelay(Object)`

- `Void _SetHiddenInternal(Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnStoryBegin(Story)`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class SubtitlePanel : ExecutorComponent
{
	private const Single SCREEN_WIDTH; // 0x0
	private const Single SCREEN_HEIGHT; // 0x0
	private AVGTypeWriterText _typeWriter; // 0x50
	private Single _hideDuration; // 0x58
	private Single _autoWaitBaseTime; // 0x5c
	private Single _autoWaitTimePerText; // 0x60
	private Ease _hideEase; // 0x64
	private Text _message; // 0x68
	private RectTransform _textTransform; // 0x70
	private Boolean m_hidden; // 0x78
	private CanvasGroup m_CanvasGroup; // 0x80
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_get_isHidden; // 0x8
	private static DelegateBridge __Hotfix0_set_isHidden; // 0x10
	private static DelegateBridge __Hotfix0_get_isTyping; // 0x18
	private static DelegateBridge __Hotfix0_Awake; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteSubtitle; // 0x28
	private static DelegateBridge __Hotfix0__OnTypeWriterEnd; // 0x30
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x38
	private static DelegateBridge __Hotfix0__OnClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnStoryBegin; // 0x48
	private static DelegateBridge __Hotfix0_OnFinish; // 0x50
	private static DelegateBridge __Hotfix0_OnReset; // 0x58
	private static DelegateBridge __Hotfix0__SetTypeWriterDelay; // 0x60
	private static DelegateBridge __Hotfix0__SetHiddenInternal; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean isHidden { get; set; }
	public Boolean isTyping { get; }

	// RVA: 0x3e902ec VA: 0x75964a82ec
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e90428 VA: 0x75964a8428
	public Boolean get_isHidden() { }
	// RVA: 0x3e90490 VA: 0x75964a8490
	private Void set_isHidden(Boolean value) { }
	// RVA: 0x3e906a4 VA: 0x75964a86a4
	public Boolean get_isTyping() { }
	// RVA: 0x3e90718 VA: 0x75964a8718
	private Void Awake() { }
	// RVA: 0x3e907dc VA: 0x75964a87dc
	protected Boolean _ExecuteSubtitle(Command command) { }
	// RVA: 0x3e90db0 VA: 0x75964a8db0
	private Void _OnTypeWriterEnd() { }
	// RVA: 0x3e90f18 VA: 0x75964a8f18
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e90f8c VA: 0x75964a8f8c
	protected virtual Void _OnClicked(Object arg) { }
	// RVA: 0x3e910a0 VA: 0x75964a90a0
	public override Void OnStoryBegin(Story story) { }
	// RVA: 0x3e9127c VA: 0x75964a927c
	protected override Void OnFinish() { }
	// RVA: 0x3e91380 VA: 0x75964a9380
	public override Void OnReset() { }
	// RVA: 0x3e911c8 VA: 0x75964a91c8
	private Void _SetTypeWriterDelay(Object arg) { }
	// RVA: 0x3e90514 VA: 0x75964a8514
	private Void _SetHiddenInternal(Boolean value, Boolean force) { }
	// RVA: 0x3e9150c VA: 0x75964a950c
	public Void .ctor() { }
	// RVA: 0x3e915a0 VA: 0x75964a95a0
	private Void <>xLuaBaseProxy_OnStoryBegin(Story P0) { }
	// RVA: 0x3e915a8 VA: 0x75964a95a8
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x3e915b0 VA: 0x75964a95b0
	private Void <>xLuaBaseProxy_OnReset() { }
}
```