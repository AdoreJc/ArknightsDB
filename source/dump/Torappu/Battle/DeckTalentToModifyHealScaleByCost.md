# DeckTalentToModifyHealScaleByCost

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _maxCost`

- `Int32 m_maxCost`


## Methods

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`

- `DeckModifier <>xLuaBaseProxy_CreateDeckModifier(Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DeckTalentToModifyHealScaleByCost : DeckBuffTalent
{
	private Int32 _maxCost; // 0x58
	private Int32 m_maxCost; // 0x5c
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0_CreateDeckModifier; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b79f84 VA: 0x7594191f84
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b7a074 VA: 0x7594192074
	public override DeckModifier CreateDeckModifier(Card sourceCard) { }
	// RVA: 0x1b7a1e4 VA: 0x75941921e4
	public Void .ctor() { }
	// RVA: 0x1b7a250 VA: 0x7594192250
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
	// RVA: 0x1b7a254 VA: 0x7594192254
	private DeckModifier <>xLuaBaseProxy_CreateDeckModifier(Card P0) { }
}
```