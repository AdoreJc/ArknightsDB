# DeckBuffTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Options _options`


## Methods

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DeckBuffTalent : DeckTalent
{
	private Options _options; // 0x48
	protected DeckBuff[] _deckBuffs; // 0x50
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0_CreateDeckModifier; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1b77fd8 VA: 0x759418ffd8
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b78108 VA: 0x7594190108
	public override DeckModifier CreateDeckModifier(Card sourceCard) { }
	// RVA: 0x1b78284 VA: 0x7594190284
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1b783dc VA: 0x75941903dc
	public Void .ctor() { }
	// RVA: 0x1b78484 VA: 0x7594190484
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
	// RVA: 0x1b78488 VA: 0x7594190488
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```