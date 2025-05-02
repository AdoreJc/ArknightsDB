# RallyPoint

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _showFullHpOnBorn`

- `EntityCategory m_categoty`

- `Boolean m_isFirstReborn`

- `RallyPointRebornTalent <rallyPointRebornTalent>k__BackingField`


## Properties

- `Boolean inRallyPointMode`

- `Boolean inDefaultMode`

- `RallyPointRebornTalent rallyPointRebornTalent`

- `FP rebornProgress`


## Methods

- `Boolean get_inRallyPointMode()`

- `Boolean get_inDefaultMode()`

- `RallyPointRebornTalent get_rallyPointRebornTalent()`

- `Void set_rallyPointRebornTalent(RallyPointRebornTalent)`

- `FP get_rebornProgress()`

- `Void SwitchCategory(EntityCategory)`

- `Void RecoverHpLikeReborn()`

- `EntityCategory <>xLuaBaseProxy_get_category()`

- `FP <>xLuaBaseProxy_get_hpToShow()`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Boolean <>xLuaBaseProxy_get_withdrawable()`

- `Boolean <>xLuaBaseProxy_Withdraw(Boolean, Boolean, Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnAwake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RallyPoint : Trap
{
	private List`1 _retainedBuffsWhenDead; // 0x4f8
	private Boolean _showFullHpOnBorn; // 0x500
	private EntityCategory m_categoty; // 0x504
	private Boolean m_isFirstReborn; // 0x508
	private RallyPointRebornTalent <rallyPointRebornTalent>k__BackingField; // 0x510
	private static DelegateBridge __Hotfix0_get_inRallyPointMode; // 0x0
	private static DelegateBridge __Hotfix0_get_inDefaultMode; // 0x8
	private static DelegateBridge __Hotfix0_get_category; // 0x10
	private static DelegateBridge __Hotfix0_get_rallyPointRebornTalent; // 0x18
	private static DelegateBridge __Hotfix0_set_rallyPointRebornTalent; // 0x20
	private static DelegateBridge __Hotfix0_get_rebornProgress; // 0x28
	private static DelegateBridge __Hotfix0_get_hpToShow; // 0x30
	private static DelegateBridge __Hotfix0_OnBorn; // 0x38
	private static DelegateBridge __Hotfix0_SwitchCategory; // 0x40
	private static DelegateBridge __Hotfix0_get_withdrawable; // 0x48
	private static DelegateBridge __Hotfix0_RecoverHpLikeReborn; // 0x50
	private static DelegateBridge __Hotfix0_Withdraw; // 0x58
	private static DelegateBridge __Hotfix0_OnAwake; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Boolean inRallyPointMode { get; }
	public Boolean inDefaultMode { get; }
	public override EntityCategory category { get; }
	public RallyPointRebornTalent rallyPointRebornTalent { get; set; }
	public FP rebornProgress { get; }
	public override FP hpToShow { get; }
	public override Boolean withdrawable { get; }

	// RVA: 0x1c24bec VA: 0x759423cbec
	public Boolean get_inRallyPointMode() { }
	// RVA: 0x1c24c5c VA: 0x759423cc5c
	public Boolean get_inDefaultMode() { }
	// RVA: 0x1c24ccc VA: 0x759423cccc
	public override EntityCategory get_category() { }
	// RVA: 0x1c24d34 VA: 0x759423cd34
	public RallyPointRebornTalent get_rallyPointRebornTalent() { }
	// RVA: 0x1c24d9c VA: 0x759423cd9c
	private Void set_rallyPointRebornTalent(RallyPointRebornTalent value) { }
	// RVA: 0x1c24e20 VA: 0x759423ce20
	public FP get_rebornProgress() { }
	// RVA: 0x1c24edc VA: 0x759423cedc
	public override FP get_hpToShow() { }
	// RVA: 0x1c24fc0 VA: 0x759423cfc0
	protected override Void OnBorn() { }
	// RVA: 0x1c2503c VA: 0x759423d03c
	public Void SwitchCategory(EntityCategory categoty) { }
	// RVA: 0x1c25188 VA: 0x759423d188
	public override Boolean get_withdrawable() { }
	// RVA: 0x1c252a0 VA: 0x759423d2a0
	public Void RecoverHpLikeReborn() { }
	// RVA: 0x1c2533c VA: 0x759423d33c
	public override Boolean Withdraw(Boolean switchToDeadState, Boolean force, Boolean manual, Boolean logAutoWithdraw) { }
	// RVA: 0x1c2555c VA: 0x759423d55c
	protected override Void OnAwake() { }
	// RVA: 0x1c25760 VA: 0x759423d760
	public Void .ctor() { }
	// RVA: 0x1c257cc VA: 0x759423d7cc
	private EntityCategory <>xLuaBaseProxy_get_category() { }
	// RVA: 0x1c25838 VA: 0x759423d838
	private FP <>xLuaBaseProxy_get_hpToShow() { }
	// RVA: 0x1c258a8 VA: 0x759423d8a8
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x1c258b0 VA: 0x759423d8b0
	private Boolean <>xLuaBaseProxy_get_withdrawable() { }
	// RVA: 0x1c258b4 VA: 0x759423d8b4
	private Boolean <>xLuaBaseProxy_Withdraw(Boolean P0, Boolean P1, Boolean P2, Boolean P3) { }
	// RVA: 0x1c258cc VA: 0x759423d8cc
	private Void <>xLuaBaseProxy_OnAwake() { }
}
```