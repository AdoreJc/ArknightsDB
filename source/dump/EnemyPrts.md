# EnemyPrts

**Namespace:** ` `


## Fields

- `Enemy enemy`

- `Enemy m_prtsDragging`

- `GridPosition m_tracePosition`


## Methods

- `Boolean TracePosition(GridPosition, Vector2)`

- `Void EnableDraggingEnemy(String)`

- `HighlandEnemyTrapPair GetHighlandEnemyTrapInfo(String, HeightType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyPrts : IHotfixable
{
	public Enemy enemy; // 0x10
	private Dictionary`2 m_draggingedEnemy; // 0x18
	private Enemy m_prtsDragging; // 0x20
	private GridPosition m_tracePosition; // 0x28
	private HighlandEnemyTrapPair[] m_enemyTrapKeyPairs; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_TracePosition; // 0x8
	private static DelegateBridge __Hotfix0_EnableDraggingEnemy; // 0x10
	private static DelegateBridge __Hotfix0_GetHighlandEnemyTrapInfo; // 0x18


	// RVA: 0x4057f78 VA: 0x759666ff78
	public Void .ctor(Enemy enemy, HighlandEnemyTrapPair[] enemyTrapKeyPairs) { }
	// RVA: 0x4055d20 VA: 0x759666dd20
	public Boolean TracePosition(GridPosition targetPos, Vector2 offset) { }
	// RVA: 0x4058e00 VA: 0x7596670e00
	public Void EnableDraggingEnemy(String enemyKey) { }
	// RVA: 0x40592ac VA: 0x75966712ac
	public HighlandEnemyTrapPair GetHighlandEnemyTrapInfo(String enemyKey, HeightType heightType) { }
}
```