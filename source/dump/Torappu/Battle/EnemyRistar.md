# EnemyRistar

**Namespace:** `Torappu.Battle`


## Fields

- `String _hitRangeId`

- `Boolean m_useHitRange`

- `Int32 m_hitCount`

- `Int32 m_maxHitCount`

- `Buff m_hitCounter`

- `String m_maxHitCountKey`


## Properties

- `Int32 maxHitCount`

- `Buff hitCounter`


## Methods

- `Int32 get_maxHitCount()`

- `Buff get_hitCounter()`

- `FP _RemainingHitRatio()`

- `Void UpdateHitCount(Boolean)`

- `String <>xLuaBaseProxy_get_hitRangeId()`

- `FP <>xLuaBaseProxy_get_spShowedBuffProgress()`

- `Void <>xLuaBaseProxy_OnSwitchMode(UnitMode, UnitMode, Boolean)`

- `Void <>xLuaBaseProxy_OnTakeDamage(ref, Boolean)`

- `Void <>xLuaBaseProxy_KnockBack(Vector2, Single, Boolean)`

- `Boolean <>xLuaBaseProxy_BeginPull(BObject, Vector2, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnemyRistar : Enemy
{
	private List`1 _modeIndexToUseHitRange; // 0x4b8
	private String _hitRangeId; // 0x4c0
	private Boolean m_useHitRange; // 0x4c8
	private Int32 m_hitCount; // 0x4cc
	private Int32 m_maxHitCount; // 0x4d0
	private Buff m_hitCounter; // 0x4d8
	private String m_maxHitCountKey; // 0x4e0
	private static DelegateBridge __Hotfix0_get_maxHitCount; // 0x0
	private static DelegateBridge __Hotfix0_get_hitCounter; // 0x8
	private static DelegateBridge __Hotfix0_get_hitRangeId; // 0x10
	private static DelegateBridge __Hotfix0_get_spShowedBuffProgress; // 0x18
	private static DelegateBridge __Hotfix0__RemainingHitRatio; // 0x20
	private static DelegateBridge __Hotfix0_OnSwitchMode; // 0x28
	private static DelegateBridge __Hotfix0_UpdateHitCount; // 0x30
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0x38
	private static DelegateBridge __Hotfix0_KnockBack; // 0x40
	private static DelegateBridge __Hotfix0_BeginPull; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Int32 maxHitCount { get; }
	private Buff hitCounter { get; }
	public override String hitRangeId { get; }
	public override FP spShowedBuffProgress { get; }

	// RVA: 0x1c1aa5c VA: 0x7594232a5c
	private Int32 get_maxHitCount() { }
	// RVA: 0x1c1ab1c VA: 0x7594232b1c
	private Buff get_hitCounter() { }
	// RVA: 0x1c1abd4 VA: 0x7594232bd4
	public override String get_hitRangeId() { }
	// RVA: 0x1c1ac68 VA: 0x7594232c68
	public override FP get_spShowedBuffProgress() { }
	// RVA: 0x1c1ad2c VA: 0x7594232d2c
	private FP _RemainingHitRatio() { }
	// RVA: 0x1c1ade4 VA: 0x7594232de4
	protected override Void OnSwitchMode(UnitMode next, UnitMode last, Boolean restartFSM) { }
	// RVA: 0x1c1aedc VA: 0x7594232edc
	public Void UpdateHitCount(Boolean clearCount) { }
	// RVA: 0x1c1afd4 VA: 0x7594232fd4
	protected override Void OnTakeDamage(ref Modifier modifier, Boolean force) { }
	// RVA: 0x1c1b0c4 VA: 0x75942330c4
	public override Void KnockBack(Vector2 dir, Single force, Boolean changeFaceByDirection) { }
	// RVA: 0x1c1b1e4 VA: 0x75942331e4
	public override Boolean BeginPull(BObject source, Vector2 dir, Single force) { }
	// RVA: 0x1c1b28c VA: 0x759423328c
	public Void .ctor() { }
	// RVA: 0x1c1b3dc VA: 0x75942333dc
	private String <>xLuaBaseProxy_get_hitRangeId() { }
	// RVA: 0x1c1b3e4 VA: 0x75942333e4
	private FP <>xLuaBaseProxy_get_spShowedBuffProgress() { }
	// RVA: 0x1c1b3ec VA: 0x75942333ec
	private Void <>xLuaBaseProxy_OnSwitchMode(UnitMode P0, UnitMode P1, Boolean P2) { }
	// RVA: 0x1c1b3f8 VA: 0x75942333f8
	private Void <>xLuaBaseProxy_OnTakeDamage(ref Modifier P0, Boolean P1) { }
	// RVA: 0x1c1b404 VA: 0x7594233404
	private Void <>xLuaBaseProxy_KnockBack(Vector2 P0, Single P1, Boolean P2) { }
	// RVA: 0x1c1b410 VA: 0x7594233410
	private Boolean <>xLuaBaseProxy_BeginPull(BObject P0, Vector2 P1, Single P2) { }
}
```