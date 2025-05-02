# SelectorOrAlwaysTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `IAlwaysTrigger m_ability`


## Methods

- `Boolean <>xLuaBaseProxy_get_isReadyToTrig()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability)`

- `Boolean <>xLuaBaseProxy_Search(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SelectorOrAlwaysTrigger : SelectorTrigger
{
	private IAlwaysTrigger m_ability; // 0x50
	private static DelegateBridge __Hotfix0_get_isReadyToTrig; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_Search; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Boolean isReadyToTrig { get; }

	// RVA: 0x1bd92dc VA: 0x75941f12dc
	public override Boolean get_isReadyToTrig() { }
	// RVA: 0x1bd9344 VA: 0x75941f1344
	public override Void Reset(Entity owner, Ability ability) { }
	// RVA: 0x1bd940c VA: 0x75941f140c
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd9524 VA: 0x75941f1524
	public Void .ctor() { }
	// RVA: 0x1bd9590 VA: 0x75941f1590
	private Boolean <>xLuaBaseProxy_get_isReadyToTrig() { }
	// RVA: 0x1bd9594 VA: 0x75941f1594
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1) { }
	// RVA: 0x1bd9598 VA: 0x75941f1598
	private Boolean <>xLuaBaseProxy_Search(Boolean P0) { }
}
```