# SandboxV2AdminMainState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Transform _tabPanelContainer`

- `SandboxV2AdminMainTabPanelDefinedList _definedTabPanels`

- `Boolean _singleMode`

- `SandboxV2AdminMainModelProperty m_prop`

- `Boolean m_inHideProcess`

- `Int32 m_cookDialogInst`

- `Int32 m_recipeMasteryDialogInst`

- `Int32 m_workbenchMakeDialogInst`

- `Coroutine m_tutorialRaisingCoroutine`


## Methods

- `Void _InitIfNot()`

- `Boolean CheckCurrentTabPanel(SandboxV2AdminMainTabPanel)`

- `T GetTabPanelInitParam(Boolean)`

- `Void RefreshPanelActiveState()`

- `Void OpenCookDialog(Options)`

- `Void OpenRecipeMasteryDialog(Options)`

- `Void OpenWorkbenchDialog(Options)`

- `Void HandleBack()`

- `Void SwitchPanel(SandboxV2AdminMainPanelType)`

- `Void DoPanelHideProcess(Action)`

- `SandboxV2AdminMainTabPanel _FindPanel(SandboxV2AdminMainPanelType)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _HandleCookCallback(ValueBundle)`

- `Void _HandleRecipeMasteryCallback(ValueBundle)`

- `Void _HandleWorkbenchCallback(ValueBundle)`

- `Void _ResumeFromDialog()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnOpenRacingInfo()`

- `Void _TutorialOnly_CheckSignalToRaise()`

- `IEnumerator _TutorialOnly_RaiseSignalWhenFinishTransiting(Action)`

- `Void _StopCoroutineIfNeed()`

- `Void OnDestroy()`

