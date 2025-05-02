# Act27sideAddTilesToEnemySideBlackList

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act27sideAddTilesToEnemySideBlackList : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eda86c VA: 0x75944f286c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eda8d4 VA: 0x75944f28d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edabf4 VA: 0x75944f2bf4
	public Void .ctor() { }
}
```