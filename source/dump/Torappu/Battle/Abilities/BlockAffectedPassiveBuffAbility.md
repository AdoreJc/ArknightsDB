# BlockAffectedPassiveBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void _HandleBlockAffectedBuffs(Object)`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BlockAffectedPassiveBuffAbility : PassiveBuffAbility
{
	private static List`1 s_tmpBuffList; // 0x0
	private BuffData[] _blockAffectedBuffs; // 0x110
	private ListDict`2 m_blockBuffMap; // 0x118
	private static DelegateBridge __Hotfix0_OnAttached; // 0x8
	private static DelegateBridge __Hotfix0_OnDetached; // 0x10
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x18
	private static DelegateBridge __Hotfix0__HandleBlockAffectedBuffs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1e509c8 VA: 0x75944689c8
	protected override Void OnAttached() { }
	// RVA: 0x1e50b14 VA: 0x7594468b14
	protected override Void OnDetached() { }
	// RVA: 0x1e50d00 VA: 0x7594468d00
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e50df4 VA: 0x7594468df4
	private Void _HandleBlockAffectedBuffs(Object arg) { }
	// RVA: 0x1e514d4 VA: 0x75944694d4
	public Void .ctor() { }
	// RVA: 0x1e51650 VA: 0x7594469650
	private static Void .cctor() { }
	// RVA: 0x1e516e8 VA: 0x75944696e8
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e516f0 VA: 0x75944696f0
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e516f8 VA: 0x75944696f8
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```