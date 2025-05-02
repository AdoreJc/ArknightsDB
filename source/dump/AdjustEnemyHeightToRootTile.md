# AdjustEnemyHeightToRootTile

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _instant`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AdjustEnemyHeightToRootTile : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _instant; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd49f4 VA: 0x75945ec9f4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd4a5c VA: 0x75945eca5c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd4c10 VA: 0x75945ecc10
	public Void .ctor() { }
}
```