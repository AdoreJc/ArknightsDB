# LevelData

**Namespace:** `Torappu`


## Fields

- `Options options`

- `String levelId`

- `String mapId`

- `String bgmEvent`

- `String environmentSe`

- `MapData mapData`

- `PredefinedData predefines`

- `PredefinedData hardPredefines`

- `Int32 randomSeed`

- `String operaConfig`

- `String cameraPlugin`

- `RuntimeData runtimeData`


## Methods

- `String GetSceneName()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class LevelData
{
	public Options options; // 0x10
	public String levelId; // 0x18
	public String mapId; // 0x20
	public String bgmEvent; // 0x28
	public String environmentSe; // 0x30
	public MapData mapData; // 0x38
	public List`1 tilesDisallowToLocate; // 0x40
	public LegacyInLevelRuneData[] runes; // 0x48
	public Dictionary`2 optionalRunes; // 0x50
	public GlobalBuffData[] globalBuffs; // 0x58
	public RouteData[] routes; // 0x60
	public RouteData[] extraRoutes; // 0x68
	public EnemyData[] enemies; // 0x70
	public EnemyDataDbReference[] enemyDbRefs; // 0x78
	public WaveData[] waves; // 0x80
	public ListDict`2 branches; // 0x88
	public PredefinedData predefines; // 0x90
	public PredefinedData hardPredefines; // 0x98
	public String[] excludeCharIdList; // 0xa0
	public Int32 randomSeed; // 0xa8
	public String operaConfig; // 0xb0
	public String cameraPlugin; // 0xb8
	public RuntimeData runtimeData; // 0xc0


	// RVA: 0x34a3e34 VA: 0x7595abbe34
	public String GetSceneName() { }
	// RVA: 0x34a3e64 VA: 0x7595abbe64
	public Void .ctor() { }
}
```