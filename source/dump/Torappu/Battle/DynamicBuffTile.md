# DynamicBuffTile

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _modeIndex`

- `Boolean _dontClearEffectOnCharacterEnter`

- `Boolean _applyToEnemyWhenSwitchMode`

- `Boolean _updateEffectOnCharacterLeave`

- `Int32 m_cachedOriginMode`


## Methods

- `Boolean SwitchMode(Func`2)`

- `Void ResetMode()`

- `Void _ClearEffects()`

- `Void _ApplyDynamicBuffs(Entity, List`1)`

- `Int32 <ResetMode>b__21_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DynamicBuffTile : BuffTile
{
	protected Int32 _modeIndex; // 0x198
	private TileBuffsAndEffectsPair[] _dynamicBuffs; // 0x1a0
	private Boolean _dontClearEffectOnCharacterEnter; // 0x1a8
	protected Boolean _applyToEnemyWhenSwitchMode; // 0x1a9
	private Boolean _updateEffectOnCharacterLeave; // 0x1aa
	protected readonly List`1 m_charDynamicBuffUids; // 0x1b0
	protected Dictionary`2 m_enemyDynamicBuffUids; // 0x1b8
	private Int32 m_cachedOriginMode; // 0x1c0
	protected readonly List`1 m_currentTileEffects; // 0x1c8

	public virtual Int32 modeIndex { get; }
	protected override Boolean traceBuffUids { get; }
	private BuffData[] dynamicBuffs { get; }
	private String[] dynamicBuffEffects { get; }

	// RVA: 0x408d000 VA: 0x75966a5000
	public virtual Int32 get_modeIndex() { }
	// RVA: 0x408d008 VA: 0x75966a5008
	protected override Boolean get_traceBuffUids() { }
	// RVA: 0x408d010 VA: 0x75966a5010
	private BuffData[] get_dynamicBuffs() { }
	// RVA: 0x408d098 VA: 0x75966a5098
	private String[] get_dynamicBuffEffects() { }
	// RVA: 0x408b97c VA: 0x75966a397c
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x408d120 VA: 0x75966a5120
	public Boolean SwitchMode(Func`2 modifyIndexFunc) { }
	// RVA: 0x408d164 VA: 0x75966a5164
	public virtual Boolean SwitchMode(Int32 modeIndex) { }
	// RVA: 0x4086e70 VA: 0x759669ee70
	public Void ResetMode() { }
	// RVA: 0x408cbd4 VA: 0x75966a4bd4
	protected virtual Void OnSwitchMode(Int32 mode) { }
	// RVA: 0x408d688 VA: 0x75966a5688
	protected virtual Void _UpdateEffects() { }
	// RVA: 0x408da58 VA: 0x75966a5a58
	private Void _ClearEffects() { }
	// RVA: 0x408d5c4 VA: 0x75966a55c4
	protected Void _ApplyDynamicBuffs(Entity target, List`1 buffUids) { }
	// RVA: 0x408db4c VA: 0x75966a5b4c
	protected override Void OnCharacterEnter(Character newChar, Character oldChar) { }
	// RVA: 0x408dbc0 VA: 0x75966a5bc0
	protected override Void OnCharacterLeave(Character character) { }
	// RVA: 0x408dc20 VA: 0x75966a5c20
	public override Void OnRallyPointLikeReborn(Unit unit) { }
	// RVA: 0x408dc80 VA: 0x75966a5c80
	public override Void OnRallyPointLikeFakeDeath(Unit unit) { }
	// RVA: 0x408dd58 VA: 0x75966a5d58
	protected override Void OnEnemyEnter(Enemy enemy) { }
	// RVA: 0x408ddb8 VA: 0x75966a5db8
	protected override Void OnEnemyLeave(Enemy enemy) { }
	// RVA: 0x408de0c VA: 0x75966a5e0c
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x408deb8 VA: 0x75966a5eb8
	protected override Void PreloadBuffAssets() { }
	// RVA: 0x408df60 VA: 0x75966a5f60
	public Void .ctor() { }
	// RVA: 0x408e098 VA: 0x75966a6098
	private Int32 <ResetMode>b__21_0(Int32 mode) { }
}
```