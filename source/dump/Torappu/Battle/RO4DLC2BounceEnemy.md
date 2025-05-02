# RO4DLC2BounceEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `String _directionEffectKey`

- `RO4DLC2BounceEnemyForceInfo m_RO4DLC2TypeDescriteForceInfo`


## Properties

- `RO4DLC2BounceEnemyForceInfo RO4DLC2TypeDescriteForceInfo`

- `FP kickBackDefaultForce`

- `FP kickBackDamageValue`


## Methods

- `RO4DLC2BounceEnemyForceInfo get_RO4DLC2TypeDescriteForceInfo()`

- `FP get_kickBackDefaultForce()`

- `FP get_kickBackDamageValue()`

- `Vector2 GetVelocity()`

- `Void <>xLuaBaseProxy_ApplyForce(Entity, IForceInfo)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy__UpdateAnimation(FP)`

- `Void <>xLuaBaseProxy_PlayUnbalanceAnimation()`

- `Void <>xLuaBaseProxy__UpdateUnbalanceAnimation()`

- `Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String, String, Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RO4DLC2BounceEnemy : InteractableBounceEnemy
{
	private String _directionEffectKey; // 0x538
	private const Single FORCE_FACTOR; // 0x0
	private const String BOUNCE_AUDIO_SIGNAL; // 0x0
	private RO4DLC2BounceEnemyForceInfo m_RO4DLC2TypeDescriteForceInfo; // 0x540
	private static DelegateBridge __Hotfix0_get_RO4DLC2TypeDescriteForceInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_kickBackDefaultForce; // 0x8
	private static DelegateBridge __Hotfix0_get_kickBackDamageValue; // 0x10
	private static DelegateBridge __Hotfix0_GetVelocity; // 0x18
	private static DelegateBridge __Hotfix0_ApplyForce; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0__UpdateAnimation; // 0x30
	private static DelegateBridge __Hotfix0_PlayUnbalanceAnimation; // 0x38
	private static DelegateBridge __Hotfix0__UpdateUnbalanceAnimation; // 0x40
	private static DelegateBridge __Hotfix0_PreloadSpecialAudioSignals; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public RO4DLC2BounceEnemyForceInfo RO4DLC2TypeDescriteForceInfo { get; }
	public FP kickBackDefaultForce { get; }
	public FP kickBackDamageValue { get; }

	// RVA: 0x1c258d4 VA: 0x759423d8d4
	public RO4DLC2BounceEnemyForceInfo get_RO4DLC2TypeDescriteForceInfo() { }
	// RVA: 0x1c259f4 VA: 0x759423d9f4
	public FP get_kickBackDefaultForce() { }
	// RVA: 0x1c25a5c VA: 0x759423da5c
	public FP get_kickBackDamageValue() { }
	// RVA: 0x1c25ac4 VA: 0x759423dac4
	public Vector2 GetVelocity() { }
	// RVA: 0x1c25b40 VA: 0x759423db40
	public override Void ApplyForce(Entity forceSource, IForceInfo forceInfo) { }
	// RVA: 0x1c25dc4 VA: 0x759423ddc4
	public override Void OnTick(FP fixedDeltaTime) { }
	// RVA: 0x1c25fcc VA: 0x759423dfcc
	protected override Void _UpdateAnimation(FP deltaTime) { }
	// RVA: 0x1c26044 VA: 0x759423e044
	public override Void PlayUnbalanceAnimation() { }
	// RVA: 0x1c260dc VA: 0x759423e0dc
	protected override Void _UpdateUnbalanceAnimation() { }
	// RVA: 0x1c26140 VA: 0x759423e140
	public override Void PreloadSpecialAudioSignals(String characterId, String tmplId, Action`2 preloader) { }
	// RVA: 0x1c26344 VA: 0x759423e344
	public Void .ctor() { }
	// RVA: 0x1c263b0 VA: 0x759423e3b0
	private Void <>xLuaBaseProxy_ApplyForce(Entity P0, IForceInfo P1) { }
	// RVA: 0x1c263b4 VA: 0x759423e3b4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1c263b8 VA: 0x759423e3b8
	private Void <>xLuaBaseProxy__UpdateAnimation(FP P0) { }
	// RVA: 0x1c263bc VA: 0x759423e3bc
	private Void <>xLuaBaseProxy_PlayUnbalanceAnimation() { }
	// RVA: 0x1c263c0 VA: 0x759423e3c0
	private Void <>xLuaBaseProxy__UpdateUnbalanceAnimation() { }
	// RVA: 0x1c263c4 VA: 0x759423e3c4
	private Void <>xLuaBaseProxy_PreloadSpecialAudioSignals(String P0, String P1, Action`2 P2) { }
}
```