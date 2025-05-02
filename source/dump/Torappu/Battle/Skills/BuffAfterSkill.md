# BuffAfterSkill

**Namespace:** `Torappu.Battle.Skills`


## Fields

- `Boolean m_waitForSkillEnd`


## Methods

- `Void GatherEffects(List`1)`

- `Void GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_OnSkillStart()`

- `Void <>xLuaBaseProxy_OnSkillEnd()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Skills
public class BuffAfterSkill : Behaviour, IEffectSource, IBuffSource
{
	private BuffData[] _buffs; // 0x20
	private Boolean m_waitForSkillEnd; // 0x28
	private static DelegateBridge __Hotfix0_OnSkillStart; // 0x0
	private static DelegateBridge __Hotfix0_OnSkillEnd; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1d2f9e4 VA: 0x75943479e4
	public override Void OnSkillStart() { }
	// RVA: 0x1d2faa8 VA: 0x7594347aa8
	public override Void OnSkillEnd() { }
	// RVA: 0x1d2fc00 VA: 0x7594347c00
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d2fc84 VA: 0x7594347c84
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1d2fd24 VA: 0x7594347d24
	public Void .ctor() { }
	// RVA: 0x1d2fdd0 VA: 0x7594347dd0
	private Void <>xLuaBaseProxy_OnSkillStart() { }
	// RVA: 0x1d2fdd8 VA: 0x7594347dd8
	private Void <>xLuaBaseProxy_OnSkillEnd() { }
}
```