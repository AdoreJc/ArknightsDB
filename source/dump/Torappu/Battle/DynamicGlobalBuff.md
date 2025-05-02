# DynamicGlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _untickInWavePostDelay`

- `FP m_refreshInterval`

- `FP m_nextRefreshTime`

- `FP m_wavePostDelayLastTime`

- `Int32 m_stackCnt`

- `Int32 m_maxStackCnt`

- `Int32 m_curStackCntIndex`

- `Blackboard m_scaledBlackboard`

- `LegionUIPlugin m_legionPlugin`

- `LegionGameMode m_gameMode`


## Methods

- `Void _RefreshBuff()`

- `Void _UpdateMaxStackCnt()`

- `Boolean _RefreshBlackboard(Boolean)`

- `Void _RefreshLegionModeDangerLevel()`

- `Void _OnWaveWillStart()`

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_OnInit(GlobalBuffData)`

- `Void <>xLuaBaseProxy_TryAddBuff(Unit, Boolean)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DynamicGlobalBuff : GlobalBuff, IHotfixable
{
	private List`1 _keysScaleWithTime; // 0xe0
	private Boolean _untickInWavePostDelay; // 0xe8
	private List`1 _initBlackboard; // 0xf0
	private readonly List`1 m_buffs; // 0xf8
	private readonly List`1 m_buffDataIndices; // 0x100
	private FP m_refreshInterval; // 0x108
	private FP m_nextRefreshTime; // 0x110
	private FP m_wavePostDelayLastTime; // 0x118
	private Int32 m_stackCnt; // 0x120
	private Int32 m_maxStackCnt; // 0x124
	private Int32 m_curStackCntIndex; // 0x128
	private List`1 m_stackCntLimit; // 0x130
	private Blackboard m_scaledBlackboard; // 0x138
	private LegionUIPlugin m_legionPlugin; // 0x140
	private LegionGameMode m_gameMode; // 0x148
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_TryAddBuff; // 0x8
	private static DelegateBridge __Hotfix0__RefreshBuff; // 0x10
	private static DelegateBridge __Hotfix0__UpdateMaxStackCnt; // 0x18
	private static DelegateBridge __Hotfix0__RefreshBlackboard; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0__RefreshLegionModeDangerLevel; // 0x30
	private static DelegateBridge __Hotfix0__OnWaveWillStart; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x401694c VA: 0x759662e94c
	public override Void OnInit(GlobalBuffData data) { }
	// RVA: 0x40172fc VA: 0x759662f2fc
	public override Void TryAddBuff(Unit unit, Boolean isInit) { }
	// RVA: 0x40175b8 VA: 0x759662f5b8
	private Void _RefreshBuff() { }
	// RVA: 0x4017854 VA: 0x759662f854
	private Void _UpdateMaxStackCnt() { }
	// RVA: 0x401708c VA: 0x759662f08c
	private Boolean _RefreshBlackboard(Boolean force) { }
	// RVA: 0x4017aa0 VA: 0x759662faa0
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x40179b0 VA: 0x759662f9b0
	private Void _RefreshLegionModeDangerLevel() { }
	// RVA: 0x4017e8c VA: 0x759662fe8c
	private Void _OnWaveWillStart() { }
	// RVA: 0x4017ef4 VA: 0x759662fef4
	public Void OnDestroy() { }
	// RVA: 0x4018018 VA: 0x7596630018
	public Void .ctor() { }
	// RVA: 0x401815c VA: 0x759663015c
	private Void <>xLuaBaseProxy_OnInit(GlobalBuffData P0) { }
	// RVA: 0x4018160 VA: 0x7596630160
	private Void <>xLuaBaseProxy_TryAddBuff(Unit P0, Boolean P1) { }
	// RVA: 0x4018168 VA: 0x7596630168
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```