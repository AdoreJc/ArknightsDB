# CooperateStartTile

**Namespace:** `Torappu.Battle`


## Fields

- `String _directEffectKey`

- `PlayerSide m_tilePlayerSide`

- `PlayerSide m_curPlayerSide`

- `CooperateGameMode m_gameMode`

- `Direction m_direct`

- `Boolean m_isPlayerDead`


## Methods

- `Void OnFixedUpdate(FP)`

- `Void _OnPlayerDying(Object)`

- `Void _OnPlayerRevive(Object)`

- `Void _GetModeAlive()`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CooperateStartTile : DynamicBuffTileFixed, IUpdateable
{
	private const String DEFAULT_EFFECT_DIRECT; // 0x0
	private String _directEffectKey; // 0x1d0
	private PlayerSide m_tilePlayerSide; // 0x1d8
	private PlayerSide m_curPlayerSide; // 0x1dc
	private CooperateGameMode m_gameMode; // 0x1e0
	private Direction m_direct; // 0x1e8
	private ObjectPtr`1 m_tileEffect; // 0x1f0
	private Boolean m_isPlayerDead; // 0x200
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x8
	private static DelegateBridge __Hotfix0__OnPlayerDying; // 0x10
	private static DelegateBridge __Hotfix0__OnPlayerRevive; // 0x18
	private static DelegateBridge __Hotfix0__GetModeAlive; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x408c108 VA: 0x75966a4108
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x408c5d8 VA: 0x75966a45d8
	public Void OnFixedUpdate(FP fixedDeltaTime) { }
	// RVA: 0x408c650 VA: 0x75966a4650
	private Void _OnPlayerDying(Object arg) { }
	// RVA: 0x408c8a8 VA: 0x75966a48a8
	private Void _OnPlayerRevive(Object arg) { }
	// RVA: 0x408c4e0 VA: 0x75966a44e0
	private Void _GetModeAlive() { }
	// RVA: 0x408c9b8 VA: 0x75966a49b8
	public Void .ctor() { }
	// RVA: 0x408ca54 VA: 0x75966a4a54
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
}
```