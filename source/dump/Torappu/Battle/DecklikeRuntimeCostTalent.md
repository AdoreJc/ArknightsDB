# DecklikeRuntimeCostTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Options _options`

- `Int32 _runtimeCost`

- `Int32 m_runtimeCost`


## Methods

- `RuntimeCostModifier CreateDecklikeRuntimeCostModifier(Card)`

- `Boolean <>xLuaBaseProxy_get_attachInDummy()`

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DecklikeRuntimeCostTalent : BasicTalent
{
	private Options _options; // 0x48
	protected Int32 _runtimeCost; // 0x50
	private Int32 m_runtimeCost; // 0x54
	private static DelegateBridge __Hotfix0_get_attachInDummy; // 0x0
	private static DelegateBridge __Hotfix0_AssignData; // 0x8
	private static DelegateBridge __Hotfix0_CreateDecklikeRuntimeCostModifier; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Boolean attachInDummy { get; }

	// RVA: 0x1b78640 VA: 0x7594190640
	public override Boolean get_attachInDummy() { }
	// RVA: 0x1b786a8 VA: 0x75941906a8
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b7879c VA: 0x759419079c
	public RuntimeCostModifier CreateDecklikeRuntimeCostModifier(Card sourceCard) { }
	// RVA: 0x1b7890c VA: 0x759419090c
	public Void .ctor() { }
	// RVA: 0x1b78978 VA: 0x7594190978
	private Boolean <>xLuaBaseProxy_get_attachInDummy() { }
	// RVA: 0x1b7897c VA: 0x759419097c
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
}
```