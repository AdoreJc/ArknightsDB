# SpController

**Namespace:** ` `


## Fields

- `SpType m_spType`

- `Entity m_owner`

- `ObscuredInt m_spCost`

- `PrecisePeriodicTimer m_spRecoverTimer`


## Properties

- `Boolean isFull`

- `Boolean isTimerValid`

- `SpType spType`

- `FP progressToFull`

- `FP progressToReady`

- `FP progressToNext`

- `Boolean spCostZero`


## Methods

- `Boolean get_isFull()`

- `Boolean get_isTimerValid()`

- `SpType get_spType()`

- `FP get_progressToFull()`

- `FP get_progressToReady()`

- `FP get_progressToNext()`

- `Boolean get_spCostZero()`

- `Void MarkInvalid()`

- `Void Reset(Entity, SpData)`

- `Void ResetSpTimer()`

- `Void UpdateSpData(SpData, Boolean)`

- `Void OnTakeDamage(ref)`

- `Void OnOutputAttackOrHeal(Ability)`

- `Void UpdateSpRecoveryPerSec(FP, FP)`

- `Void OnTick(FP)`

- `Void _RecoverMp(FP, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SpController : IHotfixable
{
	private SpType m_spType; // 0x10
	private Entity m_owner; // 0x18
	private ObscuredInt m_spCost; // 0x20
	private Single[] m_increments; // 0x38
	private PrecisePeriodicTimer m_spRecoverTimer; // 0x40
	private static DelegateBridge __Hotfix0_get_isFull; // 0x0
	private static DelegateBridge __Hotfix0_get_isTimerValid; // 0x8
	private static DelegateBridge __Hotfix0_get_spType; // 0x10
	private static DelegateBridge __Hotfix0_get_progressToFull; // 0x18
	private static DelegateBridge __Hotfix0_get_progressToReady; // 0x20
	private static DelegateBridge __Hotfix0_get_progressToNext; // 0x28
	private static DelegateBridge __Hotfix0_get_spCostZero; // 0x30
	private static DelegateBridge __Hotfix0_MarkInvalid; // 0x38
	private static DelegateBridge __Hotfix0_Reset; // 0x40
	private static DelegateBridge __Hotfix0_ResetSpTimer; // 0x48
	private static DelegateBridge __Hotfix0_UpdateSpData; // 0x50
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0x58
	private static DelegateBridge __Hotfix0_OnOutputAttackOrHeal; // 0x60
	private static DelegateBridge __Hotfix0_UpdateSpRecoveryPerSec; // 0x68
	private static DelegateBridge __Hotfix0_OnTick; // 0x70
	private static DelegateBridge __Hotfix0__RecoverMp; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Boolean isFull { get; }
	public Boolean isTimerValid { get; }
	public SpType spType { get; }
	public FP progressToFull { get; }
	public FP progressToReady { get; }
	public FP progressToNext { get; }
	public Boolean spCostZero { get; }

	// RVA: 0x3fd1704 VA: 0x75965e9704
	public Boolean get_isFull() { }
	// RVA: 0x3fd17d8 VA: 0x75965e97d8
	public Boolean get_isTimerValid() { }
	// RVA: 0x3fd184c VA: 0x75965e984c
	public SpType get_spType() { }
	// RVA: 0x3fd18b4 VA: 0x75965e98b4
	public FP get_progressToFull() { }
	// RVA: 0x3fd1a38 VA: 0x75965e9a38
	public FP get_progressToReady() { }
	// RVA: 0x3fd1c24 VA: 0x75965e9c24
	public FP get_progressToNext() { }
	// RVA: 0x3fd1dd0 VA: 0x75965e9dd0
	public Boolean get_spCostZero() { }
	// RVA: 0x3fd1e98 VA: 0x75965e9e98
	public Void MarkInvalid() { }
	// RVA: 0x3fd1f0c VA: 0x75965e9f0c
	public Void Reset(Entity owner, SpData data) { }
	// RVA: 0x3fd2070 VA: 0x75965ea070
	public Void ResetSpTimer() { }
	// RVA: 0x3fd20e8 VA: 0x75965ea0e8
	public Void UpdateSpData(SpData data, Boolean onlyUpdateSpCost) { }
	// RVA: 0x3fd2248 VA: 0x75965ea248
	public Void OnTakeDamage(ref Modifier modifier) { }
	// RVA: 0x3fd2488 VA: 0x75965ea488
	public Void OnOutputAttackOrHeal(Ability ability) { }
	// RVA: 0x3fd2584 VA: 0x75965ea584
	public Void UpdateSpRecoveryPerSec(FP newValue, FP oldValue) { }
	// RVA: 0x3fd270c VA: 0x75965ea70c
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x3fd2380 VA: 0x75965ea380
	private Void _RecoverMp(FP value, Boolean force) { }
	// RVA: 0x3fd2844 VA: 0x75965ea844
	public Void .ctor() { }
}
```