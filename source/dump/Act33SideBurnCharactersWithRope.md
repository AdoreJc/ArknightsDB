# Act33SideBurnCharactersWithRope

**Namespace:** ` `


## Fields

- `DamageType _damageType`

- `String _damageKey`

- `ActionTargetType _sourceType`

- `Boolean _isFixedEpDamage`

- `ElementType _elementDamageType`

- `String _fixedEpDamageKey`


## Properties

- `Boolean isFixedEpDamage`


## Methods

- `Boolean get_isFixedEpDamage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act33SideBurnCharactersWithRope : ActionNode
{
	private DamageType _damageType; // 0x10
	private String _damageKey; // 0x18
	private ActionTargetType _sourceType; // 0x20
	private Boolean _isFixedEpDamage; // 0x24
	protected ElementType _elementDamageType; // 0x28
	private String _fixedEpDamageKey; // 0x30
	private static DelegateBridge __Hotfix0_get_isFixedEpDamage; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Boolean isFixedEpDamage { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1ede8e4 VA: 0x75944f68e4
	private Boolean get_isFixedEpDamage() { }
	// RVA: 0x1ede94c VA: 0x75944f694c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ede9b4 VA: 0x75944f69b4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edecc4 VA: 0x75944f6cc4
	public Void .ctor() { }
}
```