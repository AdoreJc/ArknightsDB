# GlobalBuff

**Namespace:** `Torappu.Battle`


## Fields

- `String _key`

- `TargetOptions _options`

- `String _overrideCameraEffect`

- `SideTypeIndex _sourceType`

- `GlobalBuffExtraValidatorDelegate m_extraValidator`

- `Int32 m_layerMask`

- `String m_overrideCameraEffect`

- `Int32 m_buffAddLimitedTimes`

- `Boolean m_checkExtraProfession`

- `Blackboard blackboard`

- `UInt32 <instanceUid>k__BackingField`


## Properties

- `String overrideCameraEffect`

- `String key`

- `Boolean hasKey`

- `UInt32 instanceUid`


## Methods

- `String get_overrideCameraEffect()`

- `String get_key()`

- `Boolean get_hasKey()`

- `Void GatherBuffs(List`1)`

- `Void TryAddDeckBuff(Unit, ref)`

- `Void ModifyBlackboard(String, FP)`

- `Boolean _VerifyBuffAddTimes(Unit)`

- `Boolean _VerifyBuffExist(Unit)`

- `Void _OverrideByExtraData(ExtraRuntimeData)`

- `Boolean _VerifyTarget(Unit)`

- `Void OnAllocate()`

- `Void OnRecycle()`

- `UInt32 get_instanceUid()`

- `Void set_instanceUid(UInt32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GlobalBuff : MonoBehaviour, IBuffSource, IEffectSource, IHotfixable, IReusableObject, IReusable, IPtrObject
{
	private String _key; // 0x18
	protected TargetOptions _options; // 0x20
	protected BuffData[] _buffs; // 0x80
	private String _overrideCameraEffect; // 0x88
	private DeckBuff[] _deckBuffs; // 0x90
	private SideTypeIndex _sourceType; // 0x98
	private GlobalBuffExtraValidatorDelegate m_extraValidator; // 0xa0
	private Int32 m_layerMask; // 0xa8
	private String m_overrideCameraEffect; // 0xb0
	private Int32 m_buffAddLimitedTimes; // 0xb8
	private Dictionary`2 m_cachedAddedUnits; // 0xc0
	private Boolean m_checkExtraProfession; // 0xc8
	public Blackboard blackboard; // 0xd0
	private static UInt32 s_globalCounter; // 0x0
	private UInt32 <instanceUid>k__BackingField; // 0xd8
	private static DelegateBridge __Hotfix0_get_overrideCameraEffect; // 0x8
	private static DelegateBridge __Hotfix0_get_key; // 0x10
	private static DelegateBridge __Hotfix0_get_hasKey; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x28
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x30
	private static DelegateBridge __Hotfix0_OnInit; // 0x38
	private static DelegateBridge __Hotfix0_TryAddBuff; // 0x40
	private static DelegateBridge __Hotfix0_TryRemoveBuff; // 0x48
	private static DelegateBridge __Hotfix0_TryAddDeckBuff; // 0x50
	private static DelegateBridge __Hotfix0_ModifyBlackboard; // 0x58
	private static DelegateBridge __Hotfix0__VerifyBuffAddTimes; // 0x60
	private static DelegateBridge __Hotfix0__VerifyBuffExist; // 0x68
	private static DelegateBridge __Hotfix0__OverrideByExtraData; // 0x70
	private static DelegateBridge __Hotfix0__VerifyTarget; // 0x78
	private static DelegateBridge __Hotfix0_OnReset; // 0x80
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x88
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x90
	private static DelegateBridge __Hotfix0_get_instanceUid; // 0x98
	private static DelegateBridge __Hotfix0_set_instanceUid; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public String overrideCameraEffect { get; }
	public String key { get; }
	public Boolean hasKey { get; }
	public UInt32 instanceUid { get; set; }

	// RVA: 0x4018e9c VA: 0x7596630e9c
	public String get_overrideCameraEffect() { }
	// RVA: 0x4018f1c VA: 0x7596630f1c
	public String get_key() { }
	// RVA: 0x4018f84 VA: 0x7596630f84
	public Boolean get_hasKey() { }
	// RVA: 0x4013f64 VA: 0x759662bf64
	public virtual Void OnTick(FP deltaTime) { }
	// RVA: 0x4018ffc VA: 0x7596630ffc
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x4012f7c VA: 0x759662af7c
	public virtual Void GatherEffects(List`1 effects) { }
	// RVA: 0x40126ac VA: 0x759662a6ac
	public virtual Void OnInit(GlobalBuffData data) { }
	// RVA: 0x40129f4 VA: 0x759662a9f4
	public virtual Void TryAddBuff(Unit unit, Boolean isInit) { }
	// RVA: 0x4012ca0 VA: 0x759662aca0
	public virtual Void TryRemoveBuff(Unit unit, Boolean isInit) { }
	// RVA: 0x401945c VA: 0x759663145c
	public Void TryAddDeckBuff(Unit unit, ref List`1 deckBuffs) { }
	// RVA: 0x40195fc VA: 0x75966315fc
	public Void ModifyBlackboard(String blackboardKey, FP value) { }
	// RVA: 0x4019224 VA: 0x7596631224
	private Boolean _VerifyBuffAddTimes(Unit unit) { }
	// RVA: 0x4019344 VA: 0x7596631344
	private Boolean _VerifyBuffExist(Unit unit) { }
	// RVA: 0x4019180 VA: 0x7596631180
	private Void _OverrideByExtraData(ExtraRuntimeData extraData) { }
	// RVA: 0x4017530 VA: 0x759662f530
	protected Boolean _VerifyTarget(Unit unit) { }
	// RVA: 0x40132f4 VA: 0x759662b2f4
	public virtual Void OnReset() { }
	// RVA: 0x40196a0 VA: 0x75966316a0
	public Void OnAllocate() { }
	// RVA: 0x4019790 VA: 0x7596631790
	public Void OnRecycle() { }
	// RVA: 0x40197fc VA: 0x75966317fc
	public UInt32 get_instanceUid() { }
	// RVA: 0x4019714 VA: 0x7596631714
	private Void set_instanceUid(UInt32 value) { }
	// RVA: 0x4013468 VA: 0x759662b468
	public Void .ctor() { }
}
```