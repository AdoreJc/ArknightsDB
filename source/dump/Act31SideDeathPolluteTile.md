# Act31SideDeathPolluteTile

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Single _rangeRadius`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SideDeathPolluteTile : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Single _rangeRadius; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edc600 VA: 0x75944f4600
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edc668 VA: 0x75944f4668
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edcb14 VA: 0x75944f4b14
	public Void .ctor() { }
}
```