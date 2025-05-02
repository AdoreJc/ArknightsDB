# CheckHeightTypeInRange

**Namespace:** ` `


## Fields

- `ActionTargetType m_sourceType`

- `HeightType _targetTileType`

- `String _rangeId`

- `Int32 _checkCnt`

- `CompareType _condType`


## Methods

- `Boolean <Execute>b__7_0(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckHeightTypeInRange : ActionNode
{
	private ActionTargetType m_sourceType; // 0x10
	private HeightType _targetTileType; // 0x14
	private String _rangeId; // 0x18
	private Int32 _checkCnt; // 0x20
	private CompareType _condType; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f27b90 VA: 0x759453fb90
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f27bf8 VA: 0x759453fbf8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f27ef0 VA: 0x759453fef0
	public Void .ctor() { }
	// RVA: 0x1f27fb0 VA: 0x759453ffb0
	private Boolean <Execute>b__7_0(Tile tile) { }
}
```