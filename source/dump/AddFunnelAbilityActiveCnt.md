# AddFunnelAbilityActiveCnt

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `Int32 _addCnt`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddFunnelAbilityActiveCnt : ActionNode
{
	private ActionTargetType _source; // 0x10
	private String[] _abilityNames; // 0x18
	private Int32 _addCnt; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f98a84 VA: 0x75945b0a84
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f98aec VA: 0x75945b0aec
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f98ff0 VA: 0x75945b0ff0
	public Void .ctor() { }
}
```