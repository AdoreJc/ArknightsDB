# AutoChessTimeOutGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _assginOnTimeNotReach`

- `String _timeOutCameraEffect`

- `AutoChessGameMode m_gameMode`

- `PeriodicTimer m_levelTimer`

- `Boolean m_isTimeReached`

- `Boolean m_isRoundStarted`

- `CameraEffect m_timeOutCameraEffect`


## Properties

- `Boolean isTimeReached`

- `Boolean isGlobalBuffValid`


## Methods

- `Boolean get_isTimeReached()`

- `Void set_isTimeReached(Boolean)`

- `Boolean get_isGlobalBuffValid()`

- `Void _OnRoundStarted(Object)`

- `Void OnDestroy()`

- `Void _SetLevelTimer()`

- `Void _MarkInvalid()`

- `Void _UpdateBuffsWhenValidChanged()`

- `Void _UpdateTimeOutCameraEffect()`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_TryAddBuff(Unit, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AutoChessTimeOutGlobalBuff : GlobalBuff
{
	private Boolean _assginOnTimeNotReach; // 0xdc
	private String _timeOutCameraEffect; // 0xe0
	private AutoChessGameMode m_gameMode; // 0xe8
	private PeriodicTimer m_levelTimer; // 0xf0
	private Boolean m_isTimeReached; // 0xf8
	private Boolean m_isRoundStarted; // 0xf9
	private CameraEffect m_timeOutCameraEffect; // 0x100
	private static DelegateBridge __Hotfix0_get_isTimeReached; // 0x0
	private static DelegateBridge __Hotfix0_set_isTimeReached; // 0x8
	private static DelegateBridge __Hotfix0_get_isGlobalBuffValid; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0_TryAddBuff; // 0x28
	private static DelegateBridge __Hotfix0__OnRoundStarted; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0__SetLevelTimer; // 0x40
	private static DelegateBridge __Hotfix0__MarkInvalid; // 0x48
	private static DelegateBridge __Hotfix0__UpdateBuffsWhenValidChanged; // 0x50
	private static DelegateBridge __Hotfix0__UpdateTimeOutCameraEffect; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Boolean isTimeReached { get; set; }
	private Boolean isGlobalBuffValid { get; }

	// RVA: 0x4013548 VA: 0x759662b548
	private Boolean get_isTimeReached() { }
	// RVA: 0x40135b0 VA: 0x759662b5b0
	private Void set_isTimeReached(Boolean value) { }
	// RVA: 0x4013928 VA: 0x759662b928
	private Boolean get_isGlobalBuffValid() { }
	// RVA: 0x40139c8 VA: 0x759662b9c8
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x4013e7c VA: 0x759662be7c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x4013fdc VA: 0x759662bfdc
	public override Void TryAddBuff(Unit unit, Boolean isInit) { }
	// RVA: 0x4014084 VA: 0x759662c084
	private Void _OnRoundStarted(Object _) { }
	// RVA: 0x4014104 VA: 0x759662c104
	private Void OnDestroy() { }
	// RVA: 0x4013c80 VA: 0x759662bc80
	private Void _SetLevelTimer() { }
	// RVA: 0x4014220 VA: 0x759662c220
	private Void _MarkInvalid() { }
	// RVA: 0x40137c4 VA: 0x759662b7c4
	private Void _UpdateBuffsWhenValidChanged() { }
	// RVA: 0x401365c VA: 0x759662b65c
	private Void _UpdateTimeOutCameraEffect() { }
	// RVA: 0x4014370 VA: 0x759662c370
	public Void .ctor() { }
	// RVA: 0x40143dc VA: 0x759662c3dc
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
	// RVA: 0x40143e0 VA: 0x759662c3e0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x40143e4 VA: 0x759662c3e4
	private Void <>xLuaBaseProxy_TryAddBuff(Unit P0, Boolean P1) { }
}
```