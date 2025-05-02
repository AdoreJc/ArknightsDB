# BlockedToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _blockMinCnt`

- `Int32 _blockMaxCnt`

- `Boolean _useBlockAsMin`

- `Int32 m_blockMaxCnt`

- `Int32 m_blockMinCnt`

- `Unit m_unit`


## Properties

- `Boolean hasBlockeeBuff`


## Methods

- `Boolean get_hasBlockeeBuff()`

- `Boolean _CheckCondition(Unit)`

- `Void _OnRallyPointBlockeeChanged(Object)`

- `Void _OnBlockeeChanged(Object)`

- `Void _UpdateBlockeeBuffs()`

- `Void _UpdateCharacterBlockeeBuffs()`

- `Void _UpdateEnemyBlockeeBuffs()`

- `Void _ClearBlockeeBuffs()`

- `Void GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BlockedToggleChecker : Checker, IBuffSource
{
	private Int32 _blockMinCnt; // 0x20
	private Int32 _blockMaxCnt; // 0x24
	private Boolean _useBlockAsMin; // 0x28
	private BuffData[] _buffsToBlockee; // 0x30
	private Int32 m_blockMaxCnt; // 0x38
	private Int32 m_blockMinCnt; // 0x3c
	private ListDict`2 m_blockeeBuffList; // 0x40
	private Unit m_unit; // 0x48
	private static DelegateBridge __Hotfix0_get_hasBlockeeBuff; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0_OnAttached; // 0x18
	private static DelegateBridge __Hotfix0_OnDetached; // 0x20
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x28
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x30
	private static DelegateBridge __Hotfix0__OnRallyPointBlockeeChanged; // 0x38
	private static DelegateBridge __Hotfix0__OnBlockeeChanged; // 0x40
	private static DelegateBridge __Hotfix0__UpdateBlockeeBuffs; // 0x48
	private static DelegateBridge __Hotfix0__UpdateCharacterBlockeeBuffs; // 0x50
	private static DelegateBridge __Hotfix0__UpdateEnemyBlockeeBuffs; // 0x58
	private static DelegateBridge __Hotfix0__ClearBlockeeBuffs; // 0x60
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	private Boolean hasBlockeeBuff { get; }

	// RVA: 0x1e59f88 VA: 0x7594471f88
	private Boolean get_hasBlockeeBuff() { }
	// RVA: 0x1e5a014 VA: 0x7594472014
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5a0e4 VA: 0x75944720e4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5a370 VA: 0x7594472370
	public override Void OnAttached() { }
	// RVA: 0x1e5a6ac VA: 0x75944726ac
	public override Void OnDetached() { }
	// RVA: 0x1e5a9f4 VA: 0x75944729f4
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5a17c VA: 0x759447217c
	private Boolean _CheckCondition(Unit unit) { }
	// RVA: 0x1e5aa60 VA: 0x7594472a60
	private Void _OnRallyPointBlockeeChanged(Object arg) { }
	// RVA: 0x1e5ac34 VA: 0x7594472c34
	private Void _OnBlockeeChanged(Object arg) { }
	// RVA: 0x1e5a5a8 VA: 0x75944725a8
	private Void _UpdateBlockeeBuffs() { }
	// RVA: 0x1e5acb0 VA: 0x7594472cb0
	private Void _UpdateCharacterBlockeeBuffs() { }
	// RVA: 0x1e5b244 VA: 0x7594473244
	private Void _UpdateEnemyBlockeeBuffs() { }
	// RVA: 0x1e5a844 VA: 0x7594472844
	private Void _ClearBlockeeBuffs() { }
	// RVA: 0x1e5b768 VA: 0x7594473768
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e5b808 VA: 0x7594473808
	public Void .ctor() { }
	// RVA: 0x1e5b8c0 VA: 0x75944738c0
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1e5b8c4 VA: 0x75944738c4
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e5b8c8 VA: 0x75944738c8
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```