# RewriteDynamicBuffTileOptionsInRangeWhenSpecialMode

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _rangeId`

- `Boolean _exclude`

- `Boolean _keepCurrentAdvancedBuildableMask`

- `AdvancedBuildableMask _advancedBuildableMask`

- `Boolean _keepCurrentBuildableType`

- `BuildableType _buildableType`

- `Boolean _keepCurrentPassableMask`

- `MotionMask _passableMask`

- `Boolean _keepCurrentObstacleLike`

- `Boolean _isObstacleLike`

- `Boolean _killLocatedIfNotBuildable`


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
public class RewriteDynamicBuffTileOptionsInRangeWhenSpecialMode : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _rangeId; // 0x18
	private Int32[] _modes; // 0x20
	private Boolean _exclude; // 0x28
	private Boolean _keepCurrentAdvancedBuildableMask; // 0x29
	private AdvancedBuildableMask _advancedBuildableMask; // 0x2c
	private Boolean _keepCurrentBuildableType; // 0x30
	private BuildableType _buildableType; // 0x34
	private Boolean _keepCurrentPassableMask; // 0x38
	private MotionMask _passableMask; // 0x3c
	private Boolean _keepCurrentObstacleLike; // 0x40
	private Boolean _isObstacleLike; // 0x41
	private Boolean _killLocatedIfNotBuildable; // 0x42
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

	// RVA: 0x1fe539c VA: 0x75945fd39c
	public Boolean get_modifyAdvancedBuildableMask() { }
	// RVA: 0x1fe540c VA: 0x75945fd40c
	public Boolean get_modifyPassableMask() { }
	// RVA: 0x1fe547c VA: 0x75945fd47c
	public Boolean get_modifyBuildableType() { }
	// RVA: 0x1fe54ec VA: 0x75945fd4ec
	public Boolean get_modifyObstacleLike() { }
	// RVA: 0x1fe555c VA: 0x75945fd55c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe55c4 VA: 0x75945fd5c4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe5a58 VA: 0x75945fda58
	public Void .ctor() { }
}
```