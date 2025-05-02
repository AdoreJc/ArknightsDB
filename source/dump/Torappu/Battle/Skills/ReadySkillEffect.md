# ReadySkillEffect

**Namespace:** `Torappu.Battle.Skills`


## Fields

- `Boolean _stopBeforeCast`

- `Boolean m_effectsCreated`


## Properties

- `Boolean effectsCreated`


## Methods

- `Void GatherEffects(List`1)`

- `Boolean get_effectsCreated()`

- `Void _ClearEffect()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnSkillStart()`

- `Void <>xLuaBaseProxy_OnSkillEnd()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnOwnerFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Skills
public class ReadySkillEffect : Behaviour, IEffectSource
{
	private String[] _effects; // 0x20
	private Boolean _stopBeforeCast; // 0x28
	private List`1 m_effects; // 0x30
	private Boolean m_effectsCreated; // 0x38
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x0
	private static DelegateBridge __Hotfix0_get_effectsCreated; // 0x8
	private static DelegateBridge __Hotfix0_get_effects; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0_OnSkillStart; // 0x20
	private static DelegateBridge __Hotfix0_OnSkillEnd; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnOwnerFinish; // 0x38
	private static DelegateBridge __Hotfix0__ClearEffect; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected Boolean effectsCreated { get; }
	protected List`1 effects { get; }

	// RVA: 0x1d332f8 VA: 0x759434b2f8
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d3341c VA: 0x759434b41c
	protected Boolean get_effectsCreated() { }
	// RVA: 0x1d33484 VA: 0x759434b484
	protected List`1 get_effects() { }
	// RVA: 0x1d334ec VA: 0x759434b4ec
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d33734 VA: 0x759434b734
	public override Void OnSkillStart() { }
	// RVA: 0x1d339d4 VA: 0x759434b9d4
	public override Void OnSkillEnd() { }
	// RVA: 0x1d33a48 VA: 0x759434ba48
	public override Void OnInit() { }
	// RVA: 0x1d33abc VA: 0x759434babc
	public override Void OnOwnerFinish() { }
	// RVA: 0x1d337bc VA: 0x759434b7bc
	private Void _ClearEffect() { }
	// RVA: 0x1d33b30 VA: 0x759434bb30
	public Void .ctor() { }
	// RVA: 0x1d33bf4 VA: 0x759434bbf4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d33bfc VA: 0x759434bbfc
	private Void <>xLuaBaseProxy_OnSkillStart() { }
	// RVA: 0x1d33c04 VA: 0x759434bc04
	private Void <>xLuaBaseProxy_OnSkillEnd() { }
	// RVA: 0x1d33c0c VA: 0x759434bc0c
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x1d33c14 VA: 0x759434bc14
	private Void <>xLuaBaseProxy_OnOwnerFinish() { }
}
```