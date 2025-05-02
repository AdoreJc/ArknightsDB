# Main15InsertPrtsAction

**Namespace:** ` `


## Fields

- `PrtsActionType _actionType`

- `Int32 _priority`

- `ActionTargetType _sourceType`

- `BuffData _buffData`

- `Boolean _chooseMostCharSurroud`

- `Boolean _chooseMostEnemySurroud`

- `Boolean _chooseSource`

- `String _enemyKeyFly`

- `String _enemyKeyHL`

- `String _enemyKeyLL`


## Properties

- `Boolean needSource`

- `Boolean needCreateBuff`

- `Boolean isMoveDragSource`

- `Boolean isMoveCreateBuff`

- `Boolean isMoveSpawnEnemy`


## Methods

- `Boolean get_needSource()`

- `Boolean get_needCreateBuff()`

- `Boolean get_isMoveDragSource()`

- `Boolean get_isMoveCreateBuff()`

- `Boolean get_isMoveSpawnEnemy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Main15InsertPrtsAction : ActionNode
{
	private PrtsActionType _actionType; // 0x10
	private Int32 _priority; // 0x14
	private ActionTargetType _sourceType; // 0x18
	private BuffData _buffData; // 0x20
	private Boolean _chooseMostCharSurroud; // 0x28
	private Boolean _chooseMostEnemySurroud; // 0x29
	private Boolean _chooseSource; // 0x2a
	private String _enemyKeyFly; // 0x30
	private String _enemyKeyHL; // 0x38
	private String _enemyKeyLL; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_needSource; // 0x8
	private static DelegateBridge __Hotfix0_get_needCreateBuff; // 0x10
	private static DelegateBridge __Hotfix0_get_isMoveDragSource; // 0x18
	private static DelegateBridge __Hotfix0_get_isMoveCreateBuff; // 0x20
	private static DelegateBridge __Hotfix0_get_isMoveSpawnEnemy; // 0x28
	private static DelegateBridge __Hotfix0_Execute; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override SourceType allowedSource { get; }
	protected Boolean needSource { get; }
	protected Boolean needCreateBuff { get; }
	protected Boolean isMoveDragSource { get; }
	protected Boolean isMoveCreateBuff { get; }
	protected Boolean isMoveSpawnEnemy { get; }

	// RVA: 0x1f6faf4 VA: 0x7594587af4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6fb5c VA: 0x7594587b5c
	protected Boolean get_needSource() { }
	// RVA: 0x1f6fcc0 VA: 0x7594587cc0
	protected Boolean get_needCreateBuff() { }
	// RVA: 0x1f6fbe0 VA: 0x7594587be0
	protected Boolean get_isMoveDragSource() { }
	// RVA: 0x1f6fc50 VA: 0x7594587c50
	protected Boolean get_isMoveCreateBuff() { }
	// RVA: 0x1f6fd44 VA: 0x7594587d44
	protected Boolean get_isMoveSpawnEnemy() { }
	// RVA: 0x1f6fdb4 VA: 0x7594587db4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f701f8 VA: 0x75945881f8
	public Void .ctor() { }
}
```