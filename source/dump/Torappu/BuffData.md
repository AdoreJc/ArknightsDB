# BuffData

**Namespace:** `Torappu`


## Fields

- `AttributeModifierData attributes`

- `String buffKey`

- `Boolean loadFromDB`

- `Boolean isDurableBuff`

- `Boolean isDamageMissable`

- `Boolean isSilenceable`

- `Boolean isStunnable`

- `Boolean isFreezable`

- `Boolean isLevitatable`

- `StatusResistable statusResistable`

- `String templateKey`

- `Boolean disableOverride`

- `String overrideKey`

- `OverrideType overrideType`

- `Int32 maxStackCnt`

- `Boolean refreshRemainingTimeWhenStackMax`

- `Boolean clearAllStackCntWhenTimeUp`

- `Int32 maxValidStackCnt`

- `Boolean independentCharacterSource`

- `String overrideEffectKey`

- `Boolean overrideOnEventPriority`

- `OnEventPriority onEventPriority`

- `String audioSignal`

- `LifeType lifeTimeType`

- `Boolean takeSnapshotWhenExtend`

- `String durationKey`

- `Single lifeTime`

- `LifeType triggerLifeType`

- `Int32 triggerCnt`

- `Single triggerInterval`

- `Boolean waitFirstTriggerInterval`

- `Single firstTriggerInterval`

- `Int32 priority`

- `Boolean stripBlackboardParamsWithBuffKey`


## Properties

- `Boolean isAutoPriority`


## Methods

- `Boolean get_isAutoPriority()`

- `String GetOverrideKey()`

- `BuffData EnsureBuffData()`

- `BuffData DeepClone()`

- `String <>xLuaBaseProxy_ToString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuffData : IHotfixable
{
	public AttributeModifierData attributes; // 0x10
	public String buffKey; // 0x18
	public Boolean loadFromDB; // 0x20
	public Boolean isDurableBuff; // 0x21
	public Boolean isDamageMissable; // 0x22
	public Boolean isSilenceable; // 0x23
	public Boolean isStunnable; // 0x24
	public Boolean isFreezable; // 0x25
	public Boolean isLevitatable; // 0x26
	public StatusResistable statusResistable; // 0x27
	public String templateKey; // 0x28
	public Boolean disableOverride; // 0x30
	public String overrideKey; // 0x38
	public OverrideType overrideType; // 0x40
	public Int32 maxStackCnt; // 0x44
	public Boolean refreshRemainingTimeWhenStackMax; // 0x48
	public Boolean clearAllStackCntWhenTimeUp; // 0x49
	public Int32 maxValidStackCnt; // 0x4c
	public Boolean independentCharacterSource; // 0x50
	public String overrideEffectKey; // 0x58
	public Boolean overrideOnEventPriority; // 0x60
	public OnEventPriority onEventPriority; // 0x64
	public String audioSignal; // 0x68
	public LifeType lifeTimeType; // 0x70
	public Boolean takeSnapshotWhenExtend; // 0x71
	public String durationKey; // 0x78
	public Single lifeTime; // 0x80
	public LifeType triggerLifeType; // 0x84
	public Int32 triggerCnt; // 0x88
	public Single triggerInterval; // 0x8c
	public Boolean waitFirstTriggerInterval; // 0x90
	public Single firstTriggerInterval; // 0x94
	public Int32 priority; // 0x98
	public String[] priorityBBKeys; // 0xa0
	public Boolean stripBlackboardParamsWithBuffKey; // 0xa8
	public List`1 blackboard; // 0xb0
	private static DelegateBridge __Hotfix0_get_isAutoPriority; // 0x0
	private static DelegateBridge __Hotfix0_GetOverrideKey; // 0x8
	private static DelegateBridge __Hotfix0_ToString; // 0x10
	private static DelegateBridge __Hotfix0_EnsureBuffData; // 0x18
	private static DelegateBridge __Hotfix0_DeepClone; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isAutoPriority { get; }

	// RVA: 0x33c5f3c VA: 0x75959ddf3c
	public Boolean get_isAutoPriority() { }
	// RVA: 0x33c5fa8 VA: 0x75959ddfa8
	public String GetOverrideKey() { }
	// RVA: 0x33c6054 VA: 0x75959de054
	public override String ToString() { }
	// RVA: 0x33c6274 VA: 0x75959de274
	public BuffData EnsureBuffData() { }
	// RVA: 0x33c630c VA: 0x75959de30c
	public BuffData DeepClone() { }
	// RVA: 0x33c64fc VA: 0x75959de4fc
	public Void .ctor() { }
	// RVA: 0x33c660c VA: 0x75959de60c
	private String <>xLuaBaseProxy_ToString() { }
}
```