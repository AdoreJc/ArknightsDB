# AdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _targetSide`

- `MotionMask _targetMotion`

- `EntityCategory _targetCategory`

- `FilterType _postFilter`

- `Boolean _ignoreTargetFree`

- `Boolean _onlyIgnoreSomeOfTargetFreeCase`

- `AbnormalFlag _abnormalFlag`

- `AbnormalCombo _abnormalCombo`

- `Boolean _ignoreAllyTargetFree`

- `Boolean _ignoreHealFree`

- `Boolean _forceIgnoreCamouflage`

- `Boolean _needProfessionMask`

- `ProfessionCategory _professionMask`

- `Boolean _limitTargetNum`

- `String _maxTargetKey`

- `Int32 _maxNum`

- `Boolean _excludeOwner`

- `Boolean _sortByTauntAtLast`

- `Boolean _ignoreHitRange`

- `Int32 m_maxTargetNum`


## Properties

- `Boolean limitTargetNum`

- `Int32 maxTargetNum`

- `Boolean needProfessionMask`

- `Boolean filterTypeAllAndLimitTargetNum`

- `Boolean isAlly`

- `Boolean dontExcludeOwner`


## Methods

- `Boolean get_limitTargetNum()`

- `Int32 get_maxTargetNum()`

- `Boolean get_needProfessionMask()`

- `Boolean get_filterTypeAllAndLimitTargetNum()`

- `Boolean get_isAlly()`

- `Boolean get_dontExcludeOwner()`

- `Void AddExcludeTarget(Entity)`

- `Void ClearExcludeTarget()`

- `Boolean <>xLuaBaseProxy_get_ignoreAllyTargetFree()`

- `Boolean <>xLuaBaseProxy_get_ignoreHealFree()`

- `Boolean <>xLuaBaseProxy_get_forceIgnoreCamouflage()`

- `Boolean <>xLuaBaseProxy_get_ignoreHitRange()`

- `Boolean <>xLuaBaseProxy_get_onlyIgnoreSomeOfTargetFreeCase()`

- `AbnormalFlag <>xLuaBaseProxy_get_abnormalFlag()`

- `AbnormalCombo <>xLuaBaseProxy_get_abnormalCombo()`

