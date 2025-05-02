# BattleAttackRangeController

**Namespace:** `Torappu.Battle`


## Methods

- `Void BindOwner(IRangeListener, Character)`

- `Void AddRangeListener(IRangeListener)`

- `Void RemoveRangeListener(IRangeListener)`

- `Void RemoveRangeListener(Character)`

- `Void _Init()`

- `Void _OnUnitBorn(Object)`

- `Void _OnUnitReborn(Object)`

- `Void _OnUnitFinish(Object)`

- `Void _OnUnitAttackRangeUpdated(Object)`

- `Boolean _ValidCharacter(Character)`

- `Boolean _RefreshCharacterRangeTiles(Character)`

- `Void _OnCharacterAttackRangeUpdate(Character)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleAttackRangeController : IHotfixable
{
	private Dictionary`2 m_attackRangeTiles; // 0x10
	private List`1 m_rangeListeners; // 0x18
	private List`1 m_rangeListenersWithOwner; // 0x20
	private static DelegateBridge __Hotfix0_get_attackRangeTiles; // 0x0
	private static DelegateBridge __Hotfix0_BindOwner; // 0x8
	private static DelegateBridge __Hotfix0_AddRangeListener; // 0x10
	private static DelegateBridge __Hotfix0_RemoveRangeListener; // 0x18
	private static DelegateBridge __Hotfix1_RemoveRangeListener; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28
	private static DelegateBridge __Hotfix0__Init; // 0x30
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x38
	private static DelegateBridge __Hotfix0__OnUnitReborn; // 0x40
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x48
	private static DelegateBridge __Hotfix0__OnUnitAttackRangeUpdated; // 0x50
	private static DelegateBridge __Hotfix0__ValidCharacter; // 0x58
	private static DelegateBridge __Hotfix0__RefreshCharacterRangeTiles; // 0x60
	private static DelegateBridge __Hotfix0__OnCharacterAttackRangeUpdate; // 0x68

	public Dictionary`2 attackRangeTiles { get; }

	// RVA: 0x409b0e4 VA: 0x75966b30e4
	public Dictionary`2 get_attackRangeTiles() { }
	// RVA: 0x409b14c VA: 0x75966b314c
	public Void BindOwner(IRangeListener listener, Character character) { }
	// RVA: 0x409b288 VA: 0x75966b3288
	public Void AddRangeListener(IRangeListener listener) { }
	// RVA: 0x409b384 VA: 0x75966b3384
	public Void RemoveRangeListener(IRangeListener listener) { }
	// RVA: 0x409b424 VA: 0x75966b3424
	public Void RemoveRangeListener(Character character) { }
	// RVA: 0x409b598 VA: 0x75966b3598
	public Void .ctor() { }
	// RVA: 0x409b8f8 VA: 0x75966b38f8
	private Void _Init() { }
	// RVA: 0x409bcb0 VA: 0x75966b3cb0
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x409c07c VA: 0x75966b407c
	private Void _OnUnitReborn(Object arg) { }
	// RVA: 0x409c174 VA: 0x75966b4174
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x409c2ec VA: 0x75966b42ec
	private Void _OnUnitAttackRangeUpdated(Object arg) { }
	// RVA: 0x409bda8 VA: 0x75966b3da8
	private Boolean _ValidCharacter(Character character) { }
	// RVA: 0x409bae0 VA: 0x75966b3ae0
	private Boolean _RefreshCharacterRangeTiles(Character character) { }
	// RVA: 0x409be84 VA: 0x75966b3e84
	private Void _OnCharacterAttackRangeUpdate(Character character) { }
}
```