# HomeActivityState

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeMainStateBean _stateBean`

- `Transform _container`

- `ActivityCommonEntry m_activityEntry`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _TryDismissSelf()`

- `IEnumerator _CloseWhenNotLoaded()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`

- `IEnumerator <>xLuaBaseProxy_WaitForLoading()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeActivityState : PopupFloatState, INotResetToDefaultHomeState
{
	private const Int32 PRELOAD_FRAME_CNT; // 0x0
	private HomeMainStateBean _stateBean; // 0x70
	private Transform _container; // 0x78
	private ActivityCommonEntry m_activityEntry; // 0x80
	private Boolean m_isInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__TryDismissSelf; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_WaitForLoading; // 0x30
	private static DelegateBridge __Hotfix0__CloseWhenNotLoaded; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x27e19a4 VA: 0x7594df99a4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27e1a0c VA: 0x7594df9a0c
	private Void _InitIfNot() { }
	// RVA: 0x27e1b44 VA: 0x7594df9b44
	private Void _TryDismissSelf() { }
	// RVA: 0x27e1c1c VA: 0x7594df9c1c
	protected override Void OnEnter() { }
	// RVA: 0x27e1fc0 VA: 0x7594df9fc0
	protected override Void OnResume() { }
	// RVA: 0x27e208c VA: 0x7594dfa08c
	protected override Void OnExit() { }
	// RVA: 0x27e2158 VA: 0x7594dfa158
	protected override IEnumerator WaitForLoading() { }
	// RVA: 0x27e1f14 VA: 0x7594df9f14
	private IEnumerator _CloseWhenNotLoaded() { }
	// RVA: 0x27e2244 VA: 0x7594dfa244
	public Void .ctor() { }
	// RVA: 0x27e22b4 VA: 0x7594dfa2b4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27e22bc VA: 0x7594dfa2bc
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x27e22c4 VA: 0x7594dfa2c4
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x27e22cc VA: 0x7594dfa2cc
	private IEnumerator <>xLuaBaseProxy_WaitForLoading() { }
}
```