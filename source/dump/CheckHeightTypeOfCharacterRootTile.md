# CheckHeightTypeOfCharacterRootTile

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `HeightType _heightType`

- `Boolean _isUnset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckHeightTypeOfCharacterRootTile : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private HeightType _heightType; // 0x14
	private Boolean _isUnset; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f26de8 VA: 0x759453ede8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f26e50 VA: 0x759453ee50
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f26fec VA: 0x759453efec
	public Void .ctor() { }
}
```