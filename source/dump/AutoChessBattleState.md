# AutoChessBattleState

**Namespace:** ` `


## Fields

- `Int32 m_defaultCost`

- `Boolean m_disableDeployNextFrame`

- `Single m_maxPlayTime`

- `AutoChessBattleCommentManager m_commentManager`

- `PeriodicTicker m_statusTicker`

- `FP m_roundStartTime`

- `AutoChessDataCenter m_center`


## Properties

- `AutoChessDataCenter center`


## Methods

- `AutoChessDataCenter get_center()`

- `Void _TutorialTryTriggerBattleStart()`

- `Void _FadeDeadDummy(Character)`

- `Void _TryDeployAvailableCharacter()`

- `Boolean _AutoDeploy(BattleChess, UInt32)`

- `Void _TryTriggerAvailableSkills()`

- `Boolean _TryTriggerSkill(Character, AutoChessSkillTriggerType)`

- `Boolean _TryUsingSkillTypeMarcilS2(Character)`

- `Boolean _TryUsingSkillTypeMlyssWtrman(Character)`

- `Boolean _DoDefaultCheck(Character)`

- `Boolean _TrySearchTarget(Character)`

- `Boolean _TryUsingMlyssWtrmanSkill(Character, Int32)`

- `Boolean _CheckToggleSkill(BasicSkill)`

- `Void _UpdateBattleStatus()`

- `Void _UpdateTime()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AutoChessBattleState : AutoChessGameStateBase
{
	private Int32 m_defaultCost; // 0x10
	private Boolean m_disableDeployNextFrame; // 0x14
	private Single m_maxPlayTime; // 0x18
	private AutoChessBattleCommentManager m_commentManager; // 0x20
	private PeriodicTicker m_statusTicker; // 0x28
	private FP m_roundStartTime; // 0x30
	private Nullable`1 m_minLifePoint; // 0x38
	private AutoChessDataCenter m_center; // 0x40

	public override GameState currentState { get; }
	private AutoChessDataCenter center { get; }

	// RVA: 0x1cb1178 VA: 0x75942c9178
	public override GameState get_currentState() { }
	// RVA: 0x1cb1180 VA: 0x75942c9180
	private AutoChessDataCenter get_center() { }
	// RVA: 0x1cb11e8 VA: 0x75942c91e8
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1cb15ac VA: 0x75942c95ac
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1cb1b38 VA: 0x75942c9b38
	public override Void OnApplyingGlobalModifier(ref Modifier modifier) { }
	// RVA: 0x1cb1d20 VA: 0x75942c9d20
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1cb1ef0 VA: 0x75942c9ef0
	public override Void OnCharacterRespawnFailed(Character character, Card card) { }
	// RVA: 0x1cb1f44 VA: 0x75942c9f44
	public override Boolean OnDestroyEntity(Entity entity, FinishReason reason) { }
	// RVA: 0x1cb150c VA: 0x75942c950c
	private Void _TutorialTryTriggerBattleStart() { }
	// RVA: 0x1cb2328 VA: 0x75942ca328
	private Void _FadeDeadDummy(Character dummyCharacter) { }
	// RVA: 0x1cb2794 VA: 0x75942ca794
	public override Void OnUnitRegistered(Unit unit) { }
	// RVA: 0x1cb27b0 VA: 0x75942ca7b0
	public override Void OnCharacterFinished(Character character, FinishReason reason) { }
	// RVA: 0x1cb28d4 VA: 0x75942ca8d4
	public override Void OnEnemyFinished(Enemy enemy, FinishReason reason) { }
	// RVA: 0x1cb16ac VA: 0x75942c96ac
	private Void _TryDeployAvailableCharacter() { }
	// RVA: 0x1cb2a78 VA: 0x75942caa78
	private Boolean _AutoDeploy(BattleChess chess, UInt32 cardUid) { }
	// RVA: 0x1cb18a0 VA: 0x75942c98a0
	private Void _TryTriggerAvailableSkills() { }
	// RVA: 0x1cb2ba4 VA: 0x75942caba4
	private Boolean _TryTriggerSkill(Character character, AutoChessSkillTriggerType type) { }
	// RVA: 0x1cb328c VA: 0x75942cb28c
	private Boolean _TryUsingSkillTypeMarcilS2(Character character) { }
	// RVA: 0x1cb3098 VA: 0x75942cb098
	private Boolean _TryUsingSkillTypeMlyssWtrman(Character character) { }
	// RVA: 0x1cb2c90 VA: 0x75942cac90
	private Boolean _DoDefaultCheck(Character character) { }
	// RVA: 0x1cb2d5c VA: 0x75942cad5c
	private Boolean _TrySearchTarget(Character character) { }
	// RVA: 0x1cb33d0 VA: 0x75942cb3d0
	private Boolean _TryUsingMlyssWtrmanSkill(Character character, Int32 copiedChess) { }
	// RVA: 0x1cb3590 VA: 0x75942cb590
	private Boolean _CheckToggleSkill(BasicSkill skill) { }
	// RVA: 0x1cb1adc VA: 0x75942c9adc
	private Void _UpdateBattleStatus() { }
	// RVA: 0x1cb361c VA: 0x75942cb61c
	private Void _UpdateTime() { }
	// RVA: 0x1cb372c VA: 0x75942cb72c
	public Void .ctor() { }
}
```