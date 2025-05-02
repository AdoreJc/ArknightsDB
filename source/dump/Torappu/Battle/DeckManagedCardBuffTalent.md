# DeckManagedCardBuffTalent

**Namespace:** `Torappu.Battle`


## Fields

- `String _cardBuffKey`

- `ManageType _manageType`

- `Boolean _excludeTokenAndTrap`

- `DeckSelector _selector`


## Methods

- `Void RegisterDeckManagedCardBuff(Deck, Card)`

- `Boolean <>xLuaBaseProxy_get_attachInDummy()`

- `Boolean <>xLuaBaseProxy_get_affectInDeck()`

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DeckManagedCardBuffTalent : BasicTalent
{
	private String _cardBuffKey; // 0x48
	private ManageType _manageType; // 0x50
	private Boolean _excludeTokenAndTrap; // 0x54
	private DeckSelector _selector; // 0x58
	private static DelegateBridge __Hotfix0_get_attachInDummy; // 0x0
	private static DelegateBridge __Hotfix0_get_affectInDeck; // 0x8
	private static DelegateBridge __Hotfix0_RegisterDeckManagedCardBuff; // 0x10
	private static DelegateBridge __Hotfix0_AssignData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override Boolean attachInDummy { get; }
	public override Boolean affectInDeck { get; }

	// RVA: 0x1b78c58 VA: 0x7594190c58
	public override Boolean get_attachInDummy() { }
	// RVA: 0x1b78cbc VA: 0x7594190cbc
	public override Boolean get_affectInDeck() { }
	// RVA: 0x1b78d24 VA: 0x7594190d24
	public Void RegisterDeckManagedCardBuff(Deck deck, Card card) { }
	// RVA: 0x1b78f1c VA: 0x7594190f1c
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b78fcc VA: 0x7594190fcc
	public Void .ctor() { }
	// RVA: 0x1b79040 VA: 0x7594191040
	private Boolean <>xLuaBaseProxy_get_attachInDummy() { }
	// RVA: 0x1b79044 VA: 0x7594191044
	private Boolean <>xLuaBaseProxy_get_affectInDeck() { }
	// RVA: 0x1b79048 VA: 0x7594191048
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
}
```