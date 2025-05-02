# RoguelikePlayChatView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeChatController _chatPrefab`

- `RectTransform _chatContainer`

- `GameObject _panelPlaying`

- `GameObject _panelPlayed`

- `UIAnimationLocation _animShow`

- `CanvasGroup _alphaHandler`

- `Param m_param`

- `Boolean m_waitForQuitTransition`

- `Boolean m_forceQuit`

- `Boolean m_isInited`

- `RoguelikeChatController m_chatInst`


## Methods

- `Void _InitIfNot()`

- `Param _PrepareBeforeChatTrans(TransOptions)`

- `Void EventOnSkipClicked()`

- `Void EventOnCloseClicked()`

- `Void EventOnExitRogueClicked()`

- `Void _NotifyWaitQuitTransition()`

- `IEnumerator _WaitForQuitTransition()`

- `Void _ForceQuit()`

- `Void _UpdateUI(PlayStatus)`

- `Void <EventOnSkipClicked>b__21_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikePlayChatView : SubTransitionBase`1
{
	private const Single PLAY_DELAY; // 0x0
	private RoguelikeChatController _chatPrefab; // 0x18
	private RectTransform _chatContainer; // 0x20
	private GameObject _panelPlaying; // 0x28
	private GameObject _panelPlayed; // 0x30
	private UIAnimationLocation _animShow; // 0x38
	private CanvasGroup _alphaHandler; // 0x48
	private Param m_param; // 0x50
	private Boolean m_waitForQuitTransition; // 0x58
	private Boolean m_forceQuit; // 0x59
	private Boolean m_isInited; // 0x5a
	private RoguelikeChatController m_chatInst; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__PrepareBeforeChatTrans; // 0x8
	private static DelegateBridge __Hotfix0_GetParam; // 0x10
	private static DelegateBridge __Hotfix0_SetParam; // 0x18
	private static DelegateBridge __Hotfix0_GetTransType; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge __Hotfix0_TransCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_EventOnSkipClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnExitRogueClicked; // 0x48
	private static DelegateBridge __Hotfix0__NotifyWaitQuitTransition; // 0x50
	private static DelegateBridge __Hotfix0__WaitForQuitTransition; // 0x58
	private static DelegateBridge __Hotfix0__ForceQuit; // 0x60
	private static DelegateBridge __Hotfix0__UpdateUI; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x29e9104 VA: 0x7595001104
	private Void _InitIfNot() { }
	// RVA: 0x29e91ec VA: 0x75950011ec
	private Param _PrepareBeforeChatTrans(TransOptions options) { }
	// RVA: 0x29e9468 VA: 0x7595001468
	protected override Param GetParam(TransOptions transOptions) { }
	// RVA: 0x29e9528 VA: 0x7595001528
	protected override Void SetParam(Param param) { }
	// RVA: 0x29e95ac VA: 0x75950015ac
	public override SubTransType GetTransType() { }
	// RVA: 0x29e9614 VA: 0x7595001614
	public override Void Reset() { }
	// RVA: 0x29e9814 VA: 0x7595001814
	public override IEnumerator TransCoroutine() { }
	// RVA: 0x29e98e8 VA: 0x75950018e8
	public Void EventOnSkipClicked() { }
	// RVA: 0x29e9b14 VA: 0x7595001b14
	public Void EventOnCloseClicked() { }
	// RVA: 0x29e9bb8 VA: 0x7595001bb8
	public Void EventOnExitRogueClicked() { }
	// RVA: 0x29e9cb0 VA: 0x7595001cb0
	private Void _NotifyWaitQuitTransition() { }
	// RVA: 0x29e9d18 VA: 0x7595001d18
	private IEnumerator _WaitForQuitTransition() { }
	// RVA: 0x29e9dec VA: 0x7595001dec
	private Void _ForceQuit() { }
	// RVA: 0x29e9718 VA: 0x7595001718
	private Void _UpdateUI(PlayStatus status) { }
	// RVA: 0x29e9eb0 VA: 0x7595001eb0
	public Void .ctor() { }
	// RVA: 0x29e9f40 VA: 0x7595001f40
	private Void <EventOnSkipClicked>b__21_0() { }
}
```