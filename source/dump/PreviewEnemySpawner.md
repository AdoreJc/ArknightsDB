# PreviewEnemySpawner

**Namespace:** ` `


## Fields

- `Boolean m_inited`


## Methods

- `Void Spawn(LevelData, List`1)`

- `Void Reset()`

- `Void _InitIfNot()`

- `GridPosition _GetBetterGridToSpawn(GridPosition, Int32)`

- `IEnumerator _SpawnPreviewEnemies(LevelData, List`1)`

- `Boolean _IsNeedPreviewAction(List`1, ActionData)`

- `Int32 _CompareActionByTime(ActionData, ActionData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PreviewEnemySpawner : IHotfixable
{
	public const Int32 MAX_PREVIEW_CNT; // 0x0
	private ListDict`2 m_betterGridToSpawn; // 0x10
	private List`1 m_backUpTiles; // 0x18
	private ListDict`2 m_gridSpawnStatus; // 0x20
	private List`1 m_enemyData; // 0x28
	private List`1 m_spawnedEnemy; // 0x30
	private Boolean m_inited; // 0x38
	private static DelegateBridge __Hotfix0_Spawn; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__GetBetterGridToSpawn; // 0x18
	private static DelegateBridge __Hotfix0__SpawnPreviewEnemies; // 0x20
	private static DelegateBridge __Hotfix0__IsNeedPreviewAction; // 0x28
	private static DelegateBridge __Hotfix0__CompareActionByTime; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1cada88 VA: 0x75942c5a88
	public Void Spawn(LevelData levelData, List`1 extraEnabledGroup) { }
	// RVA: 0x1cadeac VA: 0x75942c5eac
	public Void Reset() { }
	// RVA: 0x1cb4068 VA: 0x75942cc068
	private Void _InitIfNot() { }
	// RVA: 0x1cb4d04 VA: 0x75942ccd04
	private GridPosition _GetBetterGridToSpawn(GridPosition pos, Int32 total) { }
	// RVA: 0x1cb4c14 VA: 0x75942ccc14
	private IEnumerator _SpawnPreviewEnemies(LevelData levelData, List`1 extraEnabledLevelGroup) { }
	// RVA: 0x1cb5474 VA: 0x75942cd474
	private Boolean _IsNeedPreviewAction(List`1 extraEnabledLevelGroup, ActionData action) { }
	// RVA: 0x1cb5580 VA: 0x75942cd580
	private Int32 _CompareActionByTime(ActionData dataL, ActionData dataR) { }
	// RVA: 0x1cae184 VA: 0x75942c6184
	public Void .ctor() { }
}
```