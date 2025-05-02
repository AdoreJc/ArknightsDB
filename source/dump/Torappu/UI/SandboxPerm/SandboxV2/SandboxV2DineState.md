# SandboxV2DineState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DineView _dineView`

- `RectTransform _backRect`

- `Boolean m_hasInited`

- `SandboxV2DineStateBean m_stateBean`

- `Int32 m_cookDialogInst`

- `Coroutine m_tutorialCoroutine`


## Methods

- `Void _InitIfNot()`

- `Void _ToCookPanel()`

- `Void _SelectItem(Int32)`

- `Void _ConfirmDine()`

- `Void _OnBack()`

- `Void _SendDineRequest()`

- `Void _OnDineConfirmed(SandboxV2DineResponse)`

- `Void _DismissIfCan()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _TryTriggerTutorial()`

- `Void _TryRaiseTutorialSignal()`

- `IEnumerator _CoroutineTriggerTutorial()`

- `Void _StopTutorialCoroutine()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DineState : PopupFadeState, ICompDialogCallBack
{
	private SandboxV2DineView _dineView; // 0x70
	private RectTransform _backRect; // 0x78
	private Boolean m_hasInited; // 0x80
	private SandboxV2DineStateBean m_stateBean; // 0x88
	private Int32 m_cookDialogInst; // 0x90
	private Coroutine m_tutorialCoroutine; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnPause; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__ToCookPanel; // 0x28
	private static DelegateBridge __Hotfix0__SelectItem; // 0x30
	private static DelegateBridge __Hotfix0__ConfirmDine; // 0x38
	private static DelegateBridge __Hotfix0__OnBack; // 0x40
	private static DelegateBridge __Hotfix0__SendDineRequest; // 0x48
	private static DelegateBridge __Hotfix0__OnDineConfirmed; // 0x50
	private static DelegateBridge __Hotfix0__DismissIfCan; // 0x58
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x60
	private static DelegateBridge __Hotfix0__TryTriggerTutorial; // 0x68
	private static DelegateBridge __Hotfix0__TryRaiseTutorialSignal; // 0x70
	private static DelegateBridge __Hotfix0__CoroutineTriggerTutorial; // 0x78
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x25084b4 VA: 0x7594b204b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x250851c VA: 0x7594b2051c
	protected override Void OnEnter() { }
	// RVA: 0x2508998 VA: 0x7594b20998
	protected override Void OnResume() { }
	// RVA: 0x2508b40 VA: 0x7594b20b40
	protected override Void OnPause() { }
	// RVA: 0x250860c VA: 0x7594b2060c
	private Void _InitIfNot() { }
	// RVA: 0x2508e6c VA: 0x7594b20e6c
	private Void _ToCookPanel() { }
	// RVA: 0x2509168 VA: 0x7594b21168
	private Void _SelectItem(Int32 index) { }
	// RVA: 0x2509700 VA: 0x7594b21700
	private Void _ConfirmDine() { }
	// RVA: 0x2509c20 VA: 0x7594b21c20
	private Void _OnBack() { }
	// RVA: 0x25099dc VA: 0x7594b219dc
	private Void _SendDineRequest() { }
	// RVA: 0x2509d9c VA: 0x7594b21d9c
	private Void _OnDineConfirmed(SandboxV2DineResponse response) { }
	// RVA: 0x2509c88 VA: 0x7594b21c88
	private Void _DismissIfCan() { }
	// RVA: 0x2509f64 VA: 0x7594b21f64
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2508870 VA: 0x7594b20870
	private Void _TryTriggerTutorial() { }
	// RVA: 0x2508a98 VA: 0x7594b20a98
	private Void _TryRaiseTutorialSignal() { }
	// RVA: 0x250a0c0 VA: 0x7594b220c0
	private IEnumerator _CoroutineTriggerTutorial() { }
	// RVA: 0x2508bb4 VA: 0x7594b20bb4
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x250a184 VA: 0x7594b22184
	public Void .ctor() { }
	// RVA: 0x250a2dc VA: 0x7594b222dc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x250a2e4 VA: 0x7594b222e4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x250a2ec VA: 0x7594b222ec
	private Void <>xLuaBaseProxy_OnPause() { }
}
```