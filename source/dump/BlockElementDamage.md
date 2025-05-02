# BlockElementDamage

**Namespace:** ` `


## Fields

- `Boolean _shieldByAnotherSource`

- `String _sourceBuffKey`

- `ActionTargetType _shieldSource`

- `String _shieldBlackboardKey`


## Properties

- `Boolean shieldByAnotherSource`


## Methods

- `Boolean get_shieldByAnotherSource()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BlockElementDamage : ActionNode
{
	private Boolean _shieldByAnotherSource; // 0x10
	private String _sourceBuffKey; // 0x18
	private ActionTargetType _shieldSource; // 0x20
	private String _shieldBlackboardKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_shieldByAnotherSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public Boolean shieldByAnotherSource { get; }

	// RVA: 0x1f41e28 VA: 0x7594559e28
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f41e90 VA: 0x7594559e90
	public Boolean get_shieldByAnotherSource() { }
	// RVA: 0x1f41ef8 VA: 0x7594559ef8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f42284 VA: 0x759455a284
	public Void .ctor() { }
}
```