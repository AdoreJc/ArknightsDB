# RewriteTileOptions

**Namespace:** ` `


## Fields

- `Boolean _keepCurrentAdvancedBuildableMask`

- `AdvancedBuildableMask _advancedBuildableMask`

- `Boolean _keepCurrentPassableMask`

- `MotionMask _passableMask`

- `Boolean _keepCurrentBuildableType`

- `BuildableType _buildableType`

- `Boolean _keepCurrentObstacleLike`

- `Boolean _isObstacleLike`

- `Boolean _restoreTileOptions`

- `Boolean _killLocatedIfNotBuildable`

- `Boolean _useOwnerRootTile`


## Properties

- `Boolean modifyAdvancedBuildableMask`

- `Boolean modifyPassableMask`

- `Boolean modifyBuildableType`

- `Boolean modifyObstacleLike`


## Methods

- `Boolean get_modifyAdvancedBuildableMask()`

- `Boolean get_modifyPassableMask()`

- `Boolean get_modifyBuildableType()`

- `Boolean get_modifyObstacleLike()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RewriteTileOptions : ActionNode
{
	private Boolean _keepCurrentAdvancedBuildableMask; // 0x10
	private AdvancedBuildableMask _advancedBuildableMask; // 0x14
	private Boolean _keepCurrentPassableMask; // 0x18
	private MotionMask _passableMask; // 0x1c
	private Boolean _keepCurrentBuildableType; // 0x20
	private BuildableType _buildableType; // 0x24
	private Boolean _keepCurrentObstacleLike; // 0x28
	private Boolean _isObstacleLike; // 0x29
	private Boolean _restoreTileOptions; // 0x2a
	private Boolean _killLocatedIfNotBuildable; // 0x2b
	private Boolean _useOwnerRootTile; // 0x2c
	private static DelegateBridge __Hotfix0_get_modifyAdvancedBuildableMask; // 0x0
	private static DelegateBridge __Hotfix0_get_modifyPassableMask; // 0x8
	private static DelegateBridge __Hotfix0_get_modifyBuildableType; // 0x10
	private static DelegateBridge __Hotfix0_get_modifyObstacleLike; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x20
	private static DelegateBridge __Hotfix0_Execute; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean modifyAdvancedBuildableMask { get; }
	public Boolean modifyPassableMask { get; }
	public Boolean modifyBuildableType { get; }
	public Boolean modifyObstacleLike { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fe4a94 VA: 0x75945fca94
	public Boolean get_modifyAdvancedBuildableMask() { }
	// RVA: 0x1fe4b04 VA: 0x75945fcb04
	public Boolean get_modifyPassableMask() { }
	// RVA: 0x1fe4b74 VA: 0x75945fcb74
	public Boolean get_modifyBuildableType() { }
	// RVA: 0x1fe4be4 VA: 0x75945fcbe4
	public Boolean get_modifyObstacleLike() { }
	// RVA: 0x1fe4c54 VA: 0x75945fcc54
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe4cbc VA: 0x75945fccbc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe4f20 VA: 0x75945fcf20
	public Void .ctor() { }
}
```