- `ProfessionCategory <>xLuaBaseProxy_get_professionMask()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_Awake()`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelector : RangeSelector, IExcludeTarget
{
	private SideType _targetSide; // 0xa0
	private MotionMask _targetMotion; // 0xa4
	private EntityCategory _targetCategory; // 0xa8
	protected FilterType _postFilter; // 0xac
	private Boolean _ignoreTargetFree; // 0xb0
	public Boolean _onlyIgnoreSomeOfTargetFreeCase; // 0xb1
	public AbnormalFlag _abnormalFlag; // 0xb4
	public AbnormalCombo _abnormalCombo; // 0xb8
	private Boolean _ignoreAllyTargetFree; // 0xbc
	private Boolean _ignoreHealFree; // 0xbd
	private Boolean _forceIgnoreCamouflage; // 0xbe
	private Boolean _needProfessionMask; // 0xbf
	public ProfessionCategory _professionMask; // 0xc0
	private Boolean _limitTargetNum; // 0xc4
	private String _maxTargetKey; // 0xc8
	private Int32 _maxNum; // 0xd0
	protected Boolean _excludeOwner; // 0xd4
	protected Boolean _sortByTauntAtLast; // 0xd5
	private Boolean _ignoreHitRange; // 0xd6
	private Int32 m_maxTargetNum; // 0xd8
	private ListSet`1 m_excludeTargetList; // 0xe0
	private static DelegateBridge __Hotfix0_get_limitTargetNum; // 0x0
	private static DelegateBridge __Hotfix0_get_targetSide; // 0x8
	private static DelegateBridge __Hotfix0_get_targetMotion; // 0x10
	private static DelegateBridge __Hotfix0_get_targetCategory; // 0x18
	private static DelegateBridge __Hotfix0_get_maxTargetNum; // 0x20
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x28
	private static DelegateBridge __Hotfix0_get_ignoreAllyTargetFree; // 0x30
	private static DelegateBridge __Hotfix0_get_ignoreHealFree; // 0x38
	private static DelegateBridge __Hotfix0_get_forceIgnoreCamouflage; // 0x40
	private static DelegateBridge __Hotfix0_get_ignoreHitRange; // 0x48
	private static DelegateBridge __Hotfix0_get_onlyIgnoreSomeOfTargetFreeCase; // 0x50
	private static DelegateBridge __Hotfix0_get_needProfessionMask; // 0x58
	private static DelegateBridge __Hotfix0_get_abnormalFlag; // 0x60
	private static DelegateBridge __Hotfix0_get_abnormalCombo; // 0x68
	private static DelegateBridge __Hotfix0_get_professionMask; // 0x70
	private static DelegateBridge __Hotfix0_get_filterTypeAllAndLimitTargetNum; // 0x78
	private static DelegateBridge __Hotfix0_get_isAlly; // 0x80
	private static DelegateBridge __Hotfix0_get_dontExcludeOwner; // 0x88
	private static DelegateBridge __Hotfix0_Reset; // 0x90
	private static DelegateBridge __Hotfix0_SetData; // 0x98
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0xa0
	private static DelegateBridge __Hotfix1_OnPostFilter; // 0xa8
	private static DelegateBridge __Hotfix0_Awake; // 0xb0
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0xb8
	private static DelegateBridge __Hotfix0_AddExcludeTarget; // 0xc0
	private static DelegateBridge __Hotfix0_ClearExcludeTarget; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public Boolean limitTargetNum { get; }
	public override SideType targetSide { get; }
	public override MotionMask targetMotion { get; }
	public override EntityCategory targetCategory { get; }
	protected Int32 maxTargetNum { get; }
	public override Boolean ignoreTargetFree { get; }
	protected override Boolean ignoreAllyTargetFree { get; }
	protected override Boolean ignoreHealFree { get; }
	protected override Boolean forceIgnoreCamouflage { get; }
	protected override Boolean ignoreHitRange { get; }
	protected override Boolean onlyIgnoreSomeOfTargetFreeCase { get; }
	protected Boolean needProfessionMask { get; }
	protected override AbnormalFlag abnormalFlag { get; }
	protected override AbnormalCombo abnormalCombo { get; }
	protected override ProfessionCategory professionMask { get; }
	private Boolean filterTypeAllAndLimitTargetNum { get; }
	protected Boolean isAlly { get; }
	protected Boolean dontExcludeOwner { get; }

	// RVA: 0x1b9810c VA: 0x75941b010c
	public Boolean get_limitTargetNum() { }
	// RVA: 0x1b98174 VA: 0x75941b0174
	public override SideType get_targetSide() { }
	// RVA: 0x1b981dc VA: 0x75941b01dc
	public override MotionMask get_targetMotion() { }
	// RVA: 0x1b98244 VA: 0x75941b0244
	public override EntityCategory get_targetCategory() { }
	// RVA: 0x1b982ac VA: 0x75941b02ac
	protected Int32 get_maxTargetNum() { }
	// RVA: 0x1b98314 VA: 0x75941b0314
	public override Boolean get_ignoreTargetFree() { }
	// RVA: 0x1b9837c VA: 0x75941b037c
	protected override Boolean get_ignoreAllyTargetFree() { }
	// RVA: 0x1b983e4 VA: 0x75941b03e4
	protected override Boolean get_ignoreHealFree() { }
	// RVA: 0x1b9844c VA: 0x75941b044c
	protected override Boolean get_forceIgnoreCamouflage() { }
	// RVA: 0x1b984b4 VA: 0x75941b04b4
	protected override Boolean get_ignoreHitRange() { }
	// RVA: 0x1b9853c VA: 0x75941b053c
	protected override Boolean get_onlyIgnoreSomeOfTargetFreeCase() { }
	// RVA: 0x1b985bc VA: 0x75941b05bc
	protected Boolean get_needProfessionMask() { }
	// RVA: 0x1b98624 VA: 0x75941b0624
	protected override AbnormalFlag get_abnormalFlag() { }
	// RVA: 0x1b9868c VA: 0x75941b068c
	protected override AbnormalCombo get_abnormalCombo() { }
	// RVA: 0x1b986f4 VA: 0x75941b06f4
	protected override ProfessionCategory get_professionMask() { }
	// RVA: 0x1b98770 VA: 0x75941b0770
	private Boolean get_filterTypeAllAndLimitTargetNum() { }
	// RVA: 0x1b987f0 VA: 0x75941b07f0
	protected Boolean get_isAlly() { }
	// RVA: 0x1b98860 VA: 0x75941b0860
	protected Boolean get_dontExcludeOwner() { }
	// RVA: 0x1b988d0 VA: 0x75941b08d0
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1b98a08 VA: 0x75941b0a08
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1b98acc VA: 0x75941b0acc
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b98d3c VA: 0x75941b0d3c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b98db4 VA: 0x75941b0db4
	protected override Void Awake() { }
	// RVA: 0x1b98e3c VA: 0x75941b0e3c
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1b98f04 VA: 0x75941b0f04
	public Void AddExcludeTarget(Entity target) { }
	// RVA: 0x1b98980 VA: 0x75941b0980
	public Void ClearExcludeTarget() { }
	// RVA: 0x1b98fa4 VA: 0x75941b0fa4
	public Void .ctor() { }
	// RVA: 0x1b990c0 VA: 0x75941b10c0
	private Boolean <>xLuaBaseProxy_get_ignoreAllyTargetFree() { }
	// RVA: 0x1b990c8 VA: 0x75941b10c8
	private Boolean <>xLuaBaseProxy_get_ignoreHealFree() { }
	// RVA: 0x1b990d0 VA: 0x75941b10d0
	private Boolean <>xLuaBaseProxy_get_forceIgnoreCamouflage() { }
	// RVA: 0x1b990d8 VA: 0x75941b10d8
	private Boolean <>xLuaBaseProxy_get_ignoreHitRange() { }
	// RVA: 0x1b990e0 VA: 0x75941b10e0
	private Boolean <>xLuaBaseProxy_get_onlyIgnoreSomeOfTargetFreeCase() { }
	// RVA: 0x1b990e8 VA: 0x75941b10e8
	private AbnormalFlag <>xLuaBaseProxy_get_abnormalFlag() { }
	// RVA: 0x1b990f0 VA: 0x75941b10f0
	private AbnormalCombo <>xLuaBaseProxy_get_abnormalCombo() { }
	// RVA: 0x1b990f8 VA: 0x75941b10f8
	private ProfessionCategory <>xLuaBaseProxy_get_professionMask() { }
	// RVA: 0x1b99100 VA: 0x75941b1100
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1b99108 VA: 0x75941b1108
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1b99110 VA: 0x75941b1110
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x1b99118 VA: 0x75941b1118
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```