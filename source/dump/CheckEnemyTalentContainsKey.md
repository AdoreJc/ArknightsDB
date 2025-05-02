# CheckEnemyTalentContainsKey

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckEnemyTalentContainsKey : ActionNode
{
	private ActionTargetType _source; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f8033c VA: 0x759459833c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f803a4 VA: 0x75945983a4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f80548 VA: 0x7594598548
	public Void .ctor() { }
}
```