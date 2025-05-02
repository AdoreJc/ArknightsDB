# ActMultiV3PrepareMainSquadPanelViewModel

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `String <activityId>k__BackingField`

- `Boolean <stepEnd>k__BackingField`

- `Boolean <reverse>k__BackingField`

- `Boolean <playNoPickBanner>k__BackingField`

- `String <pickStepName>k__BackingField`

- `Boolean <showReserveList>k__BackingField`

- `SysAllocModel <sysAllocModel>k__BackingField`

- `Int32 <squadCntMax>k__BackingField`

- `Int32 <squadCntMin>k__BackingField`

- `Int32 <tempHelpSeq>k__BackingField`

- `SkillModel skillEquipModel`

- `CheckModel checkModel`

- `ActMultiV3PrepareMainSmallCharCardModel <emptySmallChar>k__BackingField`

- `ActMultiV3PrepareMainCharCardModel <emptySquadChar>k__BackingField`

- `ActMultiV3PrepareMainSkillAndModuleCharCardModel <emptySkillSelectChar>k__BackingField`

- `ActMultiV3PrepareMainSquadProc m_currProc`


## Properties

- `String activityId`

- `Boolean stepEnd`

- `Boolean reverse`

- `Boolean playNoPickBanner`

- `String pickStepName`

- `Boolean showReserveList`

- `SysAllocModel sysAllocModel`

- `ActMultiV3PrepareMainSquadProc currProc`

- `Int32 squadCntMax`

- `Int32 squadCntMin`

- `Int32 tempHelpSeq`

- `ActMultiV3PrepareMainSmallCharCardModel emptySmallChar`

- `ActMultiV3PrepareMainCharCardModel emptySquadChar`

- `ActMultiV3PrepareMainSkillAndModuleCharCardModel emptySkillSelectChar`


## Methods

- `String get_activityId()`

- `Void set_activityId(String)`

- `Boolean get_stepEnd()`

- `Void set_stepEnd(Boolean)`

- `Boolean get_reverse()`

- `Void set_reverse(Boolean)`

- `Boolean get_playNoPickBanner()`

- `Void set_playNoPickBanner(Boolean)`

- `String get_pickStepName()`

- `Void set_pickStepName(String)`

