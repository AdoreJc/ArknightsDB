# LegionModeAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `LegionModeSettings m_gameSettings`

- `LegionGameMode m_gameMode`

- `Blackboard m_rawMultiBlackboard`


## Properties

- `LegionModeSettings gameSettings`

- `LegionGameMode gameMode`


## Methods

- `LegionModeSettings get_gameSettings()`

- `LegionGameMode get_gameMode()`

- `Void _RefreshBlackBoardWithRawMulti()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class LegionModeAbility : EmptyAbility
{
	private List`1 _buffPairs; // 0x108
	private List`1 m_usedBuffPairs; // 0x110
	private LegionModeSettings m_gameSettings; // 0x118
	private LegionGameMode m_gameMode; // 0x120
	private static String RAW_MULTI_ATTRIBUTE_SUFFIX; // 0x0
	private Blackboard m_rawMultiBlackboard; // 0x128
	private static DelegateBridge __Hotfix0_get_buffPairs; // 0x8
	private static DelegateBridge __Hotfix0_get_gameSettings; // 0x10
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x18
	private static DelegateBridge __Hotfix0_UpdateBlackboard; // 0x20
	private static DelegateBridge __Hotfix0_RefreshLegionBuff; // 0x28
	private static DelegateBridge __Hotfix0__RefreshBlackBoardWithRawMulti; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public List`1 buffPairs { get; }
	protected LegionModeSettings gameSettings { get; }
	protected LegionGameMode gameMode { get; }

	// RVA: 0x1e77040 VA: 0x759448f040
	public List`1 get_buffPairs() { }
	// RVA: 0x1e77324 VA: 0x759448f324
	protected LegionModeSettings get_gameSettings() { }
	// RVA: 0x1e773d4 VA: 0x759448f3d4
	protected LegionGameMode get_gameMode() { }
	// RVA: 0x1e77514 VA: 0x759448f514
	protected virtual Void UpdateBlackboard() { }
	// RVA: 0x1e77b94 VA: 0x759448fb94
	public virtual Void RefreshLegionBuff() { }
	// RVA: 0x1e7758c VA: 0x759448f58c
	private Void _RefreshBlackBoardWithRawMulti() { }
	// RVA: 0x1e77c40 VA: 0x759448fc40
	public Void .ctor() { }
	// RVA: 0x1e77d50 VA: 0x759448fd50
	private static Void .cctor() { }
}
```