# BldskTalent_1

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TargetOptions _targetOptions`

- `BuffData _selfBuff`

- `BuffData _randomBuff`

- `ActionArray _actions`


## Methods

- `Void _OnTrigger(Unit)`

- `Void _OnUnitFinish(Object)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BldskTalent_1 : PassiveBuffAbility
{
	private TargetOptions _targetOptions; // 0x110
	private BuffData _selfBuff; // 0x170
	private BuffData _randomBuff; // 0x178
	private ActionArray _actions; // 0x180
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_OnAttached; // 0x8
	private static DelegateBridge __Hotfix0_OnDetached; // 0x10
	private static DelegateBridge __Hotfix0__OnTrigger; // 0x18
	private static DelegateBridge __Hotfix0__OnUnitFinish; // 0x20
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1e69e9c VA: 0x7594481e9c
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e69f3c VA: 0x7594481f3c
	protected override Void OnAttached() { }
	// RVA: 0x1e6a050 VA: 0x7594482050
	protected override Void OnDetached() { }
	// RVA: 0x1e6a164 VA: 0x7594482164
	private Void _OnTrigger(Unit unit) { }
	// RVA: 0x1e6a72c VA: 0x759448272c
	private Void _OnUnitFinish(Object arg) { }
	// RVA: 0x1e6a914 VA: 0x7594482914
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1e6a9b8 VA: 0x75944829b8
	public Void .ctor() { }
	// RVA: 0x1e6aa68 VA: 0x7594482a68
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e6aa70 VA: 0x7594482a70
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e6aa78 VA: 0x7594482a78
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1e6aa80 VA: 0x7594482a80
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
}
```