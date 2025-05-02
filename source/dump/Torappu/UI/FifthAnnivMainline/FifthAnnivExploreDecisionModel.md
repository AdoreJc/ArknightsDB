# FifthAnnivExploreDecisionModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `String m_selectPlanId`

- `FifthAnnivExploreLogModel m_logModel`

- `DecisionNodeType <decisionType>k__BackingField`

- `DecisionStatus <currStatus>k__BackingField`

- `Int32 <enterSeqNum>k__BackingField`

- `Int32 <switchPlanSeqNum>k__BackingField`

- `Boolean <inExploreDetailState>k__BackingField`


## Properties

- `DecisionNodeType decisionType`

- `DecisionStatus currStatus`

- `Int32 enterSeqNum`

- `Int32 switchPlanSeqNum`

- `Boolean inExploreDetailState`

- `FifthAnnivExploreLogModel logModel`


## Methods

- `DecisionNodeType get_decisionType()`

- `Void set_decisionType(DecisionNodeType)`

- `DecisionStatus get_currStatus()`

- `Void set_currStatus(DecisionStatus)`

- `Int32 get_enterSeqNum()`

- `Void set_enterSeqNum(Int32)`

- `Int32 get_switchPlanSeqNum()`

- `Void set_switchPlanSeqNum(Int32)`

- `Boolean get_inExploreDetailState()`

- `Void set_inExploreDetailState(Boolean)`

- `FifthAnnivExploreLogModel get_logModel()`

- `FifthAnnivExploreEventPlanModel GetPrevEventModel()`

- `Void JumpToEvtRetStatus(ExploreSelectEventOptionResponse)`

- `Void JumpToPrevEvent()`

- `FifthAnnivExploreEventPlanModel GetNextEventModel()`

- `Void JumpToNextEvent()`

- `FifthAnnivExplorePlanModel GetCurrPlanModel()`

- `Boolean IsInEvtDecision()`

- `Void BackToEvtInfo()`

- `Void JumpToPlanStatus(String)`

- `Void SelectOption(String)`

- `Void SetInExploreDetailState(Boolean)`

- `Void InitData()`

- `Void _InitEventPlanList(PlayerExploreGameContextNode)`

