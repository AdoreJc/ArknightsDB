# TalentData

**Namespace:** `Torappu`


## Fields

- `UnlockCondition unlockCondition`

- `Int32 requiredPotentialRank`

- `String prefabKey`

- `String name`

- `String description`

- `String rangeId`

- `Blackboard blackboard`

- `String tokenKey`

- `Boolean isHideTalent`


## Methods

- `Boolean ShouldSerializetokenKey()`

- `TalentData Duplicate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TalentData : IHotfixable
{
	public UnlockCondition unlockCondition; // 0x10
	public Int32 requiredPotentialRank; // 0x18
	public String prefabKey; // 0x20
	public String name; // 0x28
	public String description; // 0x30
	public String rangeId; // 0x38
	public Blackboard blackboard; // 0x40
	public String tokenKey; // 0x48
	public Boolean isHideTalent; // 0x50
	private static DelegateBridge __Hotfix0_ShouldSerializetokenKey; // 0x0
	private static DelegateBridge __Hotfix0_get_displayRange; // 0x8
	private static DelegateBridge __Hotfix0_GetDescription; // 0x10
	private static DelegateBridge __Hotfix0_Duplicate; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public virtual Boolean displayRange { get; }

	// RVA: 0x34f8804 VA: 0x7595b10804
	public Boolean ShouldSerializetokenKey() { }
	// RVA: 0x34f887c VA: 0x7595b1087c
	public virtual Boolean get_displayRange() { }
	// RVA: 0x34f88e0 VA: 0x7595b108e0
	public virtual String GetDescription() { }
	// RVA: 0x34f8948 VA: 0x7595b10948
	public TalentData Duplicate() { }
	// RVA: 0x34f8a78 VA: 0x7595b10a78
	public Void .ctor() { }
}
```