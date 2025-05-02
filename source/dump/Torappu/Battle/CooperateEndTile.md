# CooperateEndTile

**Namespace:** `Torappu.Battle`


## Fields

- `String _directEffectKey`

- `PlayerSide m_curPlayerSide`

- `PlayerSide m_tilePlayerSide`

- `CooperateGameMode m_gameMode`

- `Direction m_direct`

- `Boolean m_isPlayerDead`


## Properties

- `PlayerSide tilePlayerSide`


## Methods

- `PlayerSide get_tilePlayerSide()`

- `Void OnFixedUpdate(FP)`

- `Void _GetModeAlive()`

- `Void _OnPlayerDying(Object)`

- `Void _OnPlayerRevive(Object)`

- `Int32 <>xLuaBaseProxy_get_modeIndex()`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CooperateEndTile : DynamicBuffTileFixed, IUpdateable
{
	private const String DEFAULT_EFFECT_DIRECT; // 0x0
	private String _directEffectKey; // 0x1d0
	private PlayerSide m_curPlayerSide; // 0x1d8
	private PlayerSide m_tilePlayerSide; // 0x1dc
	private CooperateGameMode m_gameMode; // 0x1e0
	private Direction m_direct; // 0x1e8
	private ObjectPtr`1 m_tileEffect; // 0x1f0
	private Boolean m_isPlayerDead; // 0x200
	private static DelegateBridge __Hotfix0_get_modeIndex; // 0x0
	private static DelegateBridge __Hotfix0_get_tilePlayerSide; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x18
	private static DelegateBridge __Hotfix0__GetModeAlive; // 0x20
	private static DelegateBridge __Hotfix0__OnPlayerDying; // 0x28
	private static DelegateBridge __Hotfix0__OnPlayerRevive; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Int32 modeIndex { get; }
	public PlayerSide tilePlayerSide { get; }

	// RVA: 0x408b504 VA: 0x75966a3504
	public override Int32 get_modeIndex() { }
	// RVA: 0x408b56c VA: 0x75966a356c
	public PlayerSide get_tilePlayerSide() { }
	// RVA: 0x408b5d4 VA: 0x75966a35d4
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x408bb94 VA: 0x75966a3b94
	public Void OnFixedUpdate(FP fixedDeltaTime) { }
	// RVA: 0x408baa0 VA: 0x75966a3aa0
	private Void _GetModeAlive() { }
	// RVA: 0x408bc0c VA: 0x75966a3c0c
	private Void _OnPlayerDying(Object arg) { }
	// RVA: 0x408be64 VA: 0x75966a3e64
	private Void _OnPlayerRevive(Object arg) { }
	// RVA: 0x408bff4 VA: 0x75966a3ff4
	public Void .ctor() { }
	// RVA: 0x408c0fc VA: 0x75966a40fc
	private Int32 <>xLuaBaseProxy_get_modeIndex() { }
	// RVA: 0x408c104 VA: 0x75966a4104
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
}
```