# ModifyAbilityAttackTime

**Namespace:** ` `


## Fields

- `String _bbKey`

- `Single _value`

- `Boolean _useOtherAbility`

- `String _abilityName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyAbilityAttackTime : ActionNode
{
	private String _bbKey; // 0x10
	private Single _value; // 0x18
	private Boolean _useOtherAbility; // 0x1c
	private String _abilityName; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f9821c VA: 0x75945b021c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f98284 VA: 0x75945b0284
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9856c VA: 0x75945b056c
	public Void .ctor() { }
}
```