# EnemyDuelBattleManager

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _enableSafeZone`

- `Vector3 _position`

- `String _cameraEffect`

- `Single _firstSafeZoneInterval`

- `Single _interval`

- `Int32 m_zoneLevel`

- `Boolean m_enableWinBuff`

- `Boolean m_enableSafeZone`

- `Int32 m_mapWidth`

- `Int32 m_mapHeight`

- `Single m_safeZoneInterval`

- `Single m_firstSafeZoneInterval`

- `Boolean m_isRoundOn`

- `Effect m_safeZoneEffect`

- `CameraEffect m_safeZoneCameraEffect`


## Properties

- `CameraEffect safeZoneCameraEffect`


## Methods

- `CameraEffect get_safeZoneCameraEffect()`

- `Void _OnSafeZoneShrink()`

- `Void _OnRoundChanged()`

- `Void _OnRoundStateChanged()`

- `Void _OnRoundStart()`

- `Void _OnRoundEnd()`

- `Void _OnGameOver(Object)`

- `Void <Init>b__28_0(Object)`

- `Void <Init>b__28_1(Object)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnemyDuelBattleManager : EnvManager
{
	private Boolean _enableSafeZone; // 0x28
	private List`1 _buffTileKeyList; // 0x30
	private List`1 _effectList; // 0x38
	private Vector3 _position; // 0x40
	private String _cameraEffect; // 0x50
	private Single _firstSafeZoneInterval; // 0x58
	private Single _interval; // 0x5c
	private BuffData[] _roundStartbuffs; // 0x60
	private Int32 m_zoneLevel; // 0x68
	private Boolean m_enableWinBuff; // 0x6c
	private Boolean m_enableSafeZone; // 0x6d
	private Int32 m_mapWidth; // 0x70
	private Int32 m_mapHeight; // 0x74
	private Single m_safeZoneInterval; // 0x78
	private Single m_firstSafeZoneInterval; // 0x7c
	private Boolean m_isRoundOn; // 0x80
	private Effect m_safeZoneEffect; // 0x88
	private CameraEffect m_safeZoneCameraEffect; // 0x90
	private readonly PeriodicTimer m_intervalTicker; // 0x98
	private readonly List`1 m_tiles; // 0xa0
	private readonly List`1 m_dangerZoneList; // 0xa8
	private const Int32 SAFE_ZONE_ROW_CONST; // 0x0
	private const Int32 SAFE_ZONE_COL_CONST; // 0x0
	private const Int32 MAX_ZONE_LEVEL; // 0x0
	private static DelegateBridge __Hotfix0_get_safeZoneCameraEffect; // 0x0
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x20
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x28
	private static DelegateBridge __Hotfix0__OnSafeZoneShrink; // 0x30
	private static DelegateBridge __Hotfix0__OnRoundChanged; // 0x38
	private static DelegateBridge __Hotfix0__OnRoundStateChanged; // 0x40
	private static DelegateBridge __Hotfix0__OnRoundStart; // 0x48
	private static DelegateBridge __Hotfix0__OnRoundEnd; // 0x50
	private static DelegateBridge __Hotfix0__OnGameOver; // 0x58
	private static DelegateBridge __Hotfix0__GetDangerZoneTilesByLevel; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private CameraEffect safeZoneCameraEffect { get; }
	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x4048e10 VA: 0x7596660e10
	private CameraEffect get_safeZoneCameraEffect() { }
	// RVA: 0x4048f08 VA: 0x7596660f08
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4049074 VA: 0x7596661074
	public override Void Init(GlobalEnvSystem envSystem) { }
	// RVA: 0x4049aa8 VA: 0x7596661aa8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x4049f30 VA: 0x7596661f30
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x4049fe0 VA: 0x7596661fe0
	public override Void GatherBuffs(List`1 buffs) { }
	// RVA: 0x4049be0 VA: 0x7596661be0
	private Void _OnSafeZoneShrink() { }
	// RVA: 0x404a090 VA: 0x7596662090
	private Void _OnRoundChanged() { }
	// RVA: 0x404a508 VA: 0x7596662508
	private Void _OnRoundStateChanged() { }
	// RVA: 0x404a288 VA: 0x7596662288
	private Void _OnRoundStart() { }
	// RVA: 0x404a5bc VA: 0x75966625bc
	private Void _OnRoundEnd() { }
	// RVA: 0x404a7e0 VA: 0x75966627e0
	private Void _OnGameOver(Object arg) { }
	// RVA: 0x4049644 VA: 0x7596661644
	private List`1 _GetDangerZoneTilesByLevel(Int32 level) { }
	// RVA: 0x404a95c VA: 0x759666295c
	public Void .ctor() { }
	// RVA: 0x404aafc VA: 0x7596662afc
	private Void <Init>b__28_0(Object arg) { }
	// RVA: 0x404ab00 VA: 0x7596662b00
	private Void <Init>b__28_1(Object arg) { }
	// RVA: 0x404ab04 VA: 0x7596662b04
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x404ab0c VA: 0x7596662b0c
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x404ab14 VA: 0x7596662b14
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x404ab1c VA: 0x7596662b1c
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x404ab24 VA: 0x7596662b24
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```