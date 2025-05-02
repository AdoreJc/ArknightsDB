# SpawnTokenInCharacterRangeById

**Namespace:** ` `


## Fields

- `ActionTargetType _hostType`

- `ActionTargetType _targetType`

- `String _tokenId`

- `Int32 _maxTileCnt`

- `SideType _targetSide`

- `MotionMask _targetMotion`

- `EntityCategory _targetCategory`

- `Boolean _checkTokenMaxDeployCnt`

- `Card m_tokenCard`

- `TargetOptions m_targetOptions`

- `Tile m_targetTile`


## Methods

- `Void _ClearLocalVariables()`

- `Boolean _ValidateTile(Tile)`

- `Void _OnPostFilter(List`1, Character)`

- `Boolean _CheckEnemies(DoubleBufferedList`1)`

- `Boolean _CheckHatredEnemyOnTile(Tile, out)`

- `Boolean _CheckNearestToTargetTile(Tile, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SpawnTokenInCharacterRangeById : ActionNode
{
	private ActionTargetType _hostType; // 0x10
	private ActionTargetType _targetType; // 0x14
	private String _tokenId; // 0x18
	private Int32 _maxTileCnt; // 0x20
	private SideType _targetSide; // 0x24
	private MotionMask _targetMotion; // 0x28
	private EntityCategory _targetCategory; // 0x2c
	private Boolean _checkTokenMaxDeployCnt; // 0x30
	private Card m_tokenCard; // 0x38
	private TargetOptions m_targetOptions; // 0x40
	private Tile m_targetTile; // 0xa0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__ClearLocalVariables; // 0x10
	private static DelegateBridge __Hotfix0__ValidateTile; // 0x18
	private static DelegateBridge __Hotfix0__OnPostFilter; // 0x20
	private static DelegateBridge __Hotfix0__CheckEnemies; // 0x28
	private static DelegateBridge __Hotfix0__CheckHatredEnemyOnTile; // 0x30
	private static DelegateBridge __Hotfix0__CheckNearestToTargetTile; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public override SourceType allowedSource { get; }

	// RVA: 0x1fcb6b4 VA: 0x75945e36b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fcb71c VA: 0x75945e371c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fcbd00 VA: 0x75945e3d00
	private Void _ClearLocalVariables() { }
	// RVA: 0x1fcc090 VA: 0x75945e4090
	private Boolean _ValidateTile(Tile tile) { }
	// RVA: 0x1fcbd90 VA: 0x75945e3d90
	private Void _OnPostFilter(List`1 candidates, Character target) { }
	// RVA: 0x1fcc130 VA: 0x75945e4130
	private Boolean _CheckEnemies(DoubleBufferedList`1 enemies) { }
	// RVA: 0x1fcc49c VA: 0x75945e449c
	private Boolean _CheckHatredEnemyOnTile(Tile tile, out FP weight) { }
	// RVA: 0x1fcc90c VA: 0x75945e490c
	private Boolean _CheckNearestToTargetTile(Tile tile, out FP weight) { }
	// RVA: 0x1fcca88 VA: 0x75945e4a88
	public Void .ctor() { }
}
```