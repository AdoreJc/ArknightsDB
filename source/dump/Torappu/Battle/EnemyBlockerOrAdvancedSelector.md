# EnemyBlockerOrAdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Enemy m_enemy`


## Methods

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnemyBlockerOrAdvancedSelector : AdvancedSelector
{
	private Enemy m_enemy; // 0xe8
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1ba9344 VA: 0x75941c1344
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1ba947c VA: 0x75941c147c
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba98a8 VA: 0x75941c18a8
	public Void .ctor() { }
	// RVA: 0x1ba9918 VA: 0x75941c1918
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1ba9920 VA: 0x75941c1920
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
}
```