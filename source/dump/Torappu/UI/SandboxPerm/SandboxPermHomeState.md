# SandboxPermHomeState

**Namespace:** `Torappu.UI.SandboxPerm`


## Fields

- `Transform _homeViewContainer`

- `RectTransform _dialogContainer`

- `Boolean m_isInited`

- `SandboxPermHomeControllerBase m_homeController`

- `UICompDialogMgr m_dialogMgr`


## Properties

- `UICompDialogMgr dialogMgr`


## Methods

- `UICompDialogMgr get_dialogMgr()`

- `Void OnMessage(Int32, ValueBundle)`

- `Coroutine PageOnlyStartShowEffects(Boolean, Boolean)`

- `Void PageOnlyDisposeEffects()`

- `Boolean CheckIfUseFastEnter()`

- `DisplayTweenConfig GetDisplayTweenConfig(Boolean)`

- `Boolean OnBackClick()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void _BindEffectsAndCanvasInController()`

- `Void _EventOpenMedalGroup()`

- `Void _EventOnOpenAnnounce()`

- `Void _JumpToMedalGroupState(IStateBean)`

- `Void _ToDiffModeState(IStateBean)`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm
public class SandboxPermHomeState : State, IValueMsgReceiver, ICompDialogCallBack
{
	public const Int32 MSG_OPEN_MEDAL_GROUP; // 0x0
	public const Int32 MSG_OPEN_ANNOUNCE; // 0x0
	private Transform _homeViewContainer; // 0x50
	private RectTransform _dialogContainer; // 0x58
	private Boolean m_isInited; // 0x60
	private SandboxPermHomeControllerBase m_homeController; // 0x68
	private UICompDialogMgr m_dialogMgr; // 0x70
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0_PageOnlyStartShowEffects; // 0x28
	private static DelegateBridge __Hotfix0_PageOnlyDisposeEffects; // 0x30
	private static DelegateBridge __Hotfix0_CheckIfUseFastEnter; // 0x38
	private static DelegateBridge __Hotfix0_GetDisplayTweenConfig; // 0x40
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x48
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__BindEffectsAndCanvasInController; // 0x60
	private static DelegateBridge __Hotfix0__EventOpenMedalGroup; // 0x68
	private static DelegateBridge __Hotfix0__EventOnOpenAnnounce; // 0x70
	private static DelegateBridge __Hotfix0__JumpToMedalGroupState; // 0x78
	private static DelegateBridge __Hotfix0__ToDiffModeState; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public UICompDialogMgr dialogMgr { get; }

	// RVA: 0x247d8a4 VA: 0x7594a958a4
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x247d90c VA: 0x7594a9590c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x247d970 VA: 0x7594a95970
	protected override Void OnResume() { }
	// RVA: 0x247dc48 VA: 0x7594a95c48
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x247df7c VA: 0x7594a95f7c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x247d658 VA: 0x7594a95658
	public Coroutine PageOnlyStartShowEffects(Boolean fastMode, Boolean backFromBattle) { }
	// RVA: 0x247d148 VA: 0x7594a95148
	public Void PageOnlyDisposeEffects() { }
	// RVA: 0x247d58c VA: 0x7594a9558c
	public Boolean CheckIfUseFastEnter() { }
	// RVA: 0x247d74c VA: 0x7594a9574c
	public DisplayTweenConfig GetDisplayTweenConfig(Boolean fastMode) { }
	// RVA: 0x247cb4c VA: 0x7594a94b4c
	public Boolean OnBackClick() { }
	// RVA: 0x247e170 VA: 0x7594a96170
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x247da58 VA: 0x7594a95a58
	private Void _InitIfNot() { }
	// RVA: 0x247e270 VA: 0x7594a96270
	private Void _BindEffectsAndCanvasInController() { }
	// RVA: 0x247dd0c VA: 0x7594a95d0c
	private Void _EventOpenMedalGroup() { }
	// RVA: 0x247de74 VA: 0x7594a95e74
	private Void _EventOnOpenAnnounce() { }
	// RVA: 0x247e4d8 VA: 0x7594a964d8
	private Void _JumpToMedalGroupState(IStateBean stateBean) { }
	// RVA: 0x247e60c VA: 0x7594a9660c
	public Void _ToDiffModeState(IStateBean stateBean) { }
	// RVA: 0x247ec50 VA: 0x7594a96c50
	public Void .ctor() { }
	// RVA: 0x247ecc0 VA: 0x7594a96cc0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x247ecc8 VA: 0x7594a96cc8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```