# TickFunction

**Namespace:** `Torappu`


## Fields

- `Single m_timeScale`

- `Single m_baseSelfTimeScale`

- `Boolean m_ignoreGlobalTimeScale`

- `Double m_lastTickTs`

- `Boolean tickWhenTimeScaleZero`

- `Boolean <isReleased>k__BackingField`

- `Boolean <isTicking>k__BackingField`

- `Int32 <frame>k__BackingField`


## Properties

- `Single timeScale`

- `Single baseSelfTimeScale`

- `Single selfTimeScale`

- `Boolean ignoreGlobalTimeScale`

- `Boolean isReleased`

- `Boolean isTicking`

- `Int32 frame`


## Methods

- `Single get_timeScale()`

- `Void SetTimeScale(Single)`

- `Single get_baseSelfTimeScale()`

- `Void set_baseSelfTimeScale(Single)`

- `Single get_selfTimeScale()`

- `Boolean get_ignoreGlobalTimeScale()`

- `Void set_ignoreGlobalTimeScale(Boolean)`

- `Boolean get_isReleased()`

- `Void set_isReleased(Boolean)`

- `Boolean get_isTicking()`

- `Void set_isTicking(Boolean)`

- `Int32 get_frame()`

- `Void set_frame(Int32)`

- `Void ClearFrameCount()`

- `Void Tick(Single, Double)`

- `Void OnGlobalTimeScaleChange(Single)`

- `Void Start()`

- `Void Stop()`

- `Void Resume()`

- `Void Release()`

- `Int32 AddSelfTimeScaleModifier(Single)`

- `Void RemoveSelfTimeScaleModifier(Int32)`

- `Void _OnTick(Single)`

- `Void _OnTimeScaleChange(Single)`

