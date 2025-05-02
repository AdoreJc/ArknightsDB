# Thorn2CardTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _passableCnt`

- `MotionMode _motion`

- `Int32 m_passableCnt`


## Methods

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Thorn2CardTalent : CardHoldTalent
{
	private Int32 _passableCnt; // 0x50
	private MotionMode _motion; // 0x54
	private Int32 m_passableCnt; // 0x58
	private static DelegateBridge __Hotfix0_AssignData; // 0x0
	private static DelegateBridge __Hotfix0_CreateHoldDataModifier; // 0x8
	private static DelegateBridge __Hotfix0_CreateCardEffectPlugin; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1b7a720 VA: 0x7594192720
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b7a810 VA: 0x7594192810
	public override CardHoldDataModifier CreateHoldDataModifier(Character character) { }
	// RVA: 0x1b7b03c VA: 0x759419303c
	public override CardEffectPlugin CreateCardEffectPlugin(Character character, CardHoldDataModifier modifier) { }
	// RVA: 0x1b7b0bc VA: 0x75941930bc
	public Void .ctor() { }
	// RVA: 0x1b7b128 VA: 0x7594193128
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
}
```