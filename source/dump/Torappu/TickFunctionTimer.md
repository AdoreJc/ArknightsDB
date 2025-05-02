# TickFunctionTimer

**Namespace:** `Torappu`


## Fields

- `TickGroupType m_tickGroupType`

- `Single m_targetTime`

- `Single m_timeCount`

- `TickFunction m_tickFunction`

- `Action m_callback`

- `Object m_context`

- `Boolean m_hasSetOwner`

- `Transform m_owner`

- `Int32 m_targetLoopLimitCount`

- `Int32 m_curLoopCount`


## Properties

- `Status timerStatus`


## Methods

- `Status get_timerStatus()`

- `Boolean _IsTimerAvail()`

- `Void _Tick(Single)`

- `Void _UpdateTimerLoopCount()`

- `TickFunction _CreateTickFunction()`

- `Boolean StartTimer(Boolean)`

- `Boolean ResumeTimer()`

- `Boolean StopTimer()`

- `Void ReleaseTimer()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class TickFunctionTimer : IHotfixable
{
	private TickGroupType m_tickGroupType; // 0x10
	private Single m_targetTime; // 0x14
	private Single m_timeCount; // 0x18
	private TickFunction m_tickFunction; // 0x20
	private Action m_callback; // 0x28
	private Object m_context; // 0x30
	private Boolean m_hasSetOwner; // 0x38
	private Transform m_owner; // 0x40
	private Int32 m_targetLoopLimitCount; // 0x48
	private Int32 m_curLoopCount; // 0x4c
	private static __XLua_Gen_Delegate15 __Hotfix0_get_timerStatus; // 0x0
	private static __XLua_Gen_Delegate8 __Hotfix0__IsTimerAvail; // 0x8
	private static __XLua_Gen_Delegate7 __Hotfix0__Tick; // 0x10
	private static __XLua_Gen_Delegate1 __Hotfix0__UpdateTimerLoopCount; // 0x18
	private static __XLua_Gen_Delegate16 __Hotfix0_Create; // 0x20
	private static __XLua_Gen_Delegate17 _c__Hotfix0_ctor; // 0x28
	private static __XLua_Gen_Delegate18 __Hotfix0__CreateTickFunction; // 0x30
	private static __XLua_Gen_Delegate19 __Hotfix0_StartTimer; // 0x38
	private static __XLua_Gen_Delegate8 __Hotfix0_ResumeTimer; // 0x40
	private static __XLua_Gen_Delegate8 __Hotfix0_StopTimer; // 0x48
	private static __XLua_Gen_Delegate1 __Hotfix0_ReleaseTimer; // 0x50

	public Status timerStatus { get; }

	// RVA: 0x674fe3c VA: 0x7598d67e3c
	public Status get_timerStatus() { }
	// RVA: 0x674fedc VA: 0x7598d67edc
	private Boolean _IsTimerAvail() { }
	// RVA: 0x674ff90 VA: 0x7598d67f90
	private Void _Tick(Single deltaTime) { }
	// RVA: 0x6750088 VA: 0x7598d68088
	private Void _UpdateTimerLoopCount() { }
	// RVA: 0x6750230 VA: 0x7598d68230
	public static TickFunctionTimer Create(Input input) { }
	// RVA: 0x67502f8 VA: 0x7598d682f8
	private Void .ctor(Input timerInput) { }
	// RVA: 0x6750494 VA: 0x7598d68494
	private TickFunction _CreateTickFunction() { }
	// RVA: 0x675012c VA: 0x7598d6812c
	public Boolean StartTimer(Boolean isRestart) { }
	// RVA: 0x6750730 VA: 0x7598d68730
	public Boolean ResumeTimer() { }
	// RVA: 0x67507cc VA: 0x7598d687cc
	public Boolean StopTimer() { }
	// RVA: 0x6750868 VA: 0x7598d68868
	public Void ReleaseTimer() { }
}
```