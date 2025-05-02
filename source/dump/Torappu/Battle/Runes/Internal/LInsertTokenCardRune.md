# LInsertTokenCardRune

**Namespace:** `Torappu.Battle.Runes.Internal`


## Methods

- `Boolean _TryAddCntIfAlreadyExist(BattlePlayerData, Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Runes.Internal
public class LInsertTokenCardRune : BasicLevelRune
{

	public override RuneTarget targetMask { get; }

	// RVA: 0x1d3f684 VA: 0x7594357684
	public override RuneTarget get_targetMask() { }
	// RVA: 0x1d3f68c VA: 0x759435768c
	protected Void .ctor() { }
	// RVA: 0x1d3f694 VA: 0x7594357694
	public override Void PreprocessBattlePlayerData(BattlePlayerData playerData) { }
	// RVA: 0x1d3f81c VA: 0x759435781c
	private Boolean _TryAddCntIfAlreadyExist(BattlePlayerData playerData, Blackboard blackboard) { }
	// RVA: 0x1d3f93c VA: 0x759435793c
	public override Void PreprocessLevelData(LevelData levelData, MapData mapData, ref RuneLevelExtraOutput extraData) { }
	// RVA: 0x1d3f940 VA: 0x7594357940
	public override Void PreprocessLevelOptions(Options options) { }
}
```