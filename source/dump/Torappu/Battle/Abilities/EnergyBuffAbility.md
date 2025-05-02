# EnergyBuffAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `BuffData _buff`

- `Boolean _overEnergied`

- `String _castAbility`

- `Ability m_castAbility`

- `Int32 <maxEnergy>k__BackingField`


## Properties

- `Int32 maxEnergy`

- `Int32 energyCnt`

- `Boolean overEnergyIsCasting`

- `FP castProgress`


## Methods

- `Int32 get_maxEnergy()`

- `Void set_maxEnergy(Int32)`

- `Int32 get_energyCnt()`

- `Boolean get_overEnergyIsCasting()`

- `FP get_castProgress()`

- `Void _InitEnergy()`

- `Void _ClearEnergy()`

- `Void UpdateEnergy()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_OnOwnerLocated()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class EnergyBuffAbility : EmptyAbility
{
	protected BuffData _buff; // 0x108
	protected Boolean _overEnergied; // 0x110
	private String _castAbility; // 0x118
	private ObjectPtr`1 m_buff; // 0x120
	private Ability m_castAbility; // 0x130
	private Int32 <maxEnergy>k__BackingField; // 0x138
	private static DelegateBridge __Hotfix0_get_maxEnergy; // 0x0
	private static DelegateBridge __Hotfix0_set_maxEnergy; // 0x8
	private static DelegateBridge __Hotfix0_get_energyCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_overEnergyIsCasting; // 0x18
	private static DelegateBridge __Hotfix0_get_castProgress; // 0x20
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x28
	private static DelegateBridge __Hotfix0_DoSetData; // 0x30
	private static DelegateBridge __Hotfix0_DoDetach; // 0x38
	private static DelegateBridge __Hotfix0_OnOwnerLocated; // 0x40
	private static DelegateBridge __Hotfix0__InitEnergy; // 0x48
	private static DelegateBridge __Hotfix0__ClearEnergy; // 0x50
	private static DelegateBridge __Hotfix0_UpdateEnergy; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Int32 maxEnergy { get; set; }
	public Int32 energyCnt { get; }
	public Boolean overEnergyIsCasting { get; }
	public FP castProgress { get; }

	// RVA: 0x1e51700 VA: 0x7594469700
	public Int32 get_maxEnergy() { }
	// RVA: 0x1e51768 VA: 0x7594469768
	private Void set_maxEnergy(Int32 value) { }
	// RVA: 0x1e517e4 VA: 0x75944697e4
	public Int32 get_energyCnt() { }
	// RVA: 0x1e518ac VA: 0x75944698ac
	public Boolean get_overEnergyIsCasting() { }
	// RVA: 0x1e51974 VA: 0x7594469974
	public FP get_castProgress() { }
	// RVA: 0x1e51a90 VA: 0x7594469a90
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e51b84 VA: 0x7594469b84
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e51cb4 VA: 0x7594469cb4
	protected override Void DoDetach() { }
	// RVA: 0x1e51dc8 VA: 0x7594469dc8
	public override Void OnOwnerLocated() { }
	// RVA: 0x1e51e3c VA: 0x7594469e3c
	private Void _InitEnergy() { }
	// RVA: 0x1e51d28 VA: 0x7594469d28
	private Void _ClearEnergy() { }
	// RVA: 0x1e51f90 VA: 0x7594469f90
	public Void UpdateEnergy() { }
	// RVA: 0x1e52328 VA: 0x759446a328
	public Void .ctor() { }
	// RVA: 0x1e52418 VA: 0x759446a418
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e52420 VA: 0x759446a420
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e52448 VA: 0x759446a448
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1e52450 VA: 0x759446a450
	private Void <>xLuaBaseProxy_OnOwnerLocated() { }
}
```