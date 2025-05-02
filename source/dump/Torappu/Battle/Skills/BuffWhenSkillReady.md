# BuffWhenSkillReady

**Namespace:** `Torappu.Battle.Skills`


## Fields

- `Boolean _clearBuffGivenLastTime`

- `Int32 m_cachedSkillStack`


## Methods

- `Void GatherBuffs(List`1)`

- `Void GatherEffects(List`1)`

- `Void _ClearBuffs()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Skills
public class BuffWhenSkillReady : Behaviour, IBuffSource, IEffectSource
{
	private BuffData[] _buffs; // 0x20
	private Boolean _clearBuffGivenLastTime; // 0x28
	private Int32 m_cachedSkillStack; // 0x2c
	private List`1 m_buffUid; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x0
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x18
	private static DelegateBridge __Hotfix0__ClearBuffs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1d302e8 VA: 0x75943482e8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1d3064c VA: 0x759434864c
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1d306ec VA: 0x75943486ec
	public override Void OnInit() { }
	// RVA: 0x1d30760 VA: 0x7594348760
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1d3055c VA: 0x759434855c
	private Void _ClearBuffs() { }
	// RVA: 0x1d307e4 VA: 0x75943487e4
	public Void .ctor() { }
	// RVA: 0x1d308e4 VA: 0x75943488e4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1d308ec VA: 0x75943488ec
	private Void <>xLuaBaseProxy_OnInit() { }
}
```