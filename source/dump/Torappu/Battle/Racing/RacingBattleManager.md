# RacingBattleManager

**Namespace:** `Torappu.Battle.Racing`


## Fields

- `RacingGameMode m_gameMode`

- `RacingInput m_racingInput`

- `PeriodicTimer m_rankingTimer`

- `FreeFollowCameraPlugin m_cameraPlugin`


## Properties

- `FreeFollowCameraPlugin cameraPlugin`

- `Int32 ranking`

- `RacingEnemy myRacingEnemy`


## Methods

- `FreeFollowCameraPlugin get_cameraPlugin()`

- `Int32 get_ranking()`

- `RacingEnemy get_myRacingEnemy()`

- `Void Init(RacingGameMode, RacingInput)`

- `Void _ParseCameraPlugin(Blackboard)`

- `Void UseCurrentItem()`

- `SandboxV2RacingItemInfo GetCurrentItemInfo()`

- `Void _OnUnitBorn(Object)`

- `Void OnTick(FP)`

- `Void _UpdateRanking()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Racing
public class RacingBattleManager : IHotfixable
{
	private RacingGameMode m_gameMode; // 0x10
	private RacingInput m_racingInput; // 0x18
	private List`1 m_rankingList; // 0x20
	private PeriodicTimer m_rankingTimer; // 0x28
	private FreeFollowCameraPlugin m_cameraPlugin; // 0x30
	private ObjectPtr`1 m_myRacingEnemy; // 0x38
	private static DelegateBridge __Hotfix0_get_cameraPlugin; // 0x0
	private static DelegateBridge __Hotfix0_get_ranking; // 0x8
	private static DelegateBridge __Hotfix0_get_myRacingEnemy; // 0x10
	private static DelegateBridge __Hotfix0_get_racingEnemies; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0__ParseCameraPlugin; // 0x28
	private static DelegateBridge __Hotfix0_UseCurrentItem; // 0x30
	private static DelegateBridge __Hotfix0_GetCurrentItemInfo; // 0x38
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x40
	private static DelegateBridge __Hotfix0_OnTick; // 0x48
	private static DelegateBridge __Hotfix0__UpdateRanking; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public FreeFollowCameraPlugin cameraPlugin { get; }
	public Int32 ranking { get; }
	public RacingEnemy myRacingEnemy { get; }
	public List`1 racingEnemies { get; }

	// RVA: 0x1d58e3c VA: 0x7594370e3c
	public FreeFollowCameraPlugin get_cameraPlugin() { }
	// RVA: 0x1d58f9c VA: 0x7594370f9c
	public Int32 get_ranking() { }
	// RVA: 0x1d59064 VA: 0x7594371064
	public RacingEnemy get_myRacingEnemy() { }
	// RVA: 0x1d590e4 VA: 0x75943710e4
	public List`1 get_racingEnemies() { }
	// RVA: 0x1d5914c VA: 0x759437114c
	public Void Init(RacingGameMode gamemode, RacingInput input) { }
	// RVA: 0x1d5936c VA: 0x759437136c
	private Void _ParseCameraPlugin(Blackboard blackboard) { }
	// RVA: 0x1d59444 VA: 0x7594371444
	public Void UseCurrentItem() { }
	// RVA: 0x1d594ec VA: 0x75943714ec
	public SandboxV2RacingItemInfo GetCurrentItemInfo() { }
	// RVA: 0x1d595b4 VA: 0x75943715b4
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x1d59900 VA: 0x7594371900
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x1d599c0 VA: 0x75943719c0
	private Void _UpdateRanking() { }
	// RVA: 0x1d59c54 VA: 0x7594371c54
	public Void .ctor() { }
}
```