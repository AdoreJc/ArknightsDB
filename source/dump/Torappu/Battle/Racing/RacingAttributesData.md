# RacingAttributesData

**Namespace:** `Torappu.Battle.Racing`


## Fields

- `Int32 m_dirtyMask`


## Methods

- `Void RegisterModifiersFromBB(Blackboard, Buff)`

- `Void Reset(RacingEnemyData)`

- `FP GetValue(RacingAttribute)`

- `Void AddModifier(RacingAttributeModifier)`

- `Void RemoveModifier(RacingAttributeModifier)`

- `Void UpdateModifiers()`

- `FP _CalculateAttributeValue(RacingAttribute)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Racing
public class RacingAttributesData : IHotfixable
{
	private static List`1 s_sharedModifiers; // 0x0
	private static readonly Dictionary`2 s_attributeRanges; // 0x8
	private Int32 m_dirtyMask; // 0x10
	private HashSet`1[] m_attributeModifiers; // 0x18
	private ObscuredFP[] m_rawData; // 0x20
	private ObscuredFP[] m_cachedData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge _c__Hotfix1_ctor; // 0x18
	private static DelegateBridge __Hotfix0_RegisterModifiersFromBB; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge __Hotfix0_GetValue; // 0x30
	private static DelegateBridge __Hotfix0_AddModifier; // 0x38
	private static DelegateBridge __Hotfix0_RemoveModifier; // 0x40
	private static DelegateBridge __Hotfix0_UpdateModifiers; // 0x48
	private static DelegateBridge __Hotfix0__CalculateAttributeValue; // 0x50


	// RVA: 0x1d56314 VA: 0x759436e314
	public Void .ctor() { }
	// RVA: 0x1d5641c VA: 0x759436e41c
	public Void .ctor(RacingEnemyData rawData) { }
	// RVA: 0x1d568cc VA: 0x759436e8cc
	public Void RegisterModifiersFromBB(Blackboard blackboard, Buff source) { }
	// RVA: 0x1d56544 VA: 0x759436e544
	public Void Reset(RacingEnemyData rawData) { }
	// RVA: 0x1d57184 VA: 0x759436f184
	public FP GetValue(RacingAttribute attributeType) { }
	// RVA: 0x1d57080 VA: 0x759436f080
	public Void AddModifier(RacingAttributeModifier modifier) { }
	// RVA: 0x1d577d0 VA: 0x759436f7d0
	public Void RemoveModifier(RacingAttributeModifier modifier) { }
	// RVA: 0x1d578d4 VA: 0x759436f8d4
	public Void UpdateModifiers() { }
	// RVA: 0x1d5728c VA: 0x759436f28c
	private FP _CalculateAttributeValue(RacingAttribute attributeType) { }
	// RVA: 0x1d57a98 VA: 0x759436fa98
	private static Void .cctor() { }
}
```