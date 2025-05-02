# DeckTakeExtraEnemyTalent

**Namespace:** `Torappu.Battle`


## Fields

- `TalentData m_talentData`


## Methods

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DeckTakeExtraEnemyTalent : DeckTalent
{
	private TalentData m_talentData; // 0x48
	private List`1 m_enemyIdList; // 0x50
	private List`1 m_enemyLevelList; // 0x58
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0_CreateDeckModifier; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b77a5c VA: 0x759418fa5c
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b77b1c VA: 0x759418fb1c
	public override DeckModifier CreateDeckModifier(Card sourceCard) { }
	// RVA: 0x1b77c10 VA: 0x759418fc10
	public Void .ctor() { }
	// RVA: 0x1b77d8c VA: 0x759418fd8c
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
}
```