# FilterAbilityName

**Namespace:** ` `


## Fields

- `String _abilityName`

- `Boolean _useSearchName`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterAbilityName : ActionNode
{
	private String _abilityName; // 0x10
	private Boolean _useSearchName; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f163b0 VA: 0x759452e3b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f16418 VA: 0x759452e418
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f16530 VA: 0x759452e530
	public Void .ctor() { }
}
```