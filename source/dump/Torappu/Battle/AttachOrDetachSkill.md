# AttachOrDetachSkill

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _switchToState`

- `Boolean _isInfinity`

- `FP m_duration`

- `FP m_remainingTime`


## Methods

- `Void _DetachSkill()`

- `Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide)`

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `FP <>xLuaBaseProxy_get_remainingTime()`

- `FP <>xLuaBaseProxy_get_remainingProgress()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnOwnerFinish(FinishReason)`

- `Void <>xLuaBaseProxy_AssignData(SkillData, Character, Blackboard, Delta)`

- `Void <>xLuaBaseProxy_OnCastSucceed()`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AttachOrDetachSkill : BasicSkill
{
	private Boolean _switchToState; // 0xf8
	private Boolean _isInfinity; // 0xf9
	private Ability[] m_abilities; // 0x100
	private FP m_duration; // 0x108
	private FP m_remainingTime; // 0x110
	private static DelegateBridge __Hotfix0_IsAvailable; // 0x0
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x8
	private static DelegateBridge __Hotfix0_get_remainingTime; // 0x10
	private static DelegateBridge __Hotfix0_get_remainingProgress; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnOwnerFinish; // 0x28
	private static DelegateBridge __Hotfix0_AssignData; // 0x30
	private static DelegateBridge __Hotfix0_DoCast; // 0x38
	private static DelegateBridge __Hotfix0_OnCastSucceed; // 0x40
	private static DelegateBridge __Hotfix0_UseSkill; // 0x48
	private static DelegateBridge __Hotfix0_OnTick; // 0x50
	private static DelegateBridge __Hotfix0_Awake; // 0x58
	private static DelegateBridge __Hotfix0__DetachSkill; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override Boolean isAffecting { get; }
	public override FP remainingTime { get; }
	public override FP remainingProgress { get; }

	// RVA: 0x40e74c4 VA: 0x75966ff4c4
	public override Boolean IsAvailable(PlayerSide operationSide) { }
	// RVA: 0x40e758c VA: 0x75966ff58c
	public override Boolean get_isAffecting() { }
	// RVA: 0x40e7604 VA: 0x75966ff604
	public override FP get_remainingTime() { }
	// RVA: 0x40e7704 VA: 0x75966ff704
	public override FP get_remainingProgress() { }
	// RVA: 0x40e77f8 VA: 0x75966ff7f8
	public override Void OnInit() { }
	// RVA: 0x40e7964 VA: 0x75966ff964
	public override Void OnOwnerFinish(FinishReason reason) { }
	// RVA: 0x40e7d9c VA: 0x75966ffd9c
	public override Void AssignData(SkillData data, Character owner, Blackboard externalBlackboard, Delta modifier) { }
	// RVA: 0x40e871c VA: 0x759670071c
	protected override Boolean DoCast(FinishCallbackDelegate finishCb, PlayerSide operationSide) { }
	// RVA: 0x40e8d24 VA: 0x7596700d24
	protected override Void OnCastSucceed() { }
	// RVA: 0x40e90f8 VA: 0x75967010f8
	public override Boolean UseSkill(PlayerSide operationSide) { }
	// RVA: 0x40e91b0 VA: 0x75967011b0
	protected override Void OnTick(FP deltaTime) { }
	// RVA: 0x40e9498 VA: 0x7596701498
	protected override Void Awake() { }
	// RVA: 0x40e7a04 VA: 0x75966ffa04
	private Void _DetachSkill() { }
	// RVA: 0x40e96ac VA: 0x75967016ac
	public Void .ctor() { }
	// RVA: 0x40e9718 VA: 0x7596701718
	private Boolean <>xLuaBaseProxy_IsAvailable(PlayerSide P0) { }
	// RVA: 0x40e971c VA: 0x759670171c
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x40e9720 VA: 0x7596701720
	private FP <>xLuaBaseProxy_get_remainingTime() { }
	// RVA: 0x40e981c VA: 0x759670181c
	private FP <>xLuaBaseProxy_get_remainingProgress() { }
	// RVA: 0x40e9820 VA: 0x7596701820
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x40e9824 VA: 0x7596701824
	private Void <>xLuaBaseProxy_OnOwnerFinish(FinishReason P0) { }
	// RVA: 0x40e9828 VA: 0x7596701828
	private Void <>xLuaBaseProxy_AssignData(SkillData P0, Character P1, Blackboard P2, Delta P3) { }
	// RVA: 0x40e982c VA: 0x759670182c
	private Void <>xLuaBaseProxy_OnCastSucceed() { }
	// RVA: 0x40e9830 VA: 0x7596701830
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x40e9834 VA: 0x7596701834
	private Void <>xLuaBaseProxy_Awake() { }
}
```