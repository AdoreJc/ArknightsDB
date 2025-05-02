# SandboxV2DungeonAVGAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonPage _page`

- `SandboxV2DungeonController _controller`

- `StateEngine _stateEngine`

- `SandboxV2FloatPanelManager _floatPanelManager`

- `Coroutine m_coroutine`

- `Int32 m_guideStartMsgSeq`

- `String m_currWaitingGuideStartMsgId`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Boolean _ExecuteEnsureDungeonQuest(Command)`

- `Boolean _ExecuteEnsureDungeonStable(Command)`

- `IEnumerator _CoroutineEnsureDungeonStable()`

- `Void TriggerWhenDialogQueueCompleted(String)`

- `Boolean _ExecuteDungeonFocusNode(Command)`

- `IEnumerator _CoroutineDungeonFocusNode(String)`

- `IEnumerator _CoroutineCameraZoom(ZoomType, String)`

- `Boolean _ExecuteDungeonBackToDungeonState(Command)`

- `IEnumerator _CoroutineDungeonBackToDungeonState()`

- `Boolean _ExecuteOpenGainItemPage(Command)`

- `Boolean _ExecuteCloseGainItemPage(Command)`

- `IEnumerator _CoroutineCloseGainItemPage()`

- `Boolean _ExecuteSettleGameAndLeave(Command)`

- `Void <_ExecuteSettleGameAndLeave>b__26_0(SandboxV2SettleGameResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonAVGAdapter : ExecutorComponent
{
	private const Single FOCUS_NODE_WAIT_TIME; // 0x0
	private const Single NODE_PREVIEW_FADE_OUT_WAIT_TIME; // 0x0
	private SandboxV2DungeonPage _page; // 0x50
	private SandboxV2DungeonController _controller; // 0x58
	private StateEngine _stateEngine; // 0x60
	private SandboxV2FloatPanelManager _floatPanelManager; // 0x68
	private Coroutine m_coroutine; // 0x70
	private Int32 m_guideStartMsgSeq; // 0x78
	private String m_currWaitingGuideStartMsgId; // 0x80
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteEnsureDungeonQuest; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteEnsureDungeonStable; // 0x28
	private static DelegateBridge __Hotfix0__CoroutineEnsureDungeonStable; // 0x30
	private static DelegateBridge __Hotfix0_TriggerWhenDialogQueueCompleted; // 0x38
	private static DelegateBridge __Hotfix0__ExecuteDungeonFocusNode; // 0x40
	private static DelegateBridge __Hotfix0__CoroutineDungeonFocusNode; // 0x48
	private static DelegateBridge __Hotfix0__CoroutineCameraZoom; // 0x50
	private static DelegateBridge __Hotfix0__ExecuteDungeonBackToDungeonState; // 0x58
	private static DelegateBridge __Hotfix0__CoroutineDungeonBackToDungeonState; // 0x60
	private static DelegateBridge __Hotfix0__ExecuteOpenGainItemPage; // 0x68
	private static DelegateBridge __Hotfix0__ExecuteCloseGainItemPage; // 0x70
	private static DelegateBridge __Hotfix0__CoroutineCloseGainItemPage; // 0x78
	private static DelegateBridge __Hotfix0__ExecuteSettleGameAndLeave; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x253378c VA: 0x7594b4b78c
	protected override Void ForceCommandEnd() { }
	// RVA: 0x25337f0 VA: 0x7594b4b7f0
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x2533bc4 VA: 0x7594b4bbc4
	private Void Start() { }
	// RVA: 0x2533c80 VA: 0x7594b4bc80
	private Void OnDestroy() { }
	// RVA: 0x2533d68 VA: 0x7594b4bd68
	private Boolean _ExecuteEnsureDungeonQuest(Command command) { }
	// RVA: 0x2533e84 VA: 0x7594b4be84
	private Boolean _ExecuteEnsureDungeonStable(Command command) { }
	// RVA: 0x2533f34 VA: 0x7594b4bf34
	private IEnumerator _CoroutineEnsureDungeonStable() { }
	// RVA: 0x2534008 VA: 0x7594b4c008
	public Void TriggerWhenDialogQueueCompleted(String msgId) { }
	// RVA: 0x25340b0 VA: 0x7594b4c0b0
	private Boolean _ExecuteDungeonFocusNode(Command command) { }
	// RVA: 0x253431c VA: 0x7594b4c31c
	private IEnumerator _CoroutineDungeonFocusNode(String focusNodeId) { }
	// RVA: 0x25343ec VA: 0x7594b4c3ec
	private IEnumerator _CoroutineCameraZoom(ZoomType zoomType, String focusNodeId) { }
	// RVA: 0x2534518 VA: 0x7594b4c518
	private Boolean _ExecuteDungeonBackToDungeonState(Command command) { }
	// RVA: 0x25345c8 VA: 0x7594b4c5c8
	private IEnumerator _CoroutineDungeonBackToDungeonState() { }
	// RVA: 0x253469c VA: 0x7594b4c69c
	private Boolean _ExecuteOpenGainItemPage(Command command) { }
	// RVA: 0x25348f0 VA: 0x7594b4c8f0
	private Boolean _ExecuteCloseGainItemPage(Command command) { }
	// RVA: 0x25349a0 VA: 0x7594b4c9a0
	private IEnumerator _CoroutineCloseGainItemPage() { }
	// RVA: 0x2534a74 VA: 0x7594b4ca74
	private Boolean _ExecuteSettleGameAndLeave(Command command) { }
	// RVA: 0x2534c70 VA: 0x7594b4cc70
	public Void .ctor() { }
	// RVA: 0x2534ce0 VA: 0x7594b4cce0
	private Void <_ExecuteSettleGameAndLeave>b__26_0(SandboxV2SettleGameResponse response) { }
}
```