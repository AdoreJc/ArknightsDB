# BuffDuringSkill

**Namespace:** `Torappu.Battle.Skills`


## Methods

- `Void GatherEffects(List`1)`

- `Void GatherBuffs(List`1)`

- `Void _ClearBuffs()`

- `Void <>xLuaBaseProxy_OnSkillStart()`

- `Void <>xLuaBaseProxy_OnSkillEnd()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Skills
public class BuffDuringSkill : Behaviour, IEffectSource, IBuffSource
{
	private BuffData[] _buffs; // 0x20
	private List`1 m_buffUid; // 0x28
	private static DelegateBridge __Hotfix0_OnSkillStart; // 0x0
	private static DelegateBridge __Hotfix0_OnSkillEnd; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge __Hotfix0__ClearBuffs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1d2fde0 VA: 0x7594347de0
	public override Void OnSkillStart() { }
	// RVA: 0x1d30040 VA: 0x7594348040
	public override Void OnSkillEnd() { }
	// RVA: 0x1d300b4 VA: 0x75943480b4
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d30138 VA: 0x7594348138
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1d2ff50 VA: 0x7594347f50
	private Void _ClearBuffs() { }
	// RVA: 0x1d301d8 VA: 0x75943481d8
	public Void .ctor() { }
	// RVA: 0x1d302d8 VA: 0x75943482d8
	private Void <>xLuaBaseProxy_OnSkillStart() { }
	// RVA: 0x1d302e0 VA: 0x75943482e0
	private Void <>xLuaBaseProxy_OnSkillEnd() { }
}
```