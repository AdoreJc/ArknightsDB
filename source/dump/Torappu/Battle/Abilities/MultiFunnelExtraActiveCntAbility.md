# MultiFunnelExtraActiveCntAbility

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void AddExtraFunnelActiveCnt(String, Int32)`

- `Int32 GetExtraFunnelActiveCnt(String)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class MultiFunnelExtraActiveCntAbility : PassiveBuffAbility
{
	private Dictionary`2 m_abilityExtraFunnelActiveCnt; // 0x110
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_AddExtraFunnelActiveCnt; // 0x8
	private static DelegateBridge __Hotfix0_GetExtraFunnelActiveCnt; // 0x10
	private static DelegateBridge __Hotfix0_DoDetach; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e7c0f8 VA: 0x75944940f8
	protected override Void Reset() { }
	// RVA: 0x1e7c18c VA: 0x759449418c
	public Void AddExtraFunnelActiveCnt(String abilityName, Int32 cnt) { }
	// RVA: 0x1e7c2c0 VA: 0x75944942c0
	public Int32 GetExtraFunnelActiveCnt(String abilityName) { }
	// RVA: 0x1e7c370 VA: 0x7594494370
	protected override Void DoDetach() { }
	// RVA: 0x1e7c404 VA: 0x7594494404
	public Void .ctor() { }
	// RVA: 0x1e7c4c8 VA: 0x75944944c8
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x1e7c4d0 VA: 0x75944944d0
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```