# CheckTargetRootTile

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _hasCharacter`

- `Boolean _hasCertainEnemy`

- `Boolean _checkTileKey`


## Properties

- `Boolean hasCertainEnemy`

- `Boolean checkTileKey`


## Methods

- `Boolean get_hasCertainEnemy()`

- `Boolean get_checkTileKey()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTargetRootTile : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _hasCharacter; // 0x14
	private List`1 _characterKeys; // 0x18
	private Boolean _hasCertainEnemy; // 0x20
	private List`1 _enemyKeys; // 0x28
	private Boolean _checkTileKey; // 0x30
	private List`1 _tileKeys; // 0x38
	private static DelegateBridge __Hotfix0_get_hasCertainEnemy; // 0x0
	private static DelegateBridge __Hotfix0_get_checkTileKey; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean hasCertainEnemy { get; }
	public Boolean checkTileKey { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f2cce0 VA: 0x7594544ce0
	public Boolean get_hasCertainEnemy() { }
	// RVA: 0x1f2cd48 VA: 0x7594544d48
	public Boolean get_checkTileKey() { }
	// RVA: 0x1f2cdb0 VA: 0x7594544db0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f2ce18 VA: 0x7594544e18
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f2d3b0 VA: 0x75945453b0
	public Void .ctor() { }
}
```