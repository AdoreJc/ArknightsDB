# RoguelikeEndingState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Transform _container`

- `RoguelikeEndingControllerBase m_controller`

- `RoguelikeEndingStateBean m_stateBean`

- `RoguelikeMenuAdapter m_menuAdapter`


## Methods

- `Void OnDestroy()`

- `Void _LoadControllerIfNot(String)`

- `Void _TriggerBGMSignal()`

- `Void _ClearBGM()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeEndingState : UIPopupState
{
	private Transform _container; // 0x60
	private RoguelikeEndingControllerBase m_controller; // 0x68
	private RoguelikeEndingStateBean m_stateBean; // 0x70
	private RoguelikeMenuAdapter m_menuAdapter; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge __Hotfix0__LoadControllerIfNot; // 0x28
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x40
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x48
	private static DelegateBridge __Hotfix0__TriggerBGMSignal; // 0x50
	private static DelegateBridge __Hotfix0__ClearBGM; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2a309b8 VA: 0x75950489b8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a30a20 VA: 0x7595048a20
	protected override Void OnEnter() { }
	// RVA: 0x2a31060 VA: 0x7595049060
	protected override Void OnExit() { }
	// RVA: 0x2a311cc VA: 0x75950491cc
	protected override Void OnResume() { }
	// RVA: 0x2a31284 VA: 0x7595049284
	private Void OnDestroy() { }
	// RVA: 0x2a30bbc VA: 0x7595048bbc
	private Void _LoadControllerIfNot(String topicId) { }
	// RVA: 0x2a312ec VA: 0x75950492ec
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2a31464 VA: 0x7595049464
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2a315dc VA: 0x75950495dc
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2a316e8 VA: 0x75950496e8
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2a30ef0 VA: 0x7595048ef0
	private Void _TriggerBGMSignal() { }
	// RVA: 0x2a31120 VA: 0x7595049120
	private Void _ClearBGM() { }
	// RVA: 0x2a317f4 VA: 0x75950497f4
	public Void .ctor() { }
	// RVA: 0x2a31910 VA: 0x7595049910
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2a31918 VA: 0x7595049918
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2a31920 VA: 0x7595049920
	private Void <>xLuaBaseProxy_OnResume() { }
}
```