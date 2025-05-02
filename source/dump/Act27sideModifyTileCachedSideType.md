# Act27sideModifyTileCachedSideType

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _useRangeId`

- `Boolean _useTileInSnapShot`

- `MechanismSideType _sideType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act27sideModifyTileCachedSideType : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _useRangeId; // 0x14
	private Boolean _useTileInSnapShot; // 0x15
	private MechanismSideType _sideType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eda3f0 VA: 0x75944f23f0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eda458 VA: 0x75944f2458
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eda7f0 VA: 0x75944f27f0
	public Void .ctor() { }
}
```