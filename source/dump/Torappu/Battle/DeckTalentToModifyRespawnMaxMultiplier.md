# DeckTalentToModifyRespawnMaxMultiplier

**Namespace:** `Torappu.Battle`


## Fields

- `DeckSelector _selector`

- `FP m_maxMultiplier`


## Methods

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DeckTalentToModifyRespawnMaxMultiplier : DeckTalent
{
	private DeckSelector _selector; // 0x48
	private FP m_maxMultiplier; // 0x78
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0_CreateDeckModifier; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b7a33c VA: 0x759419233c
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b7a460 VA: 0x7594192460
	public override DeckModifier CreateDeckModifier(Card sourceCard) { }
	// RVA: 0x1b7a59c VA: 0x759419259c
	public Void .ctor() { }
	// RVA: 0x1b7a63c VA: 0x759419263c
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
}
```