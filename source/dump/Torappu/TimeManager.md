# TimeManager

**Namespace:** `Torappu`


## Fields

- `Double m_unscaledTime`

- `Int32 m_timeScaleKeyCounter`

- `Single m_timeScale`

- `Single m_maxTimeDelta`

- `Int64 <frameCount>k__BackingField`

- `Boolean <isInited>k__BackingField`


## Properties

- `Int64 frameCount`

- `Boolean isInited`

- `Single timeScale`

- `Double unscaledTime`


## Methods

- `Root _PickTickRoot(TickGroupType)`

- `Int64 get_frameCount()`

- `Void set_frameCount(Int64)`

- `Boolean get_isInited()`

- `Void set_isInited(Boolean)`

- `Single get_timeScale()`

- `Double get_unscaledTime()`

- `Void Init(Options)`

- `Void UnInit()`

- `Void Tick(Single)`

- `TickFunction NewRoughLogicTick(Action`1, Object)`

- `TickFunction NewRoughLogicTickWithOwner(ITickOwner, Action`1)`

- `TickFunction NewFrameTick(Action`1, Object)`

- `TickFunction NewFrameTickWithOwner(ITickOwner, Action`1)`

- `TickFunction _NewTickFunc(TickGroupType, Action`1, Object)`

- `TickFunction _NewTickFuncWithOwner(TickGroupType, ITickOwner, Action`1)`

- `TickFunction StartInstruciton(TickYieldInstruction)`

- `Int32 AddDelayTimer(Single, Action, Boolean)`

- `Int32 AddDelayTimer(Single, Action, Action, Boolean)`

- `Int32 AddLoopTimer(Single, Action, Int32, Action, Boolean)`

- `Void ClearTimer(Int32)`

- `Single GetTimerLeftTime(Int32)`

- `TimerStatus GetTimerStatus(Int32)`

- `TimerGroup _PickTimerGroup(Boolean)`

- `Int32 StartChangeTimeScale(Single)`

- `Boolean ChangeTimeScaleByExistingKey(Int32, Single)`

- `Void StopChangeTimeScale(Int32)`

- `Void ResetTimeScale()`

- `Single _GetLowestTimeScale()`

- `Void _SetTimeScale(Single)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class TimeManager : Singleton`1
{
	public const Single DEFAULT_TIME_SCALE; // 0x0
	public const Int32 EMPTY_TIMER; // 0x0
	private const String NAME_ROUGH_LOGIC; // 0x0
	private const String NAME_FRAME; // 0x0
	private Double m_unscaledTime; // 0x10
	private readonly Dictionary`2 m_timeScaleDic; // 0x18
	private Int32 m_timeScaleKeyCounter; // 0x20
	private Single m_timeScale; // 0x24
	private Single m_maxTimeDelta; // 0x28
	private ListDict`2 m_tickRoots; // 0x30
	private readonly TimerGroup m_unscaledTimers; // 0x38
	private readonly TimerGroup m_scaledTimers; // 0x40
	private Int64 <frameCount>k__BackingField; // 0x48
	private Boolean <isInited>k__BackingField; // 0x50
	private static __XLua_Gen_Delegate20 __Hotfix0__PickTickRoot; // 0x0
	private static __XLua_Gen_Delegate21 __Hotfix0_get_frameCount; // 0x8
	private static __XLua_Gen_Delegate22 __Hotfix0_set_frameCount; // 0x10
	private static __XLua_Gen_Delegate8 __Hotfix0_get_isInited; // 0x18
	private static __XLua_Gen_Delegate9 __Hotfix0_set_isInited; // 0x20
	private static __XLua_Gen_Delegate6 __Hotfix0_get_timeScale; // 0x28
	private static __XLua_Gen_Delegate23 __Hotfix0_get_unscaledTime; // 0x30
	private static __XLua_Gen_Delegate24 __Hotfix0_Init; // 0x38
	private static __XLua_Gen_Delegate1 __Hotfix0_UnInit; // 0x40
	private static __XLua_Gen_Delegate7 __Hotfix0_Tick; // 0x48
	private static __XLua_Gen_Delegate25 __Hotfix0_NewRoughLogicTick; // 0x50
	private static __XLua_Gen_Delegate25 __Hotfix0_NewRoughLogicTickWithOwner; // 0x58
	private static __XLua_Gen_Delegate25 __Hotfix0_NewFrameTick; // 0x60
	private static __XLua_Gen_Delegate25 __Hotfix0_NewFrameTickWithOwner; // 0x68
	private static __XLua_Gen_Delegate26 __Hotfix0__NewTickFunc; // 0x70
	private static __XLua_Gen_Delegate26 __Hotfix0__NewTickFuncWithOwner; // 0x78
	private static __XLua_Gen_Delegate27 __Hotfix0__TestOnlyDebugNameByContext; // 0x80
	private static __XLua_Gen_Delegate27 __Hotfix0__TestOnlyDebugNameByOwner; // 0x88
	private static __XLua_Gen_Delegate28 __Hotfix0_StartInstruciton; // 0x90
	private static __XLua_Gen_Delegate29 __Hotfix0_AddDelayTimer; // 0x98
	private static __XLua_Gen_Delegate30 __Hotfix1_AddDelayTimer; // 0xa0
	private static __XLua_Gen_Delegate31 __Hotfix0_AddLoopTimer; // 0xa8
	private static __XLua_Gen_Delegate11 __Hotfix0_ClearTimer; // 0xb0
	private static __XLua_Gen_Delegate32 __Hotfix0_GetTimerLeftTime; // 0xb8
	private static __XLua_Gen_Delegate33 __Hotfix0_GetTimerStatus; // 0xc0
	private static __XLua_Gen_Delegate34 __Hotfix0__PickTimerGroup; // 0xc8
	private static __XLua_Gen_Delegate14 __Hotfix0_StartChangeTimeScale; // 0xd0
	private static __XLua_Gen_Delegate35 __Hotfix0_ChangeTimeScaleByExistingKey; // 0xd8
	private static __XLua_Gen_Delegate11 __Hotfix0_StopChangeTimeScale; // 0xe0
	private static __XLua_Gen_Delegate1 __Hotfix0_ResetTimeScale; // 0xe8
	private static __XLua_Gen_Delegate6 __Hotfix0__GetLowestTimeScale; // 0xf0
	private static __XLua_Gen_Delegate7 __Hotfix0__SetTimeScale; // 0xf8
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x100

	public Int64 frameCount { get; set; }
	public Boolean isInited { get; set; }
	public Single timeScale { get; }
	public Double unscaledTime { get; }

	// RVA: 0x6750a5c VA: 0x7598d68a5c
	private Root _PickTickRoot(TickGroupType type) { }
	// RVA: 0x6750b40 VA: 0x7598d68b40
	public Int64 get_frameCount() { }
	// RVA: 0x6750bb0 VA: 0x7598d68bb0
	private Void set_frameCount(Int64 value) { }
	// RVA: 0x6750c34 VA: 0x7598d68c34
	public Boolean get_isInited() { }
	// RVA: 0x6750ca4 VA: 0x7598d68ca4
	private Void set_isInited(Boolean value) { }
	// RVA: 0x674fd80 VA: 0x7598d67d80
	public Single get_timeScale() { }
	// RVA: 0x6750d2c VA: 0x7598d68d2c
	public Double get_unscaledTime() { }
	// RVA: 0x6750d9c VA: 0x7598d68d9c
	public Void Init(Options options) { }
	// RVA: 0x6750e88 VA: 0x7598d68e88
	public Void UnInit() { }
	// RVA: 0x675107c VA: 0x7598d6907c
	public Void Tick(Single unscaledDeltaTime) { }
	// RVA: 0x6750600 VA: 0x7598d68600
	public TickFunction NewRoughLogicTick(Action`1 tickFunc, Object context) { }
	// RVA: 0x675136c VA: 0x7598d6936c
	public TickFunction NewRoughLogicTickWithOwner(ITickOwner owner, Action`1 tickFunc) { }
	// RVA: 0x6750698 VA: 0x7598d68698
	public TickFunction NewFrameTick(Action`1 tickFunc, Object context) { }
	// RVA: 0x67514e0 VA: 0x7598d694e0
	public TickFunction NewFrameTickWithOwner(ITickOwner owner, Action`1 tickFunc) { }
	// RVA: 0x6751290 VA: 0x7598d69290
	private TickFunction _NewTickFunc(TickGroupType type, Action`1 tickFunc, Object context) { }
	// RVA: 0x6751404 VA: 0x7598d69404
	private TickFunction _NewTickFuncWithOwner(TickGroupType type, ITickOwner owner, Action`1 tickFunc) { }
	// RVA: 0x6751578 VA: 0x7598d69578
	private static Void _TestOnlyDebugNameByContext(Object context, String tickType, ref String debugName) { }
	// RVA: 0x67517cc VA: 0x7598d697cc
	private static Void _TestOnlyDebugNameByOwner(ITickOwner owner, String tickType, ref String debugName) { }
	// RVA: 0x67518d4 VA: 0x7598d698d4
	public TickFunction StartInstruciton(TickYieldInstruction inst) { }
	// RVA: 0x67519d8 VA: 0x7598d699d8
	public Int32 AddDelayTimer(Single delay, Action callback, Boolean unscaled) { }
	// RVA: 0x6751b2c VA: 0x7598d69b2c
	public Int32 AddDelayTimer(Single delay, Action callback, Action callbackOnRemoved, Boolean unscaled) { }
	// RVA: 0x6751c04 VA: 0x7598d69c04
	public Int32 AddLoopTimer(Single interval, Action callback, Int32 loopCnt, Action callbackOnRemoved, Boolean unscaled) { }
	// RVA: 0x6751ce4 VA: 0x7598d69ce4
	public Void ClearTimer(Int32 timerId) { }
	// RVA: 0x6751d8c VA: 0x7598d69d8c
	public Single GetTimerLeftTime(Int32 timerId) { }
	// RVA: 0x6751e74 VA: 0x7598d69e74
	public TimerStatus GetTimerStatus(Int32 timerId) { }
	// RVA: 0x6751a9c VA: 0x7598d69a9c
	private TimerGroup _PickTimerGroup(Boolean unscaled) { }
	// RVA: 0x6751f2c VA: 0x7598d69f2c
	public Int32 StartChangeTimeScale(Single inTimeScale) { }
	// RVA: 0x6752398 VA: 0x7598d6a398
	public Boolean ChangeTimeScaleByExistingKey(Int32 key, Single inTimeScale) { }
	// RVA: 0x6752554 VA: 0x7598d6a554
	public Void StopChangeTimeScale(Int32 key) { }
	// RVA: 0x6752620 VA: 0x7598d6a620
	public Void ResetTimeScale() { }
	// RVA: 0x6751ffc VA: 0x7598d69ffc
	private Single _GetLowestTimeScale() { }
	// RVA: 0x67521e0 VA: 0x7598d6a1e0
	private Void _SetTimeScale(Single inTimeScale) { }
	// RVA: 0x67526bc VA: 0x7598d6a6bc
	private Void .ctor() { }
}
```