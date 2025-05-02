# AVGChatBoxController

**Namespace:** `Torappu.AVG`


## Fields

- `UIChatBoxView _chatBox`

- `AVGParser m_parser`

- `PlayContext m_activePlay`


## Methods

- `Boolean Play(PlayOptions)`

- `Boolean IsPlaying()`

- `Void InterruptPlaying()`

- `Void SetPauseIfPlaying(Boolean)`

- `Boolean Log(LogOptions)`

- `Void Reset()`

- `Void OnEnable()`

- `Void EventOnContentClicked()`

- `Boolean _PlayImpl(PlayOptions)`

- `Void _CancelPlaying()`

- `Boolean _LogImpl(LogOptions)`

- `IEnumerator _PlayCoroutine()`

- `Boolean _SearchInsertForRecord(ChatItemOptions, Boolean)`

- `Boolean _SearchInsertForPlayable(ChatItemOptions, Boolean)`

- `IEnumerator _TraverseCoroutine(PlayHandler, Boolean)`

- `Void _OnChatEnd()`

- `Void _OnPlayFinish()`

- `String _LoadScriptContent(String)`

- `IEnumerator _WaitForNextClick(Single)`

- `Void _FilterRecorded(Action`3, IList`1, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGChatBoxController : MonoBehaviour, IHotfixable
{
	private UIChatBoxView _chatBox; // 0x18
	private AVGParser m_parser; // 0x20
	private PlayContext m_activePlay; // 0x28
	private static DelegateBridge __Hotfix0_Play; // 0x0
	private static DelegateBridge __Hotfix0_IsPlaying; // 0x8
	private static DelegateBridge __Hotfix0_InterruptPlaying; // 0x10
	private static DelegateBridge __Hotfix0_SetPauseIfPlaying; // 0x18
	private static DelegateBridge __Hotfix0_Log; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge __Hotfix0_EventOnContentClicked; // 0x38
	private static DelegateBridge __Hotfix0__PlayImpl; // 0x40
	private static DelegateBridge __Hotfix0__CancelPlaying; // 0x48
	private static DelegateBridge __Hotfix0__LogImpl; // 0x50
	private static DelegateBridge __Hotfix0__LoadViewsFromScript; // 0x58
	private static DelegateBridge __Hotfix0__CreateAVGParser; // 0x60
	private static DelegateBridge __Hotfix0__PlayCoroutine; // 0x68
	private static DelegateBridge __Hotfix0__SearchInsertForRecord; // 0x70
	private static DelegateBridge __Hotfix0__SearchInsertForPlayable; // 0x78
	private static DelegateBridge __Hotfix0__ExtractRecords; // 0x80
	private static DelegateBridge __Hotfix0__TraverseCoroutine; // 0x88
	private static DelegateBridge __Hotfix0__PlayItemCoroutine; // 0x90
	private static DelegateBridge __Hotfix0__OnChatEnd; // 0x98
	private static DelegateBridge __Hotfix0__OnPlayFinish; // 0xa0
	private static DelegateBridge __Hotfix0__LoadScriptContent; // 0xa8
	private static DelegateBridge __Hotfix0__WaitForNextClick; // 0xb0
	private static DelegateBridge __Hotfix0__FilterRecorded; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0


	// RVA: 0x3eafaf8 VA: 0x75964c7af8
	public Boolean Play(PlayOptions options) { }
	// RVA: 0x3eaff80 VA: 0x75964c7f80
	public Boolean IsPlaying() { }
	// RVA: 0x3eb0000 VA: 0x75964c8000
	public Void InterruptPlaying() { }
	// RVA: 0x3eb0068 VA: 0x75964c8068
	public Void SetPauseIfPlaying(Boolean isPaused) { }
	// RVA: 0x3eb00e8 VA: 0x75964c80e8
	public Boolean Log(LogOptions options) { }
	// RVA: 0x3eb0690 VA: 0x75964c8690
	public Void Reset() { }
	// RVA: 0x3eb071c VA: 0x75964c871c
	private Void OnEnable() { }
	// RVA: 0x3eb07d4 VA: 0x75964c87d4
	public Void EventOnContentClicked() { }
	// RVA: 0x3eafc70 VA: 0x75964c7c70
	private Boolean _PlayImpl(PlayOptions options) { }
	// RVA: 0x3eafbac VA: 0x75964c7bac
	private Void _CancelPlaying() { }
	// RVA: 0x3eb0188 VA: 0x75964c8188
	private Boolean _LogImpl(LogOptions options) { }
	// RVA: 0x3eb0944 VA: 0x75964c8944
	private IList`1 _LoadViewsFromScript(String storyId, Func`2 cmdHandler) { }
	// RVA: 0x3eb0e08 VA: 0x75964c8e08
	private static AVGParser _CreateAVGParser() { }
	// RVA: 0x3eb0850 VA: 0x75964c8850
	private IEnumerator _PlayCoroutine() { }
	// RVA: 0x3eb0fd4 VA: 0x75964c8fd4
	private Boolean _SearchInsertForRecord(ChatItemOptions record, Boolean needSkip) { }
	// RVA: 0x3eb15b4 VA: 0x75964c95b4
	private Boolean _SearchInsertForPlayable(ChatItemOptions playable, Boolean needSkip) { }
	// RVA: 0x3eb1778 VA: 0x75964c9778
	private static Void _ExtractRecords(List`1 doubtingRecords, List`1 recordedViews) { }
	// RVA: 0x3eb1950 VA: 0x75964c9950
	private IEnumerator _TraverseCoroutine(PlayHandler playHandler, Boolean needSkip) { }
	// RVA: 0x3eb1a58 VA: 0x75964c9a58
	private static IEnumerator _PlayItemCoroutine(PlayHandler playHandler, ChatItemOptions playable, IChatDelayView preDelayView) { }
	// RVA: 0x3eb1b88 VA: 0x75964c9b88
	private Void _OnChatEnd() { }
	// RVA: 0x3eb1c0c VA: 0x75964c9c0c
	private Void _OnPlayFinish() { }
	// RVA: 0x3eb0a64 VA: 0x75964c8a64
	private String _LoadScriptContent(String id) { }
	// RVA: 0x3eb1c7c VA: 0x75964c9c7c
	private IEnumerator _WaitForNextClick(Single timeout) { }
	// RVA: 0x3eb1344 VA: 0x75964c9344
	private Void _FilterRecorded(Action`3 filter, IList`1 items, out Boolean meetPlayable) { }
	// RVA: 0x3eb1d68 VA: 0x75964c9d68
	public Void .ctor() { }
}
```