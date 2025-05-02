# ToggleablePassiveBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Checker _checker`

- `Boolean _setToggleFalseOnDetached`

- `Boolean m_toggled`

- `FP m_nextActiveTime`


## Properties

- `Boolean toggled`

- `Checker checker`


## Methods

- `Boolean get_toggled()`

- `Void set_toggled(Boolean)`

- `Checker get_checker()`

- `Boolean _SetToggledInternal(Boolean, Boolean)`

- `Void _UpdateNextActiveTime()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_AddPassiveBuffs()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ToggleablePassiveBuffAbility : PassiveBuffAbility
{
	private Checker _checker; // 0x110
	private BuffData[] _unmanagedBuffsWhenToggleOn; // 0x118
	private Boolean _setToggleFalseOnDetached; // 0x120
	private Boolean m_toggled; // 0x121
	protected FP m_nextActiveTime; // 0x128
	private static DelegateBridge __Hotfix0_get_toggled; // 0x0
	private static DelegateBridge __Hotfix0_set_toggled; // 0x8
	private static DelegateBridge __Hotfix0_get_checker; // 0x10
	private static DelegateBridge __Hotfix0_get_unmanagedBuffsWhenToggleOn; // 0x18
	private static DelegateBridge __Hotfix0_DoSetData; // 0x20
	private static DelegateBridge __Hotfix0_DoAttach; // 0x28
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_AddPassiveBuffs; // 0x40
	private static DelegateBridge __Hotfix0_OnAttached; // 0x48
	private static DelegateBridge __Hotfix0_OnDetached; // 0x50
	private static DelegateBridge __Hotfix0_OnToggleChanged; // 0x58
	private static DelegateBridge __Hotfix0__SetToggledInternal; // 0x60
	private static DelegateBridge __Hotfix0__UpdateNextActiveTime; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	protected Boolean toggled { get; set; }
	protected Checker checker { get; }
	protected virtual BuffData[] unmanagedBuffsWhenToggleOn { get; }

	// RVA: 0x1e610dc VA: 0x75944790dc
	protected Boolean get_toggled() { }
	// RVA: 0x1e61144 VA: 0x7594479144
	protected Void set_toggled(Boolean value) { }
	// RVA: 0x1e61338 VA: 0x7594479338
	protected Checker get_checker() { }
	// RVA: 0x1e61410 VA: 0x7594479410
	protected virtual BuffData[] get_unmanagedBuffsWhenToggleOn() { }
	// RVA: 0x1e609a4 VA: 0x75944789a4
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e61514 VA: 0x7594479514
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e6159c VA: 0x759447959c
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e61674 VA: 0x7594479674
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e61718 VA: 0x7594479718
	protected override Void AddPassiveBuffs() { }
	// RVA: 0x1e61910 VA: 0x7594479910
	protected override Void OnAttached() { }
	// RVA: 0x1e61a7c VA: 0x7594479a7c
	protected override Void OnDetached() { }
	// RVA: 0x1e60cbc VA: 0x7594478cbc
	protected virtual Void OnToggleChanged(Boolean isToggled) { }
	// RVA: 0x1e611c8 VA: 0x75944791c8
	private Boolean _SetToggledInternal(Boolean value, Boolean force) { }
	// RVA: 0x1e61b1c VA: 0x7594479b1c
	private Void _UpdateNextActiveTime() { }
	// RVA: 0x1e60bb4 VA: 0x7594478bb4
	public Void .ctor() { }
	// RVA: 0x1e61c20 VA: 0x7594479c20
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e61c48 VA: 0x7594479c48
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e61c50 VA: 0x7594479c50
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e61c58 VA: 0x7594479c58
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1e61c60 VA: 0x7594479c60
	private Void <>xLuaBaseProxy_AddPassiveBuffs() { }
	// RVA: 0x1e61c68 VA: 0x7594479c68
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e61c70 VA: 0x7594479c70
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```