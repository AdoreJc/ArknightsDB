# TraitData

**Namespace:** ` `


## Fields

- `UnlockCondition unlockCondition`

- `Int32 requiredPotentialRank`

- `Blackboard blackboard`

- `String overrideDescripton`

- `String prefabKey`

- `String rangeId`


## Methods

- `String ConcatTraitDescription(String)`

- `TraitData Duplicate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TraitData : IHotfixable
{
	public UnlockCondition unlockCondition; // 0x10
	public Int32 requiredPotentialRank; // 0x18
	public Blackboard blackboard; // 0x20
	public String overrideDescripton; // 0x28
	public String prefabKey; // 0x30
	public String rangeId; // 0x38
	private static DelegateBridge __Hotfix0_get_additionalDesc; // 0x0
	private static DelegateBridge __Hotfix0_ConcatTraitDescription; // 0x8
	private static DelegateBridge __Hotfix0_Duplicate; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public virtual String additionalDesc { get; }

	// RVA: 0x33c9658 VA: 0x75959e1658
	public virtual String get_additionalDesc() { }
	// RVA: 0x33c8830 VA: 0x75959e0830
	public String ConcatTraitDescription(String defaultDescription) { }
	// RVA: 0x33c96dc VA: 0x75959e16dc
	public TraitData Duplicate() { }
	// RVA: 0x33c97e8 VA: 0x75959e17e8
	public Void .ctor() { }
}
```