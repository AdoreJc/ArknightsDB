# RacingEnemyFilterByRanking

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Int32 _ranking`

- `Boolean _isReverseRanking`

- `CompareType _compareType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RacingEnemyFilterByRanking : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Int32 _ranking; // 0x14
	private Boolean _isReverseRanking; // 0x18
	private CompareType _compareType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7a800 VA: 0x7594592800
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7a868 VA: 0x7594592868
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7aa94 VA: 0x7594592a94
	public Void .ctor() { }
}
```