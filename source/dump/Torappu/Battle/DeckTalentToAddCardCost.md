# DeckTalentToAddCardCost

**Namespace:** `Torappu.Battle`


## Fields

- `DeckSelector _selector`

- `Int32 m_cost`


## Methods

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DeckTalentToAddCardCost : DeckTalent
{
	private DeckSelector _selector; // 0x48
	private Int32 m_cost; // 0x78
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0_CreateDeckModifier; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b7966c VA: 0x759419166c
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b7975c VA: 0x759419175c
	public override DeckModifier CreateDeckModifier(Card sourceCard) { }
	// RVA: 0x1b79984 VA: 0x7594191984
	public Void .ctor() { }
	// RVA: 0x1b799f0 VA: 0x75941919f0
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
}
```