# RewriteDynamicBuffTileOptionsOneLine

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Direction _direction`

- `Boolean _useCurrentTileDirection`

- `Boolean _useLocationFromBBAsCurrentTile`

- `String _buffKey`

- `Boolean _keepCurrentObstacleLike`

- `Boolean _isObstacleLike`

- `Boolean _exceptCurrentTile`


## Properties

- `Boolean modifyObstacleLike`


## Methods

- `Boolean get_modifyObstacleLike()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RewriteDynamicBuffTileOptionsOneLine : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Direction _direction; // 0x14
	private Boolean _useCurrentTileDirection; // 0x18
	private Boolean _useLocationFromBBAsCurrentTile; // 0x19
	private String _buffKey; // 0x20
	private Boolean _keepCurrentObstacleLike; // 0x28
	private Boolean _isObstacleLike; // 0x29
	private Boolean _exceptCurrentTile; // 0x2a
	private static DelegateBridge __Hotfix0_get_modifyObstacleLike; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean modifyObstacleLike { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fe5b18 VA: 0x75945fdb18
	public Boolean get_modifyObstacleLike() { }
	// RVA: 0x1fe5b88 VA: 0x75945fdb88
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe5bf0 VA: 0x75945fdbf0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe60ec VA: 0x75945fe0ec
	public Void .ctor() { }
}
```