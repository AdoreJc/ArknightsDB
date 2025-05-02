# EnvEnableBuffToTargetsOnTile

**Namespace:** `Torappu.Battle`


## Fields

- `TargetOptions _targetOptions`

- `String _attachStatus`

- `String _detachStatus`

- `Int32 _tickInterval`

- `PeriodicTicker m_ticker`


## Methods

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnEnvChanged(Tile, String)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvEnableBuffToTargetsOnTile : EnvEventExecutor
{
	private TargetOptions _targetOptions; // 0x28
	private BuffData[] _buffs; // 0x88
	private String _attachStatus; // 0x90
	private String _detachStatus; // 0x98
	private Int32 _tickInterval; // 0xa0
	private PeriodicTicker m_ticker; // 0xa8
	private ListDict`2 m_tileWithListeners; // 0xb0
	private ObjectPool`1 m_listenerPool; // 0xb8
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x4020278 VA: 0x7596638278
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x40203d0 VA: 0x75966383d0
	public override Void OnEnvChanged(Tile tile, String status) { }
	// RVA: 0x4020624 VA: 0x7596638624
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x4020868 VA: 0x7596638868
	private Void OnDestroy() { }
	// RVA: 0x4020a84 VA: 0x7596638a84
	public Void .ctor() { }
	// RVA: 0x4020b90 VA: 0x7596638b90
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4020b98 VA: 0x7596638b98
	private Void <>xLuaBaseProxy_OnEnvChanged(Tile P0, String P1) { }
	// RVA: 0x4020ba0 VA: 0x7596638ba0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```