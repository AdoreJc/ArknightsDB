# ActiveOneOfBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 m_spellCnt`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_OnSpellStart()`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ActiveOneOfBuffAbility : ActiveBuffAbility
{
	private List`1 _extraBuffs; // 0x160
	private Int32 m_spellCnt; // 0x168
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnSpellStart; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1e1dccc VA: 0x7594435ccc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e1dd70 VA: 0x7594435d70
	protected override Boolean OnSpellStart() { }
	// RVA: 0x1e1ded0 VA: 0x7594435ed0
	protected override Void Reset() { }
	// RVA: 0x1e1df40 VA: 0x7594435f40
	public Void .ctor() { }
	// RVA: 0x1e1dfac VA: 0x7594435fac
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e1dfd0 VA: 0x7594435fd0
	private Boolean <>xLuaBaseProxy_OnSpellStart() { }
	// RVA: 0x1e1dfd4 VA: 0x7594435fd4
	private Void <>xLuaBaseProxy_Reset() { }
}
```