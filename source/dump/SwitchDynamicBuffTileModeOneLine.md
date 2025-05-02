# SwitchDynamicBuffTileModeOneLine

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Direction _direction`

- `Boolean _useCurrentTileDirection`

- `Boolean _useLocationFromBBAsCurrentTile`

- `Boolean _updateDirectionBeforeApply`

- `String _buffKey`

- `Int32 _modeIndex`

- `Boolean _exceptCurrentTile`

- `Boolean _switchOneTileEachTime`

- `String _tileIndexKey`

- `Int32 _modeIndexDeltaWhenFinalTile`

- `Boolean _dontSwitchModeOnlyAssignTileCntToAbilityBb`

- `String _abilityName`

- `String _blackboardKey`


## Methods

- `Int32 _GetLineTileCnt(List`1, Int32)`

- `DirectionTile _GetTile(Entity, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchDynamicBuffTileModeOneLine : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Direction _direction; // 0x14
	private Boolean _useCurrentTileDirection; // 0x18
	private Boolean _useLocationFromBBAsCurrentTile; // 0x19
	private Boolean _updateDirectionBeforeApply; // 0x1a
	private String _buffKey; // 0x20
	private Int32 _modeIndex; // 0x28
	private Boolean _exceptCurrentTile; // 0x2c
	private Boolean _switchOneTileEachTime; // 0x2d
	private String _tileIndexKey; // 0x30
	private Int32 _modeIndexDeltaWhenFinalTile; // 0x38
	private Boolean _dontSwitchModeOnlyAssignTileCntToAbilityBb; // 0x3c
	private String _abilityName; // 0x40
	private String _blackboardKey; // 0x48
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__GetLineTileCnt; // 0x10
	private static DelegateBridge __Hotfix0__GetTile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe2d30 VA: 0x75945fad30
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe2d98 VA: 0x75945fad98
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe34c8 VA: 0x75945fb4c8
	private Int32 _GetLineTileCnt(List`1 tileList, Int32 index) { }
	// RVA: 0x1fe3268 VA: 0x75945fb268
	private DirectionTile _GetTile(Entity source, ref GridPosition startPos) { }
	// RVA: 0x1fe364c VA: 0x75945fb64c
	public Void .ctor() { }
}
```