# LMultiEnemyKeyReplace

**Namespace:** ` `


## Methods

- `Void _ProcessEnemyReplace(LevelData, SandboxV2Data, Dictionary`2)`

- `EnemyDataDbReference _GetEnemyDataDbReference(SandboxV2Data, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LMultiEnemyKeyReplace : BasicLevelRune
{
	private const Single MIN_VIEW_RADIUS; // 0x0
	private HashSet`1 m_replacedEnemyKeys; // 0x20

	public override RuneTarget targetMask { get; }

	// RVA: 0x1df33c4 VA: 0x759440b3c4
	protected Void .ctor() { }
	// RVA: 0x1df344c VA: 0x759440b44c
	public override RuneTarget get_targetMask() { }
	// RVA: 0x1df3454 VA: 0x759440b454
	public override Void PreprocessLevelData(LevelData levelData, MapData mapData, ref RuneLevelExtraOutput extraData) { }
	// RVA: 0x1df35a0 VA: 0x759440b5a0
	private Void _ProcessEnemyReplace(LevelData levelData, SandboxV2Data configData, Dictionary`2 replaceKeys) { }
	// RVA: 0x1df39d8 VA: 0x759440b9d8
	private EnemyDataDbReference _GetEnemyDataDbReference(SandboxV2Data configData, String enemyId) { }
	// RVA: 0x1df3d38 VA: 0x759440bd38
	public override Void PreprocessLevelOptions(Options options) { }
}
```