- `Void <HandleBack>b__22_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainState : PopupFadeState, IValueMsgReceiver, ICompDialogCallBack
{
	public const Int32 MSG_OPEN_RACING_INFO; // 0x0
	private Transform _tabPanelContainer; // 0x70
	private SandboxV2AdminMainTabPanelDefinedList _definedTabPanels; // 0x78
	private SandboxV2AdminMainViewDef[] _viewDefList; // 0x80
	private Boolean _singleMode; // 0x88
	private SandboxV2AdminMainModelProperty m_prop; // 0x90
	private List`1 m_tabPanels; // 0x98
	private Boolean m_inHideProcess; // 0xa0
	private Int32 m_cookDialogInst; // 0xa4
	private Int32 m_recipeMasteryDialogInst; // 0xa8
	private Int32 m_workbenchMakeDialogInst; // 0xac
	private Coroutine m_tutorialRaisingCoroutine; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_CheckCurrentTabPanel; // 0x28
	private static DelegateBridge __Hotfix0_GetTabPanelInitParam; // 0x30
	private static DelegateBridge __Hotfix0_RefreshPanelActiveState; // 0x38
	private static DelegateBridge __Hotfix0_OpenCookDialog; // 0x40
	private static DelegateBridge __Hotfix0_OpenRecipeMasteryDialog; // 0x48
	private static DelegateBridge __Hotfix0_OpenWorkbenchDialog; // 0x50
	private static DelegateBridge __Hotfix0_HandleBack; // 0x58
	private static DelegateBridge __Hotfix0_SwitchPanel; // 0x60
	private static DelegateBridge __Hotfix0_DoPanelHideProcess; // 0x68
	private static DelegateBridge __Hotfix0__FindPanel; // 0x70
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x78
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x80
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x88
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x90
	private static DelegateBridge __Hotfix0__HandleCookCallback; // 0x98
	private static DelegateBridge __Hotfix0__HandleRecipeMasteryCallback; // 0xa0
	private static DelegateBridge __Hotfix0__HandleWorkbenchCallback; // 0xa8
	private static DelegateBridge __Hotfix0__ResumeFromDialog; // 0xb0
	private static DelegateBridge __Hotfix0_OnMessage; // 0xb8
	private static DelegateBridge __Hotfix0__OnOpenRacingInfo; // 0xc0
	private static DelegateBridge __Hotfix0__TutorialOnly_CheckSignalToRaise; // 0xc8
	private static DelegateBridge __Hotfix0__TutorialOnly_RaiseSignalWhenFinishTransiting; // 0xd0
	private static DelegateBridge __Hotfix0__StopCoroutineIfNeed; // 0xd8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8


	// RVA: 0x24da3b4 VA: 0x7594af23b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x24da418 VA: 0x7594af2418
	protected override Void OnEnter() { }
	// RVA: 0x24da9ac VA: 0x7594af29ac
	protected override Void OnExit() { }
	// RVA: 0x24daa90 VA: 0x7594af2a90
	protected override Void OnResume() { }
	// RVA: 0x24da480 VA: 0x7594af2480
	private Void _InitIfNot() { }
	// RVA: 0x24dad4c VA: 0x7594af2d4c
	public Boolean CheckCurrentTabPanel(SandboxV2AdminMainTabPanel tabPanel) { }
	// RVA: 0x VA: 0x0
	public T GetTabPanelInitParam(Boolean notNull) { }
	// RVA: 0x24dae14 VA: 0x7594af2e14
	public Void RefreshPanelActiveState() { }
	// RVA: 0x24daec8 VA: 0x7594af2ec8
	public Void OpenCookDialog(Options options) { }
	// RVA: 0x24db148 VA: 0x7594af3148
	public Void OpenRecipeMasteryDialog(Options options) { }
	// RVA: 0x24db3c8 VA: 0x7594af33c8
	public Void OpenWorkbenchDialog(Options options) { }
	// RVA: 0x24d9acc VA: 0x7594af1acc
	public Void HandleBack() { }
	// RVA: 0x24d9374 VA: 0x7594af1374
	public Void SwitchPanel(SandboxV2AdminMainPanelType panelType) { }
	// RVA: 0x24db648 VA: 0x7594af3648
	public Void DoPanelHideProcess(Action done) { }
	// RVA: 0x24db838 VA: 0x7594af3838
	private SandboxV2AdminMainTabPanel _FindPanel(SandboxV2AdminMainPanelType pt) { }
	// RVA: 0x24db988 VA: 0x7594af3988
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x24dbe70 VA: 0x7594af3e70
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x24dbee8 VA: 0x7594af3ee8
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x24dc3d4 VA: 0x7594af43d4
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x24dc4bc VA: 0x7594af44bc
	private Void _HandleCookCallback(ValueBundle output) { }
	// RVA: 0x24dc5ac VA: 0x7594af45ac
	private Void _HandleRecipeMasteryCallback(ValueBundle output) { }
	// RVA: 0x24dc810 VA: 0x7594af4810
	private Void _HandleWorkbenchCallback(ValueBundle output) { }
	// RVA: 0x24dc900 VA: 0x7594af4900
	private Void _ResumeFromDialog() { }
	// RVA: 0x24dc9b4 VA: 0x7594af49b4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x24dca58 VA: 0x7594af4a58
	private Void _OnOpenRacingInfo() { }
	// RVA: 0x24dab80 VA: 0x7594af2b80
	private Void _TutorialOnly_CheckSignalToRaise() { }
	// RVA: 0x24dcd20 VA: 0x7594af4d20
	private IEnumerator _TutorialOnly_RaiseSignalWhenFinishTransiting(Action signalAction) { }
	// RVA: 0x24dcc3c VA: 0x7594af4c3c
	private Void _StopCoroutineIfNeed() { }
	// RVA: 0x24dce18 VA: 0x7594af4e18
	private Void OnDestroy() { }
	// RVA: 0x24dce80 VA: 0x7594af4e80
	public Void .ctor() { }
	// RVA: 0x24dcef0 VA: 0x7594af4ef0
	private Void <HandleBack>b__22_0() { }
	// RVA: 0x24dcf10 VA: 0x7594af4f10
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x24dcf18 VA: 0x7594af4f18
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x24dcf20 VA: 0x7594af4f20
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x24dcf28 VA: 0x7594af4f28
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x24dcf30 VA: 0x7594af4f30
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x24dcf38 VA: 0x7594af4f38
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```