# AdvancedSelectorWithEnemyOptions

**Namespace:** `Torappu.Battle`


## Fields

- `EnemyLevelMask _enemyLevelMask`

- `MotionMask _motionMask`

- `Boolean _allowNoneApplyWay`

- `SourceApplyWay _applyWay`

- `Boolean _filterByEnemiesKey`

- `Boolean _filterByEnemiesMode`

- `Boolean _filterByEnemiesTag`

- `Int32 _enemyMode`

- `String _enemyTag`

- `Boolean _excludeDisappeared`

- `Boolean _excludeInCombat`

- `Boolean _filterBuff`

- `Boolean _buffKeyExcluded`

- `String _buffKey`

- `String m_enemyKey`


## Methods

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithEnemyOptions : AdvancedSelector
{
	private EnemyLevelMask _enemyLevelMask; // 0xe8
	private MotionMask _motionMask; // 0xec
	private Boolean _allowNoneApplyWay; // 0xf0
	private SourceApplyWay _applyWay; // 0xf4
	private Boolean _filterByEnemiesKey; // 0xf8
	private Boolean _filterByEnemiesMode; // 0xf9
	private Boolean _filterByEnemiesTag; // 0xfa
	private Int32 _enemyMode; // 0xfc
	private String _enemyTag; // 0x100
	private Boolean _excludeDisappeared; // 0x108
	private Boolean _excludeInCombat; // 0x109
	private Boolean _filterBuff; // 0x10a
	private Boolean _buffKeyExcluded; // 0x10b
	private String _buffKey; // 0x110
	private String m_enemyKey; // 0x118
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b9ad4c VA: 0x75941b2d4c
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1b9ae30 VA: 0x75941b2e30
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b9b1d4 VA: 0x75941b31d4
	public Void .ctor() { }
	// RVA: 0x1b9b25c VA: 0x75941b325c
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1b9b260 VA: 0x75941b3260
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```