- `Void _ReCalculateTimeScale()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class TickFunction : IHotfixable
{
	private static Int32 s_selfModifierInstanceId; // 0x0
	private readonly ITickOwner m_owner; // 0x10
	private readonly Action`1 m_func; // 0x18
	private Single m_timeScale; // 0x20
	private Single m_baseSelfTimeScale; // 0x24
	private Boolean m_ignoreGlobalTimeScale; // 0x28
	private Dictionary`2 m_selfTimeScaleModifier; // 0x30
	private Double m_lastTickTs; // 0x38
	public Boolean tickWhenTimeScaleZero; // 0x40
	private Boolean <isReleased>k__BackingField; // 0x41
	private Boolean <isTicking>k__BackingField; // 0x42
	private Int32 <frame>k__BackingField; // 0x44
	private static __XLua_Gen_Delegate6 __Hotfix0_get_timeScale; // 0x8
	private static __XLua_Gen_Delegate7 __Hotfix0_SetTimeScale; // 0x10
	private static __XLua_Gen_Delegate6 __Hotfix0_get_baseSelfTimeScale; // 0x18
	private static __XLua_Gen_Delegate7 __Hotfix0_set_baseSelfTimeScale; // 0x20
	private static __XLua_Gen_Delegate6 __Hotfix0_get_selfTimeScale; // 0x28
	private static __XLua_Gen_Delegate8 __Hotfix0_get_ignoreGlobalTimeScale; // 0x30
	private static __XLua_Gen_Delegate9 __Hotfix0_set_ignoreGlobalTimeScale; // 0x38
	private static __XLua_Gen_Delegate8 __Hotfix0_get_isReleased; // 0x40
	private static __XLua_Gen_Delegate9 __Hotfix0_set_isReleased; // 0x48
	private static __XLua_Gen_Delegate8 __Hotfix0_get_isTicking; // 0x50
	private static __XLua_Gen_Delegate9 __Hotfix0_set_isTicking; // 0x58
	private static __XLua_Gen_Delegate10 __Hotfix0_get_frame; // 0x60
	private static __XLua_Gen_Delegate11 __Hotfix0_set_frame; // 0x68
	private static __XLua_Gen_Delegate12 _c__Hotfix0_ctor; // 0x70
	private static __XLua_Gen_Delegate1 __Hotfix0_ClearFrameCount; // 0x78
	private static __XLua_Gen_Delegate13 __Hotfix0_Tick; // 0x80
	private static __XLua_Gen_Delegate7 __Hotfix0_OnGlobalTimeScaleChange; // 0x88
	private static __XLua_Gen_Delegate1 __Hotfix0_Start; // 0x90
	private static __XLua_Gen_Delegate1 __Hotfix0_Stop; // 0x98
	private static __XLua_Gen_Delegate1 __Hotfix0_Resume; // 0xa0
	private static __XLua_Gen_Delegate1 __Hotfix0_Release; // 0xa8
	private static __XLua_Gen_Delegate14 __Hotfix0_AddSelfTimeScaleModifier; // 0xb0
	private static __XLua_Gen_Delegate11 __Hotfix0_RemoveSelfTimeScaleModifier; // 0xb8
	private static __XLua_Gen_Delegate7 __Hotfix0__OnTick; // 0xc0
	private static __XLua_Gen_Delegate7 __Hotfix0__OnTimeScaleChange; // 0xc8
	private static __XLua_Gen_Delegate1 __Hotfix0__ReCalculateTimeScale; // 0xd0

	public Single timeScale { get; }
	public Single baseSelfTimeScale { get; set; }
	public Single selfTimeScale { get; }
	public Boolean ignoreGlobalTimeScale { get; set; }
	public Boolean isReleased { get; set; }
	public Boolean isTicking { get; set; }
	public Int32 frame { get; set; }

	// RVA: 0x674e95c VA: 0x7598d6695c
	public Single get_timeScale() { }
	// RVA: 0x674e9dc VA: 0x7598d669dc
	public Void SetTimeScale(Single inScale) { }
	// RVA: 0x674eba8 VA: 0x7598d66ba8
	public Single get_baseSelfTimeScale() { }
	// RVA: 0x674ec28 VA: 0x7598d66c28
	public Void set_baseSelfTimeScale(Single value) { }
	// RVA: 0x674ee38 VA: 0x7598d66e38
	public Single get_selfTimeScale() { }
	// RVA: 0x674efdc VA: 0x7598d66fdc
	public Boolean get_ignoreGlobalTimeScale() { }
	// RVA: 0x674f05c VA: 0x7598d6705c
	public Void set_ignoreGlobalTimeScale(Boolean value) { }
	// RVA: 0x674f118 VA: 0x7598d67118
	public Boolean get_isReleased() { }
	// RVA: 0x674f198 VA: 0x7598d67198
	private Void set_isReleased(Boolean value) { }
	// RVA: 0x674f230 VA: 0x7598d67230
	public Boolean get_isTicking() { }
	// RVA: 0x674f2b0 VA: 0x7598d672b0
	private Void set_isTicking(Boolean value) { }
	// RVA: 0x674f348 VA: 0x7598d67348
	public Int32 get_frame() { }
	// RVA: 0x674f3c8 VA: 0x7598d673c8
	private Void set_frame(Int32 value) { }
	// RVA: 0x674f45c VA: 0x7598d6745c
	public Void .ctor(ITickOwner owner, Action`1 func, String debugName) { }
	// RVA: 0x674f564 VA: 0x7598d67564
	public Void ClearFrameCount() { }
	// RVA: 0x674f5e8 VA: 0x7598d675e8
	public Void Tick(Single unscaledDeltaTime, Double unscaledTime) { }
	// RVA: 0x674f848 VA: 0x7598d67848
	public Void OnGlobalTimeScaleChange(Single globalTimeScale) { }
	// RVA: 0x674f904 VA: 0x7598d67904
	public Void Start() { }
	// RVA: 0x674f988 VA: 0x7598d67988
	public Void Stop() { }
	// RVA: 0x674fa0c VA: 0x7598d67a0c
	public Void Resume() { }
	// RVA: 0x674fa90 VA: 0x7598d67a90
	public Void Release() { }
	// RVA: 0x674fb38 VA: 0x7598d67b38
	public Int32 AddSelfTimeScaleModifier(Single value) { }
	// RVA: 0x674fcb0 VA: 0x7598d67cb0
	public Void RemoveSelfTimeScaleModifier(Int32 handle) { }
	// RVA: 0x674f6f8 VA: 0x7598d676f8
	private Void _OnTick(Single deltaTime) { }
	// RVA: 0x674ea94 VA: 0x7598d66a94
	private Void _OnTimeScaleChange(Single newTimeScale) { }
	// RVA: 0x674ed24 VA: 0x7598d66d24
	private Void _ReCalculateTimeScale() { }
	// RVA: 0x674fdf0 VA: 0x7598d67df0
	private static Void .cctor() { }
}
```