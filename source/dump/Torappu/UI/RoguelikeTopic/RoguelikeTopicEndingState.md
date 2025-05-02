# RoguelikeTopicEndingState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Transform _container`

- `RoguelikeTopicEndingViewModelBase m_viewModel`

- `RoguelikeTopicEndingControllerBase m_controller`


## Methods

- `Void _LoadControllerIfNot(String)`

- `Void _Init()`

- `Void EventOnComplete()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicEndingState : PopupFloatState
{
	private Transform _container; // 0x70
	private RoguelikeTopicEndingViewModelBase m_viewModel; // 0x78
	private RoguelikeTopicEndingControllerBase m_controller; // 0x80
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0__LoadControllerIfNot; // 0x20
	private static DelegateBridge __Hotfix0__Init; // 0x28
	private static DelegateBridge __Hotfix0_EventOnComplete; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x264ef48 VA: 0x7594c66f48
	protected override Void OnEnter() { }
	// RVA: 0x264f1b0 VA: 0x7594c671b0
	protected override Void OnResume() { }
	// RVA: 0x264f274 VA: 0x7594c67274
	protected override Void OnExit() { }
	// RVA: 0x264f338 VA: 0x7594c67338
	public override IStateBean GetCacheBean() { }
	// RVA: 0x264f39c VA: 0x7594c6739c
	private Void _LoadControllerIfNot(String topicId) { }
	// RVA: 0x264f008 VA: 0x7594c67008
	private Void _Init() { }
	// RVA: 0x264f518 VA: 0x7594c67518
	public Void EventOnComplete() { }
	// RVA: 0x264f684 VA: 0x7594c67684
	public Void .ctor() { }
	// RVA: 0x264f6f4 VA: 0x7594c676f4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x264f6fc VA: 0x7594c676fc
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x264f704 VA: 0x7594c67704
	private Void <>xLuaBaseProxy_OnExit() { }
}
```