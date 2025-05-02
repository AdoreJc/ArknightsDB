# CheckTileTypeCntInAttackRange

**Namespace:** ` `


## Fields

- `HeightType _targetTileType`

- `CompareType _condType`

- `ActionTargetType m_sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTileTypeCntInAttackRange : ActionNode
{
	private HeightType _targetTileType; // 0x10
	private CompareType _condType; // 0x14
	private ActionTargetType m_sourceType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f269bc VA: 0x759453e9bc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f26a24 VA: 0x759453ea24
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f26d64 VA: 0x759453ed64
	public Void .ctor() { }
}
```