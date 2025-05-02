# PassiveOneOfBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `SelectMethod _selectMethod`

- `Int32 m_attachCnt`

- `String m_lastCastedBuffKey`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class PassiveOneOfBuffAbility : PassiveBuffAbility
{
	private SelectMethod _selectMethod; // 0x110
	private Int32 m_attachCnt; // 0x114
	private String m_lastCastedBuffKey; // 0x118
	private List`1 m_buffGroupThisTime; // 0x120
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_GetPassiveBuffs; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e553c0 VA: 0x759446d3c0
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e55494 VA: 0x759446d494
	protected override IList`1 GetPassiveBuffs() { }
	// RVA: 0x1e5591c VA: 0x759446d91c
	public Void .ctor() { }
	// RVA: 0x1e559dc VA: 0x759446d9dc
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e55a04 VA: 0x759446da04
	private IList`1 <>xLuaBaseProxy_GetPassiveBuffs() { }
}
```