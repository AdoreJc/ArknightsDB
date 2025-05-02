# SetEnemySpecialBlockCondition

**Namespace:** ` `


## Fields

- `ActionTargetType _enemy`

- `Type _type`


## Properties

- `Boolean filterBuffKeyPairs`

- `Boolean filterTags`


## Methods

- `Boolean get_filterBuffKeyPairs()`

- `Boolean get_filterTags()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetEnemySpecialBlockCondition : ActionNode
{
	private ActionTargetType _enemy; // 0x10
	private Type _type; // 0x14
	private List`1 _buffKeyPairs; // 0x18
	private String[] _filterTags; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_filterBuffKeyPairs; // 0x8
	private static DelegateBridge __Hotfix0_get_filterTags; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }
	private Boolean filterBuffKeyPairs { get; }
	private Boolean filterTags { get; }

	// RVA: 0x1fd04c4 VA: 0x75945e84c4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd052c VA: 0x75945e852c
	private Boolean get_filterBuffKeyPairs() { }
	// RVA: 0x1fd05a0 VA: 0x75945e85a0
	private Boolean get_filterTags() { }
	// RVA: 0x1fd0610 VA: 0x75945e8610
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd07b4 VA: 0x75945e87b4
	public Void .ctor() { }
}
```