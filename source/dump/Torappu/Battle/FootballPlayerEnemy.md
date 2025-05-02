# FootballPlayerEnemy

**Namespace:** `Torappu.Battle`


## Fields

- `Ability _searchBallAbility`

- `Ability _searchTeammateAbility`

- `Ability _closeToBallAbility`

- `Ability _searchTargetAbility`

- `SlapShotType _slapShotType`

- `ClearanceType _clearancePosType`

- `FootballEnemy m_adjacentFootball`

- `FootballPlayerEnemy m_adjacentPlayer`

- `FP m_passBallForce`

- `FP m_slapshotForce`

- `FP m_clearanceForce`

- `Vector2 m_defaultClearancePos`

- `Boolean m_forceSearchTarget`


## Properties

- `FootballEnemy adjacentFootball`


## Methods

- `FootballEnemy get_adjacentFootball()`

- `Vector2 _MoveToTarget(Single, out, Unit)`

- `Tile _FindNoTrapAroundTile()`

- `Tile _SlapShotSelectGoalTile()`

- `Vector2 _ClearanceGetPos()`

- `Boolean IsCloseToFootball(Boolean)`

- `Boolean HasTeammate()`

- `Boolean DiceSlapShot()`

- `Boolean DoSlapShot()`

- `Boolean DoClearance()`

- `Boolean DoPassTheBall()`

- `Boolean DoDribble()`

- `Void SetForceSearchTarget(Boolean)`

- `FP GetMinimumDistanceToGoal()`

- `Void InitForces(FP, FP, FP)`

- `Void <>xLuaBaseProxy_OnBorn()`

- `Vector2 <>xLuaBaseProxy__MoveByRoute(Single, out)`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class FootballPlayerEnemy : Enemy
{
	private Ability _searchBallAbility; // 0x4b8
	private Ability _searchTeammateAbility; // 0x4c0
	private Ability _closeToBallAbility; // 0x4c8
	private Ability _searchTargetAbility; // 0x4d0
	private SlapShotType _slapShotType; // 0x4d8
	private ClearanceType _clearancePosType; // 0x4dc
	private FootballEnemy m_adjacentFootball; // 0x4e0
	private FootballPlayerEnemy m_adjacentPlayer; // 0x4e8
	private List`1 m_allyGoalTiles; // 0x4f0
	private FP m_passBallForce; // 0x4f8
	private FP m_slapshotForce; // 0x500
	private FP m_clearanceForce; // 0x508
	private Vector2 m_defaultClearancePos; // 0x510
	private Boolean m_forceSearchTarget; // 0x518
	private static DelegateBridge __Hotfix0_get_adjacentFootball; // 0x0
	private static DelegateBridge __Hotfix0_OnBorn; // 0x8
	private static DelegateBridge __Hotfix0__MoveByRoute; // 0x10
	private static DelegateBridge __Hotfix0__MoveToTarget; // 0x18
	private static DelegateBridge __Hotfix0__FindNoTrapAroundTile; // 0x20
	private static DelegateBridge __Hotfix0__SlapShotSelectGoalTile; // 0x28
	private static DelegateBridge __Hotfix0__ClearanceGetPos; // 0x30
	private static DelegateBridge __Hotfix0_IsCloseToFootball; // 0x38
	private static DelegateBridge __Hotfix0_HasTeammate; // 0x40
	private static DelegateBridge __Hotfix0_DiceSlapShot; // 0x48
	private static DelegateBridge __Hotfix0_DoSlapShot; // 0x50
	private static DelegateBridge __Hotfix0_DoClearance; // 0x58
	private static DelegateBridge __Hotfix0_DoPassTheBall; // 0x60
	private static DelegateBridge __Hotfix0_DoDribble; // 0x68
	private static DelegateBridge __Hotfix0_SetForceSearchTarget; // 0x70
	private static DelegateBridge __Hotfix0_GetMinimumDistanceToGoal; // 0x78
	private static DelegateBridge __Hotfix0_InitForces; // 0x80
	private static DelegateBridge __Hotfix0_OnReset; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public FootballEnemy adjacentFootball { get; }

	// RVA: 0x1c1dae8 VA: 0x7594235ae8
	public FootballEnemy get_adjacentFootball() { }
	// RVA: 0x1c1db50 VA: 0x7594235b50
	protected override Void OnBorn() { }
	// RVA: 0x1c1de1c VA: 0x7594235e1c
	protected override Vector2 _MoveByRoute(Single deltaTime, out Boolean isHanging) { }
	// RVA: 0x1c1e3cc VA: 0x75942363cc
	private Vector2 _MoveToTarget(Single deltaTime, out Boolean isHanging, Unit footballEnemy) { }
	// RVA: 0x1c1e894 VA: 0x7594236894
	private Tile _FindNoTrapAroundTile() { }
	// RVA: 0x1c1ebf8 VA: 0x7594236bf8
	private Tile _SlapShotSelectGoalTile() { }
	// RVA: 0x1c1ed38 VA: 0x7594236d38
	private Vector2 _ClearanceGetPos() { }
	// RVA: 0x1c1f1d8 VA: 0x75942371d8
	public Boolean IsCloseToFootball(Boolean ignoreIsSelected) { }
	// RVA: 0x1c1ef04 VA: 0x7594236f04
	public Boolean HasTeammate() { }
	// RVA: 0x1c1f4d4 VA: 0x75942374d4
	public Boolean DiceSlapShot() { }
	// RVA: 0x1c1f824 VA: 0x7594237824
	public Boolean DoSlapShot() { }
	// RVA: 0x1c1fa34 VA: 0x7594237a34
	public Boolean DoClearance() { }
	// RVA: 0x1c1fbec VA: 0x7594237bec
	public Boolean DoPassTheBall() { }
	// RVA: 0x1c1fdd4 VA: 0x7594237dd4
	public Boolean DoDribble() { }
	// RVA: 0x1c1ffb8 VA: 0x7594237fb8
	public Void SetForceSearchTarget(Boolean isActive) { }
	// RVA: 0x1c20038 VA: 0x7594238038
	public FP GetMinimumDistanceToGoal() { }
	// RVA: 0x1c20260 VA: 0x7594238260
	public Void InitForces(FP passBallForce, FP slapShotForce, FP clearanceForce) { }
	// RVA: 0x1c20300 VA: 0x7594238300
	protected override Void OnReset() { }
	// RVA: 0x1c203c8 VA: 0x75942383c8
	public Void .ctor() { }
	// RVA: 0x1c204e8 VA: 0x75942384e8
	private Void <>xLuaBaseProxy_OnBorn() { }
	// RVA: 0x1c204f0 VA: 0x75942384f0
	private Vector2 <>xLuaBaseProxy__MoveByRoute(Single P0, out Boolean P1) { }
	// RVA: 0x1c204f8 VA: 0x75942384f8
	private Void <>xLuaBaseProxy_OnReset() { }
}
```