- `Void set_squad(List`1)`

- `Void set_reserveList(List`1)`

- `Boolean get_showReserveList()`

- `Void set_showReserveList(Boolean)`

- `SysAllocModel get_sysAllocModel()`

- `Void set_sysAllocModel(SysAllocModel)`

- `ActMultiV3PrepareMainSquadProc get_currProc()`

- `Int32 get_squadCntMax()`

- `Void set_squadCntMax(Int32)`

- `Int32 get_squadCntMin()`

- `Void set_squadCntMin(Int32)`

- `Int32 get_tempHelpSeq()`

- `Void set_tempHelpSeq(Int32)`

- `ActMultiV3PrepareMainSmallCharCardModel get_emptySmallChar()`

- `Void set_emptySmallChar(ActMultiV3PrepareMainSmallCharCardModel)`

- `ActMultiV3PrepareMainCharCardModel get_emptySquadChar()`

- `Void set_emptySquadChar(ActMultiV3PrepareMainCharCardModel)`

- `ActMultiV3PrepareMainSkillAndModuleCharCardModel get_emptySkillSelectChar()`

- `Void set_emptySkillSelectChar(ActMultiV3PrepareMainSkillAndModuleCharCardModel)`

- `Void LoadStableData(String)`

- `Void Reset()`

- `Void Update()`

- `Int32 _GetMapSquadMax(ActMultiV3Data, Int32)`

- `Void _AddToReserveList(Int32, ActMultiV3PrepareMainSmallCharCardModel, Boolean)`

- `Void _FillList(IList`1, T, Int32)`

- `Int32 _FindPosInSquad(Int32)`

- `Boolean _AddToSquad(ActMultiV3PrepareMainSmallCharCardModel, Int32)`

- `Void CheckReserveVisible()`

- `Boolean SetCharInSquad(Int32, Boolean)`

- `Boolean CheckInSquad(Int32)`

- `Boolean HasEmptyPos()`

- `Void _LoadSkillProcDataBySquad()`

- `Void SetCharSkill(Int32, String)`

- `Void SetCharEquip(Int32, String)`

- `Void SwitchShowSkill()`

- `Boolean _TryFindSkillSelectModelByInstId(Int32, out)`

- `Void _SaveSquadSkillEquipInfo()`

- `Void _FillSlot(ActMultiV3PrepareMainSmallCharCardModel, TeamSquadSlotParam)`

- `Boolean JumpToEnd()`

- `Boolean ToNextProc()`

- `Boolean ToPreProc()`

- `Boolean _SwitchProc(Int32)`

- `Void _UpdateCheck()`

- `ActMultiV3IdentityType _CheckCharType(STPlayerStatus, Int32)`

- `Int32 _CompareChar(ActMultiV3PrepareMainSquadPanelReserveCharCardModel, ActMultiV3PrepareMainSquadPanelReserveCharCardModel)`

- `Int32 _GetIdentityPrior(ActMultiV3IdentityType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainSquadPanelViewModel : IHotfixable
{
	private String <activityId>k__BackingField; // 0x10
	private Boolean <stepEnd>k__BackingField; // 0x18
	private Boolean <reverse>k__BackingField; // 0x19
	private Boolean <playNoPickBanner>k__BackingField; // 0x1a
	private String <pickStepName>k__BackingField; // 0x20
	private List`1 <squad>k__BackingField; // 0x28
	private List`1 <reserveList>k__BackingField; // 0x30
	private Boolean <showReserveList>k__BackingField; // 0x38
	private SysAllocModel <sysAllocModel>k__BackingField; // 0x40
	private Int32 <squadCntMax>k__BackingField; // 0x48
	private Int32 <squadCntMin>k__BackingField; // 0x4c
	private Int32 <tempHelpSeq>k__BackingField; // 0x50
	public SkillModel skillEquipModel; // 0x58
	public CheckModel checkModel; // 0x68
	private ActMultiV3PrepareMainSmallCharCardModel <emptySmallChar>k__BackingField; // 0x78
	private ActMultiV3PrepareMainCharCardModel <emptySquadChar>k__BackingField; // 0x80
	private ActMultiV3PrepareMainSkillAndModuleCharCardModel <emptySkillSelectChar>k__BackingField; // 0x88
	public const Int32 SQUAD_COUNT_MAX; // 0x0
	public const Int32 SQUAD_COUNT_MIN; // 0x0
	private ActMultiV3PrepareMainSquadProc m_currProc; // 0x90
	private Dictionary`2 m_modelDict; // 0x98
	private List`1 m_squadForSvr; // 0xa0
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_set_activityId; // 0x8
	private static DelegateBridge __Hotfix0_get_stepEnd; // 0x10
	private static DelegateBridge __Hotfix0_set_stepEnd; // 0x18
	private static DelegateBridge __Hotfix0_get_reverse; // 0x20
	private static DelegateBridge __Hotfix0_set_reverse; // 0x28
	private static DelegateBridge __Hotfix0_get_playNoPickBanner; // 0x30
	private static DelegateBridge __Hotfix0_set_playNoPickBanner; // 0x38
	private static DelegateBridge __Hotfix0_get_pickStepName; // 0x40
	private static DelegateBridge __Hotfix0_set_pickStepName; // 0x48
	private static DelegateBridge __Hotfix0_get_squad; // 0x50
	private static DelegateBridge __Hotfix0_set_squad; // 0x58
	private static DelegateBridge __Hotfix0_get_reserveList; // 0x60
	private static DelegateBridge __Hotfix0_set_reserveList; // 0x68
	private static DelegateBridge __Hotfix0_get_showReserveList; // 0x70
	private static DelegateBridge __Hotfix0_set_showReserveList; // 0x78
	private static DelegateBridge __Hotfix0_get_sysAllocModel; // 0x80
	private static DelegateBridge __Hotfix0_set_sysAllocModel; // 0x88
	private static DelegateBridge __Hotfix0_get_currProc; // 0x90
	private static DelegateBridge __Hotfix0_get_squadCntMax; // 0x98
	private static DelegateBridge __Hotfix0_set_squadCntMax; // 0xa0
	private static DelegateBridge __Hotfix0_get_squadCntMin; // 0xa8
	private static DelegateBridge __Hotfix0_set_squadCntMin; // 0xb0
	private static DelegateBridge __Hotfix0_get_tempHelpSeq; // 0xb8
	private static DelegateBridge __Hotfix0_set_tempHelpSeq; // 0xc0
	private static DelegateBridge __Hotfix0_get_emptySmallChar; // 0xc8
	private static DelegateBridge __Hotfix0_set_emptySmallChar; // 0xd0
	private static DelegateBridge __Hotfix0_get_emptySquadChar; // 0xd8
	private static DelegateBridge __Hotfix0_set_emptySquadChar; // 0xe0
	private static DelegateBridge __Hotfix0_get_emptySkillSelectChar; // 0xe8
	private static DelegateBridge __Hotfix0_set_emptySkillSelectChar; // 0xf0
	private static DelegateBridge __Hotfix0_LoadStableData; // 0xf8
	private static DelegateBridge __Hotfix0_Reset; // 0x100
	private static DelegateBridge __Hotfix0_Update; // 0x108
	private static DelegateBridge __Hotfix0__GetMapSquadMax; // 0x110
	private static DelegateBridge __Hotfix0__AddToReserveList; // 0x118
	private static DelegateBridge __Hotfix0__FillList; // 0x120
	private static DelegateBridge __Hotfix0__FindPosInSquad; // 0x128
	private static DelegateBridge __Hotfix0__AddToSquad; // 0x130
	private static DelegateBridge __Hotfix0_CheckReserveVisible; // 0x138
	private static DelegateBridge __Hotfix0_SetCharInSquad; // 0x140
	private static DelegateBridge __Hotfix0_CheckInSquad; // 0x148
	private static DelegateBridge __Hotfix0_HasEmptyPos; // 0x150
	private static DelegateBridge __Hotfix0__LoadSkillProcDataBySquad; // 0x158
	private static DelegateBridge __Hotfix0_SetCharSkill; // 0x160
	private static DelegateBridge __Hotfix0_SetCharEquip; // 0x168
	private static DelegateBridge __Hotfix0_SwitchShowSkill; // 0x170
	private static DelegateBridge __Hotfix0__TryFindSkillSelectModelByInstId; // 0x178
	private static DelegateBridge __Hotfix0__SaveSquadSkillEquipInfo; // 0x180
	private static DelegateBridge __Hotfix0_ConfirmSquadDataForSvr; // 0x188
	private static DelegateBridge __Hotfix0__GenSvrSquadData; // 0x190
	private static DelegateBridge __Hotfix0__FillSlot; // 0x198
	private static DelegateBridge __Hotfix0_JumpToEnd; // 0x1a0
	private static DelegateBridge __Hotfix0_ToNextProc; // 0x1a8
	private static DelegateBridge __Hotfix0_ToPreProc; // 0x1b0
	private static DelegateBridge __Hotfix0__SwitchProc; // 0x1b8
	private static DelegateBridge __Hotfix0__UpdateCheck; // 0x1c0
	private static DelegateBridge __Hotfix0__CheckCharType; // 0x1c8
	private static DelegateBridge __Hotfix0__CompareChar; // 0x1d0
	private static DelegateBridge __Hotfix0__GetIdentityPrior; // 0x1d8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1e0

	public String activityId { get; set; }
	public Boolean stepEnd { get; set; }
	public Boolean reverse { get; set; }
	public Boolean playNoPickBanner { get; set; }
	public String pickStepName { get; set; }
	public List`1 squad { get; set; }
	public List`1 reserveList { get; set; }
	public Boolean showReserveList { get; set; }
	public SysAllocModel sysAllocModel { get; set; }
	public ActMultiV3PrepareMainSquadProc currProc { get; }
	public Int32 squadCntMax { get; set; }
	public Int32 squadCntMin { get; set; }
	public Int32 tempHelpSeq { get; set; }
	public ActMultiV3PrepareMainSmallCharCardModel emptySmallChar { get; set; }
	public ActMultiV3PrepareMainCharCardModel emptySquadChar { get; set; }
	public ActMultiV3PrepareMainSkillAndModuleCharCardModel emptySkillSelectChar { get; set; }

	// RVA: 0x3171278 VA: 0x7595789278
	public String get_activityId() { }
	// RVA: 0x31712e0 VA: 0x75957892e0
	private Void set_activityId(String value) { }
	// RVA: 0x3171364 VA: 0x7595789364
	public Boolean get_stepEnd() { }
	// RVA: 0x31713cc VA: 0x75957893cc
	private Void set_stepEnd(Boolean value) { }
	// RVA: 0x317144c VA: 0x759578944c
	public Boolean get_reverse() { }
	// RVA: 0x31714b4 VA: 0x75957894b4
	private Void set_reverse(Boolean value) { }
	// RVA: 0x3170f94 VA: 0x7595788f94
	public Boolean get_playNoPickBanner() { }
	// RVA: 0x3171534 VA: 0x7595789534
	private Void set_playNoPickBanner(Boolean value) { }
	// RVA: 0x31715b4 VA: 0x75957895b4
	public String get_pickStepName() { }
	// RVA: 0x317161c VA: 0x759578961c
	private Void set_pickStepName(String value) { }
	// RVA: 0x31716a0 VA: 0x75957896a0
	public List`1 get_squad() { }
	// RVA: 0x3171708 VA: 0x7595789708
	private Void set_squad(List`1 value) { }
	// RVA: 0x317178c VA: 0x759578978c
	public List`1 get_reserveList() { }
	// RVA: 0x31717f4 VA: 0x75957897f4
	private Void set_reserveList(List`1 value) { }
	// RVA: 0x3171878 VA: 0x7595789878
	public Boolean get_showReserveList() { }
	// RVA: 0x31718e0 VA: 0x75957898e0
	private Void set_showReserveList(Boolean value) { }
	// RVA: 0x3170ffc VA: 0x7595788ffc
	public SysAllocModel get_sysAllocModel() { }
	// RVA: 0x3171960 VA: 0x7595789960
	private Void set_sysAllocModel(SysAllocModel value) { }
	// RVA: 0x316ddac VA: 0x7595785dac
	public ActMultiV3PrepareMainSquadProc get_currProc() { }
	// RVA: 0x31719e4 VA: 0x75957899e4
	public Int32 get_squadCntMax() { }
	// RVA: 0x3171a4c VA: 0x7595789a4c
	private Void set_squadCntMax(Int32 value) { }
	// RVA: 0x3171ac8 VA: 0x7595789ac8
	public Int32 get_squadCntMin() { }
	// RVA: 0x3171b30 VA: 0x7595789b30
	private Void set_squadCntMin(Int32 value) { }
	// RVA: 0x3171bac VA: 0x7595789bac
	public Int32 get_tempHelpSeq() { }
	// RVA: 0x3171c14 VA: 0x7595789c14
	private Void set_tempHelpSeq(Int32 value) { }
	// RVA: 0x3171c90 VA: 0x7595789c90
	public ActMultiV3PrepareMainSmallCharCardModel get_emptySmallChar() { }
	// RVA: 0x3171cf8 VA: 0x7595789cf8
	private Void set_emptySmallChar(ActMultiV3PrepareMainSmallCharCardModel value) { }
	// RVA: 0x3171d7c VA: 0x7595789d7c
	public ActMultiV3PrepareMainCharCardModel get_emptySquadChar() { }
	// RVA: 0x3171de4 VA: 0x7595789de4
	private Void set_emptySquadChar(ActMultiV3PrepareMainCharCardModel value) { }
	// RVA: 0x3171e68 VA: 0x7595789e68
	public ActMultiV3PrepareMainSkillAndModuleCharCardModel get_emptySkillSelectChar() { }
	// RVA: 0x3171ed0 VA: 0x7595789ed0
	private Void set_emptySkillSelectChar(ActMultiV3PrepareMainSkillAndModuleCharCardModel value) { }
	// RVA: 0x316f768 VA: 0x7595787768
	public Void LoadStableData(String actId) { }
	// RVA: 0x316f128 VA: 0x7595787128
	public Void Reset() { }
	// RVA: 0x316e3c4 VA: 0x75957863c4
	public Void Update() { }
	// RVA: 0x3171f5c VA: 0x7595789f5c
	private Int32 _GetMapSquadMax(ActMultiV3Data actData, Int32 defaultNum) { }
	// RVA: 0x31720ac VA: 0x759578a0ac
	private Void _AddToReserveList(Int32 instId, ActMultiV3PrepareMainSmallCharCardModel viewModel, Boolean showInReserve) { }
	// RVA: 0x VA: 0x0
	private Void _FillList(IList`1 list, T item, Int32 count) { }
	// RVA: 0x31722f4 VA: 0x759578a2f4
	private Int32 _FindPosInSquad(Int32 instId) { }
	// RVA: 0x3172418 VA: 0x759578a418
	private Boolean _AddToSquad(ActMultiV3PrepareMainSmallCharCardModel smallChrModel, Int32 pos) { }
	// RVA: 0x3170484 VA: 0x7595788484
	public Void CheckReserveVisible() { }
	// RVA: 0x316fd58 VA: 0x7595787d58
	public Boolean SetCharInSquad(Int32 instId, Boolean inSquad) { }
	// RVA: 0x31702cc VA: 0x75957882cc
	public Boolean CheckInSquad(Int32 instId) { }
	// RVA: 0x3170358 VA: 0x7595788358
	public Boolean HasEmptyPos() { }
	// RVA: 0x3172af4 VA: 0x759578aaf4
	private Void _LoadSkillProcDataBySquad() { }
	// RVA: 0x31709bc VA: 0x75957889bc
	public Void SetCharSkill(Int32 instId, String skillId) { }
	// RVA: 0x3170b4c VA: 0x7595788b4c
	public Void SetCharEquip(Int32 instId, String equipId) { }
	// RVA: 0x3170cb8 VA: 0x7595788cb8
	public Void SwitchShowSkill() { }
	// RVA: 0x3172da0 VA: 0x759578ada0
	private Boolean _TryFindSkillSelectModelByInstId(Int32 instId, out ActMultiV3PrepareMainSkillAndModuleCharCardModel outModel) { }
	// RVA: 0x3172ef0 VA: 0x759578aef0
	private Void _SaveSquadSkillEquipInfo() { }
	// RVA: 0x3170878 VA: 0x7595788878
	public List`1 ConfirmSquadDataForSvr() { }
	// RVA: 0x317309c VA: 0x759578b09c
	private List`1 _GenSvrSquadData(Int32 excludeInstId) { }
	// RVA: 0x3173388 VA: 0x759578b388
	private Void _FillSlot(ActMultiV3PrepareMainSmallCharCardModel chr, TeamSquadSlotParam slot) { }
	// RVA: 0x3170788 VA: 0x7595788788
	public Boolean JumpToEnd() { }
	// RVA: 0x3170104 VA: 0x7595788104
	public Boolean ToNextProc() { }
	// RVA: 0x316f644 VA: 0x7595787644
	public Boolean ToPreProc() { }
	// RVA: 0x3173594 VA: 0x759578b594
	private Boolean _SwitchProc(Int32 offset) { }
	// RVA: 0x3172580 VA: 0x759578a580
	private Void _UpdateCheck() { }
	// RVA: 0x3173738 VA: 0x759578b738
	private ActMultiV3IdentityType _CheckCharType(STPlayerStatus player, Int32 instId) { }
	// RVA: 0x3173818 VA: 0x759578b818
	private Int32 _CompareChar(ActMultiV3PrepareMainSquadPanelReserveCharCardModel a, ActMultiV3PrepareMainSquadPanelReserveCharCardModel b) { }
	// RVA: 0x31739e4 VA: 0x759578b9e4
	private Int32 _GetIdentityPrior(ActMultiV3IdentityType identityType) { }
	// RVA: 0x3173a7c VA: 0x759578ba7c
	public Void .ctor() { }
}
```