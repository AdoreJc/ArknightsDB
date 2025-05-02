# Transition

**Namespace:** `Torappu.UI`


## Fields

- `State m_fromState`

- `State m_toState`

- `Int32 m_liveActionCounter`

- `TransitionType m_transType`

- `Boolean m_isFastMode`


## Properties

- `Boolean IsRunning`


## Methods

- `Boolean get_IsRunning()`

- `Boolean StartTransition(State, State, Action`2, Boolean)`

- `Void ResetDynamicActions()`

- `Void AppendDynamicAction(ITransAction)`

- `Void PrependDynamicAction(ITransAction)`

- `Void _DequeueActionAndExec()`

- `Void _OnParallelActionFinish()`

- `Void _OnSequentialActionFinish()`

- `Void _NotifyAnActionEnd()`

- `Void _FinishTransition()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class Transition : IHotfixable
{
	protected List`1 m_staticActionSlot; // 0x10
	protected List`1 m_dynamicActionSlot; // 0x18
	private Queue`1 m_runningActions; // 0x20
	private Action`2 m_transitionEndListener; // 0x28
	private State m_fromState; // 0x30
	private State m_toState; // 0x38
	private Int32 m_liveActionCounter; // 0x40
	private TransitionType m_transType; // 0x44
	private Boolean m_isFastMode; // 0x48
	private static DelegateBridge __Hotfix0_IsSideIn; // 0x0
	private static DelegateBridge __Hotfix0_IsSideOut; // 0x8
	private static DelegateBridge __Hotfix0_get_IsRunning; // 0x10
	private static DelegateBridge __Hotfix0_StartTransition; // 0x18
	private static DelegateBridge __Hotfix0_ResetDynamicActions; // 0x20
	private static DelegateBridge __Hotfix0_AddStaticAction; // 0x28
	private static DelegateBridge __Hotfix0_AddStaticActions; // 0x30
	private static DelegateBridge __Hotfix0_AppendDynamicAction; // 0x38
	private static DelegateBridge __Hotfix0_PrependDynamicAction; // 0x40
	private static DelegateBridge __Hotfix0__DequeueActionAndExec; // 0x48
	private static DelegateBridge __Hotfix0__OnParallelActionFinish; // 0x50
	private static DelegateBridge __Hotfix0__OnSequentialActionFinish; // 0x58
	private static DelegateBridge __Hotfix0__NotifyAnActionEnd; // 0x60
	private static DelegateBridge __Hotfix0__FinishTransition; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Boolean IsRunning { get; }

	// RVA: 0x21680f8 VA: 0x75947800f8
	public static Boolean IsSideIn(TransitionType type) { }
	// RVA: 0x2168160 VA: 0x7594780160
	public static Boolean IsSideOut(TransitionType type) { }
	// RVA: 0x21681c8 VA: 0x75947801c8
	public Boolean get_IsRunning() { }
	// RVA: 0x215cdf4 VA: 0x7594774df4
	public Boolean StartTransition(State fromState, State toState, Action`2 onTransitionEnd, Boolean isFastMode) { }
	// RVA: 0x21686c4 VA: 0x75947806c4
	public Void ResetDynamicActions() { }
	// RVA: 0x21687e0 VA: 0x75947807e0
	public virtual Void AddStaticAction(ITransAction action) { }
	// RVA: 0x21688dc VA: 0x75947808dc
	public virtual Void AddStaticActions(ITransAction[] actions) { }
	// RVA: 0x215ca28 VA: 0x7594774a28
	public Void AppendDynamicAction(ITransAction action) { }
	// RVA: 0x2160928 VA: 0x7594778928
	public Void PrependDynamicAction(ITransAction action) { }
	// RVA: 0x2168378 VA: 0x7594780378
	private Void _DequeueActionAndExec() { }
	// RVA: 0x2168a08 VA: 0x7594780a08
	private Void _OnParallelActionFinish() { }
	// RVA: 0x2168af8 VA: 0x7594780af8
	private Void _OnSequentialActionFinish() { }
	// RVA: 0x2168a70 VA: 0x7594780a70
	private Void _NotifyAnActionEnd() { }
	// RVA: 0x2168238 VA: 0x7594780238
	private Void _FinishTransition() { }
	// RVA: 0x2168b68 VA: 0x7594780b68
	public Void .ctor() { }
}
```