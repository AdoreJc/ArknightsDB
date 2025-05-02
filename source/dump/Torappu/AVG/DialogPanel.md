# DialogPanel

**Namespace:** `Torappu.AVG`


## Fields

- `Text _name`

- `AVGTypeWriterText _typeWriter`

- `Single _hideDuration`

- `Single _autoWaitBaseTime`

- `Single _autoWaitTimePerText`

- `Ease _hideEase`

- `Text _message`

- `Single _messageBottomPadding`

- `Single _messageTextMaxHeight`

- `Single _nameTextMaxHeight`

- `Boolean m_hidden`

- `Single m_messageOriginYPos`

- `Single m_messageOriginXPos`

- `Single m_nameOriginYPos`

- `CanvasGroup m_canvasGroup`

- `Boolean m_ismultiline`

- `String m_cachedMultiline`

- `Boolean m_multilineEnd`


## Properties

- `Boolean isHidden`

- `Boolean isTyping`


## Methods

- `Boolean get_isHidden()`

- `Void set_isHidden(Boolean)`

- `Boolean get_isTyping()`

- `Void _SetTypeWriterDelay(Object)`

- `Void _AdjustMessagePosition(String)`

- `Boolean _ExecuteAside(Command)`

- `Boolean _ExecuteDialog(Command)`

- `Boolean _ExecuteMultiline(Command)`

- `Void _ResetMultiline()`

- `Single _CalculateTextHeight(Text, String)`

- `Void _OnTypeWriterEnd()`

- `Void _SetHiddenInternal(Boolean, Boolean)`

- `Void Awake()`

- `Void <>xLuaBaseProxy_OnStoryBegin(Story)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class DialogPanel : ExecutorComponent
{
	private const Single MESSAGE_ASIDE_X_POS; // 0x0
	private Text _name; // 0x50
	private AVGTypeWriterText _typeWriter; // 0x58
	private Single _hideDuration; // 0x60
	private Single _autoWaitBaseTime; // 0x64
	private Single _autoWaitTimePerText; // 0x68
	private Ease _hideEase; // 0x6c
	private Text _message; // 0x70
	private Single _messageBottomPadding; // 0x78
	private Single _messageTextMaxHeight; // 0x7c
	private Single _nameTextMaxHeight; // 0x80
	private Boolean m_hidden; // 0x84
	private Single m_messageOriginYPos; // 0x88
	private Single m_messageOriginXPos; // 0x8c
	private Single m_nameOriginYPos; // 0x90
	private CanvasGroup m_canvasGroup; // 0x98
	private Boolean m_ismultiline; // 0xa0
	private String m_cachedMultiline; // 0xa8
	private Boolean m_multilineEnd; // 0xb0
	private static DelegateBridge __Hotfix0_get_isHidden; // 0x0
	private static DelegateBridge __Hotfix0_set_isHidden; // 0x8
	private static DelegateBridge __Hotfix0_get_isTyping; // 0x10
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x18
	private static DelegateBridge __Hotfix0_OnStoryBegin; // 0x20
	private static DelegateBridge __Hotfix0_OnReset; // 0x28
	private static DelegateBridge __Hotfix0__SetTypeWriterDelay; // 0x30
	private static DelegateBridge __Hotfix0__AdjustMessagePosition; // 0x38
	private static DelegateBridge __Hotfix0__ExecuteAside; // 0x40
	private static DelegateBridge __Hotfix0__ExecuteDialog; // 0x48
	private static DelegateBridge __Hotfix0__ExecuteMultiline; // 0x50
	private static DelegateBridge __Hotfix0__ResetMultiline; // 0x58
	private static DelegateBridge __Hotfix0__CalculateTextHeight; // 0x60
	private static DelegateBridge __Hotfix0_OnFinish; // 0x68
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x70
	private static DelegateBridge __Hotfix0__OnClicked; // 0x78
	private static DelegateBridge __Hotfix0__OnTypeWriterEnd; // 0x80
	private static DelegateBridge __Hotfix0__SetHiddenInternal; // 0x88
	private static DelegateBridge __Hotfix0_Awake; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public Boolean isHidden { get; set; }
	public Boolean isTyping { get; }

	// RVA: 0x3e833d4 VA: 0x759649b3d4
	public Boolean get_isHidden() { }
	// RVA: 0x3e8343c VA: 0x759649b43c
	private Void set_isHidden(Boolean value) { }
	// RVA: 0x3e83650 VA: 0x759649b650
	public Boolean get_isTyping() { }
	// RVA: 0x3e836c4 VA: 0x759649b6c4
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e838c4 VA: 0x759649b8c4
	public override Void OnStoryBegin(Story story) { }
	// RVA: 0x3e83aa0 VA: 0x759649baa0
	public override Void OnReset() { }
	// RVA: 0x3e839ec VA: 0x759649b9ec
	private Void _SetTypeWriterDelay(Object arg) { }
	// RVA: 0x3e83c64 VA: 0x759649bc64
	private Void _AdjustMessagePosition(String content) { }
	// RVA: 0x3e83e64 VA: 0x759649be64
	private Boolean _ExecuteAside(Command command) { }
	// RVA: 0x3e842c8 VA: 0x759649c2c8
	private Boolean _ExecuteDialog(Command command) { }
	// RVA: 0x3e84664 VA: 0x759649c664
	private Boolean _ExecuteMultiline(Command command) { }
	// RVA: 0x3e840c8 VA: 0x759649c0c8
	private Void _ResetMultiline() { }
	// RVA: 0x3e8417c VA: 0x759649c17c
	private Single _CalculateTextHeight(Text textComponent, String text) { }
	// RVA: 0x3e84bc4 VA: 0x759649cbc4
	protected override Void OnFinish() { }
	// RVA: 0x3e84cc8 VA: 0x759649ccc8
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e84d3c VA: 0x759649cd3c
	protected virtual Void _OnClicked(Object arg) { }
	// RVA: 0x3e84e68 VA: 0x759649ce68
	private Void _OnTypeWriterEnd() { }
	// RVA: 0x3e834c0 VA: 0x759649b4c0
	private Void _SetHiddenInternal(Boolean value, Boolean force) { }
	// RVA: 0x3e84f14 VA: 0x759649cf14
	private Void Awake() { }
	// RVA: 0x3e85004 VA: 0x759649d004
	public Void .ctor() { }
	// RVA: 0x3e850e4 VA: 0x759649d0e4
	private Void <>xLuaBaseProxy_OnStoryBegin(Story P0) { }
	// RVA: 0x3e850ec VA: 0x759649d0ec
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e850f4 VA: 0x759649d0f4
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```