- `Void _InitTargetPlanList(String, List`1)`

- `Int32 _GetCurrPlanIdx()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreDecisionModel : IHotfixable
{
	private List`1 m_planList; // 0x10
	private String m_selectPlanId; // 0x18
	private FifthAnnivExploreLogModel m_logModel; // 0x20
	private DecisionNodeType <decisionType>k__BackingField; // 0x28
	private DecisionStatus <currStatus>k__BackingField; // 0x2c
	private Int32 <enterSeqNum>k__BackingField; // 0x30
	private Int32 <switchPlanSeqNum>k__BackingField; // 0x34
	private Boolean <inExploreDetailState>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_decisionType; // 0x0
	private static DelegateBridge __Hotfix0_set_decisionType; // 0x8
	private static DelegateBridge __Hotfix0_get_currStatus; // 0x10
	private static DelegateBridge __Hotfix0_set_currStatus; // 0x18
	private static DelegateBridge __Hotfix0_get_enterSeqNum; // 0x20
	private static DelegateBridge __Hotfix0_set_enterSeqNum; // 0x28
	private static DelegateBridge __Hotfix0_get_switchPlanSeqNum; // 0x30
	private static DelegateBridge __Hotfix0_set_switchPlanSeqNum; // 0x38
	private static DelegateBridge __Hotfix0_get_inExploreDetailState; // 0x40
	private static DelegateBridge __Hotfix0_set_inExploreDetailState; // 0x48
	private static DelegateBridge __Hotfix0_get_planList; // 0x50
	private static DelegateBridge __Hotfix0_get_logModel; // 0x58
	private static DelegateBridge __Hotfix0_GetPrevEventModel; // 0x60
	private static DelegateBridge __Hotfix0_JumpToEvtRetStatus; // 0x68
	private static DelegateBridge __Hotfix0_JumpToPrevEvent; // 0x70
	private static DelegateBridge __Hotfix0_GetNextEventModel; // 0x78
	private static DelegateBridge __Hotfix0_JumpToNextEvent; // 0x80
	private static DelegateBridge __Hotfix0_GetCurrPlanModel; // 0x88
	private static DelegateBridge __Hotfix0_IsInEvtDecision; // 0x90
	private static DelegateBridge __Hotfix0_BackToEvtInfo; // 0x98
	private static DelegateBridge __Hotfix0_JumpToPlanStatus; // 0xa0
	private static DelegateBridge __Hotfix0_SelectOption; // 0xa8
	private static DelegateBridge __Hotfix0_SetInExploreDetailState; // 0xb0
	private static DelegateBridge __Hotfix0_InitData; // 0xb8
	private static DelegateBridge __Hotfix0__InitEventPlanList; // 0xc0
	private static DelegateBridge __Hotfix0__InitTargetPlanList; // 0xc8
	private static DelegateBridge __Hotfix0__GetCurrPlanIdx; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public DecisionNodeType decisionType { get; set; }
	public DecisionStatus currStatus { get; set; }
	public Int32 enterSeqNum { get; set; }
	public Int32 switchPlanSeqNum { get; set; }
	public Boolean inExploreDetailState { get; set; }
	public List`1 planList { get; }
	public FifthAnnivExploreLogModel logModel { get; }

	// RVA: 0x290d194 VA: 0x7594f25194
	public DecisionNodeType get_decisionType() { }
	// RVA: 0x290d1fc VA: 0x7594f251fc
	private Void set_decisionType(DecisionNodeType value) { }
	// RVA: 0x290d278 VA: 0x7594f25278
	public DecisionStatus get_currStatus() { }
	// RVA: 0x290d2e0 VA: 0x7594f252e0
	private Void set_currStatus(DecisionStatus value) { }
	// RVA: 0x290d35c VA: 0x7594f2535c
	public Int32 get_enterSeqNum() { }
	// RVA: 0x290d3c4 VA: 0x7594f253c4
	private Void set_enterSeqNum(Int32 value) { }
	// RVA: 0x290d440 VA: 0x7594f25440
	public Int32 get_switchPlanSeqNum() { }
	// RVA: 0x290d4a8 VA: 0x7594f254a8
	private Void set_switchPlanSeqNum(Int32 value) { }
	// RVA: 0x290d524 VA: 0x7594f25524
	public Boolean get_inExploreDetailState() { }
	// RVA: 0x290d58c VA: 0x7594f2558c
	private Void set_inExploreDetailState(Boolean value) { }
	// RVA: 0x290d60c VA: 0x7594f2560c
	public List`1 get_planList() { }
	// RVA: 0x290d674 VA: 0x7594f25674
	public FifthAnnivExploreLogModel get_logModel() { }
	// RVA: 0x290d6dc VA: 0x7594f256dc
	public FifthAnnivExploreEventPlanModel GetPrevEventModel() { }
	// RVA: 0x290d8f0 VA: 0x7594f258f0
	public Void JumpToEvtRetStatus(ExploreSelectEventOptionResponse response) { }
	// RVA: 0x290db0c VA: 0x7594f25b0c
	public Void JumpToPrevEvent() { }
	// RVA: 0x290dcf0 VA: 0x7594f25cf0
	public FifthAnnivExploreEventPlanModel GetNextEventModel() { }
	// RVA: 0x290de10 VA: 0x7594f25e10
	public Void JumpToNextEvent() { }
	// RVA: 0x290d9f4 VA: 0x7594f259f4
	public FifthAnnivExplorePlanModel GetCurrPlanModel() { }
	// RVA: 0x290df08 VA: 0x7594f25f08
	public Boolean IsInEvtDecision() { }
	// RVA: 0x290df94 VA: 0x7594f25f94
	public Void BackToEvtInfo() { }
	// RVA: 0x290e03c VA: 0x7594f2603c
	public Void JumpToPlanStatus(String planId) { }
	// RVA: 0x290e0ec VA: 0x7594f260ec
	public Void SelectOption(String optionId) { }
	// RVA: 0x290e224 VA: 0x7594f26224
	public Void SetInExploreDetailState(Boolean inExploreDetailState) { }
	// RVA: 0x290e2a4 VA: 0x7594f262a4
	public Void InitData() { }
	// RVA: 0x290e5e4 VA: 0x7594f265e4
	private Void _InitEventPlanList(PlayerExploreGameContextNode playerNode) { }
	// RVA: 0x290e4a8 VA: 0x7594f264a8
	private Void _InitTargetPlanList(String nextStageId, List`1 playerTarget) { }
	// RVA: 0x290d7e8 VA: 0x7594f257e8
	private Int32 _GetCurrPlanIdx() { }
	// RVA: 0x290ee6c VA: 0x7594f26e6c
	public Void .ctor() { }
}
```