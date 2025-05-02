# BoomberangAttackTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `BoomberangTrait m_trait`


## Methods

- `Void <>xLuaBaseProxy_Reset(Entity, Ability)`

- `Boolean <>xLuaBaseProxy_Search(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BoomberangAttackTrigger : SelectorTrigger
{
	private BoomberangTrait m_trait; // 0x50
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_Search; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1bd40e0 VA: 0x75941ec0e0
	public override Void Reset(Entity owner, Ability ability) { }
	// RVA: 0x1bd44f0 VA: 0x75941ec4f0
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd4998 VA: 0x75941ec998
	public Void .ctor() { }
	// RVA: 0x1bd4b08 VA: 0x75941ecb08
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1) { }
	// RVA: 0x1bd4b0c VA: 0x75941ecb0c
	private Boolean <>xLuaBaseProxy_Search(Boolean P0) { }
}
```