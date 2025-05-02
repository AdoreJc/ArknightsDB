# CardBuff

**Namespace:** ` `


## Fields

- `LifeType m_lifeType`

- `UInt32 m_sourceCardUid`

- `String m_key`

- `String m_stackKey`

- `FP m_remainingTime`


## Properties

- `LifeType lifeType`

- `String key`

- `String stackKey`

- `UInt32 sourceCardUid`

- `Buff owner`


## Methods

- `LifeType get_lifeType()`

- `String get_key()`

- `String get_stackKey()`

- `UInt32 get_sourceCardUid()`

- `Buff get_owner()`

- `Void ApplyModifiersFirstPass(Card, ref)`

- `Void ApplyModifiersSecondPass(Card, ref)`

- `Void SetRemainingTime(FP)`

- `Boolean OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CardBuff : IHotfixable
{
	private LifeType m_lifeType; // 0x10
	private ObjectPtr`1 m_owner; // 0x18
	private UInt32 m_sourceCardUid; // 0x28
	private CardBuffModifier[] m_modifiers; // 0x30
	private String m_key; // 0x38
	private String m_stackKey; // 0x40
	private FP m_remainingTime; // 0x48
	private static DelegateBridge __Hotfix0_get_lifeType; // 0x0
	private static DelegateBridge __Hotfix0_get_key; // 0x8
	private static DelegateBridge __Hotfix0_get_stackKey; // 0x10
	private static DelegateBridge __Hotfix0_get_sourceCardUid; // 0x18
	private static DelegateBridge __Hotfix0_get_owner; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28
	private static DelegateBridge _c__Hotfix1_ctor; // 0x30
	private static DelegateBridge _c__Hotfix2_ctor; // 0x38
	private static DelegateBridge __Hotfix0_ApplyModifiersFirstPass; // 0x40
	private static DelegateBridge __Hotfix0_ApplyModifiersSecondPass; // 0x48
	private static DelegateBridge __Hotfix0_SetRemainingTime; // 0x50
	private static DelegateBridge __Hotfix0_OnTick; // 0x58

	public LifeType lifeType { get; }
	public String key { get; }
	public String stackKey { get; }
	public UInt32 sourceCardUid { get; }
	public Buff owner { get; }

	// RVA: 0x3fb49d0 VA: 0x75965cc9d0
	public LifeType get_lifeType() { }
	// RVA: 0x3fb4a38 VA: 0x75965cca38
	public String get_key() { }
	// RVA: 0x3fb4aa0 VA: 0x75965ccaa0
	public String get_stackKey() { }
	// RVA: 0x3fb4b08 VA: 0x75965ccb08
	public UInt32 get_sourceCardUid() { }
	// RVA: 0x3fb4b70 VA: 0x75965ccb70
	public Buff get_owner() { }
	// RVA: 0x3fb4c38 VA: 0x75965ccc38
	public Void .ctor(String key, LifeType lifeType, CardBuffModifier[] modifiers) { }
	// RVA: 0x3fb4e64 VA: 0x75965cce64
	public Void .ctor(Card sourceCard, LifeType lifeType, String key, CardBuffModifier[] modifiers) { }
	// RVA: 0x3fb50ec VA: 0x75965cd0ec
	public Void .ctor(Buff sourceBuff, LifeType lifeType, String key, CardBuffModifier[] modifiers) { }
	// RVA: 0x3fb5384 VA: 0x75965cd384
	public Void ApplyModifiersFirstPass(Card card, ref CardBuffOptions options) { }
	// RVA: 0x3fb5488 VA: 0x75965cd488
	public Void ApplyModifiersSecondPass(Card card, ref CardBuffOptions options) { }
	// RVA: 0x3fb558c VA: 0x75965cd58c
	public Void SetRemainingTime(FP remainingTime) { }
	// RVA: 0x3fb5608 VA: 0x75965cd608
	public Boolean OnTick(FP deltaTime) { }
}
```