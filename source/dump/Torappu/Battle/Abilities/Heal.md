# Heal

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _isCont`

- `Boolean _isHpRatio`

- `Boolean _hasNoActionNode`

- `Boolean _ignoreHealFree`

- `Boolean _applyEPHeal`

- `Boolean _applyHealScaleToEPHealScale`

- `Single m_healScale`

- `ApplyHeal m_healNode`

- `FP m_elementHealScale`

- `ApplyElementHeal m_elementHealNode`


## Properties

- `Boolean isCont`

- `Boolean ignoreHealFree`

- `Boolean isHpRatio`

- `FP healScale`


## Methods

- `Boolean get_isCont()`

- `Boolean get_ignoreHealFree()`

- `Boolean get_isHpRatio()`

- `FP get_healScale()`

- `Void ApplyHealScale(FP, Boolean, Boolean)`

- `Void ApplyElementHealScale(FP, Boolean)`

- `Void ApplyElementHealScaleForElementHealNode(FP)`

- `SourceApplyWay <>xLuaBaseProxy_get_applyWay()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_CheckIsDamageOrHealSource()`

- `ActionPurposeMask <>xLuaBaseProxy_GeneratePurposeMask()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class Heal : AbstractAnimatedAbility
{
	private Boolean _isCont; // 0x1c0
	private Boolean _isHpRatio; // 0x1c1
	private Boolean _hasNoActionNode; // 0x1c2
	private Boolean _ignoreHealFree; // 0x1c3
	private Boolean _applyEPHeal; // 0x1c4
	private Boolean _applyHealScaleToEPHealScale; // 0x1c5
	protected Single m_healScale; // 0x1c8
	protected ApplyHeal m_healNode; // 0x1d0
	protected List`1 m_actions; // 0x1d8
	protected FP m_elementHealScale; // 0x1e0
	protected ApplyElementHeal m_elementHealNode; // 0x1e8
	private static DelegateBridge __Hotfix0_get_isCont; // 0x0
	private static DelegateBridge __Hotfix0_get_ignoreHealFree; // 0x8
	private static DelegateBridge __Hotfix0_get_isHpRatio; // 0x10
	private static DelegateBridge __Hotfix0_get_applyWay; // 0x18
	private static DelegateBridge __Hotfix0_get_healScale; // 0x20
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x28
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x30
	private static DelegateBridge __Hotfix0_ApplyHealScale; // 0x38
	private static DelegateBridge __Hotfix0_ApplyElementHealScale; // 0x40
	private static DelegateBridge __Hotfix0_ApplyElementHealScaleForElementHealNode; // 0x48
	private static DelegateBridge __Hotfix0_DoSetData; // 0x50
	private static DelegateBridge __Hotfix0_NewHealNode; // 0x58
	private static DelegateBridge __Hotfix0_NewElementHealNode; // 0x60
	private static DelegateBridge __Hotfix0_CheckIsDamageOrHealSource; // 0x68
	private static DelegateBridge __Hotfix0_GeneratePurposeMask; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	protected Boolean isCont { get; }
	protected Boolean ignoreHealFree { get; }
	protected Boolean isHpRatio { get; }
	public override SourceApplyWay applyWay { get; }
	public FP healScale { get; }

	// RVA: 0x1e1ee8c VA: 0x7594436e8c
	protected Boolean get_isCont() { }
	// RVA: 0x1e1eef4 VA: 0x7594436ef4
	protected Boolean get_ignoreHealFree() { }
	// RVA: 0x1e1ef5c VA: 0x7594436f5c
	protected Boolean get_isHpRatio() { }
	// RVA: 0x1e1efc4 VA: 0x7594436fc4
	public override SourceApplyWay get_applyWay() { }
	// RVA: 0x1e1f028 VA: 0x7594437028
	public FP get_healScale() { }
	// RVA: 0x1e1f0c8 VA: 0x75944370c8
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e1f154 VA: 0x7594437154
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1e1e74c VA: 0x759443674c
	public Void ApplyHealScale(FP healScale, Boolean overwrite, Boolean createNewNode) { }
	// RVA: 0x1e1e894 VA: 0x7594436894
	public Void ApplyElementHealScale(FP elementHealScale, Boolean overwrite) { }
	// RVA: 0x1e1f1d4 VA: 0x75944371d4
	public Void ApplyElementHealScaleForElementHealNode(FP elementHealScale) { }
	// RVA: 0x1e1e0dc VA: 0x75944360dc
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e1f290 VA: 0x7594437290
	protected virtual ApplyHeal NewHealNode(FP healScale) { }
	// RVA: 0x1e1f380 VA: 0x7594437380
	protected virtual ApplyElementHeal NewElementHealNode() { }
	// RVA: 0x1e1f454 VA: 0x7594437454
	protected override Boolean CheckIsDamageOrHealSource() { }
	// RVA: 0x1e1f4bc VA: 0x75944374bc
	protected override ActionPurposeMask GeneratePurposeMask() { }
	// RVA: 0x1e1f530 VA: 0x7594437530
	public Void .ctor() { }
	// RVA: 0x1e1f63c VA: 0x759443763c
	private SourceApplyWay <>xLuaBaseProxy_get_applyWay() { }
	// RVA: 0x1e1f644 VA: 0x7594437644
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e1f66c VA: 0x759443766c
	private Boolean <>xLuaBaseProxy_CheckIsDamageOrHealSource() { }
	// RVA: 0x1e1f674 VA: 0x7594437674
	private ActionPurposeMask <>xLuaBaseProxy_GeneratePurposeMask() { }
}
```