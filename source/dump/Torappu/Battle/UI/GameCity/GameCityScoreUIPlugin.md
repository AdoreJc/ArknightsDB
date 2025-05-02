# GameCityScoreUIPlugin

**Namespace:** `Torappu.Battle.UI.GameCity`


## Fields

- `GameCityBattleScoreUIPanel _scorePanel`

- `String _buffKey`

- `Unit m_owner`

- `GameCityGameMode m_gameMode`


## Properties

- `GameCityGameMode gameMode`


## Methods

- `GameCityGameMode get_gameMode()`

- `Void Start()`

- `Void Update()`

- `Void <>xLuaBaseProxy_DoAttach(Unit)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.GameCity
public class GameCityScoreUIPlugin : HudPlugin
{
	private GameCityBattleScoreUIPanel _scorePanel; // 0x28
	private String _buffKey; // 0x30
	private ObjectPtr`1 m_buff; // 0x38
	private Unit m_owner; // 0x48
	private GameCityGameMode m_gameMode; // 0x50
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private GameCityGameMode gameMode { get; }

	// RVA: 0x20f786c VA: 0x759470f86c
	private GameCityGameMode get_gameMode() { }
	// RVA: 0x20f79b8 VA: 0x759470f9b8
	protected override Void DoAttach(Unit owner) { }
	// RVA: 0x20f7a4c VA: 0x759470fa4c
	private Void Start() { }
	// RVA: 0x20f7ac4 VA: 0x759470fac4
	private Void Update() { }
	// RVA: 0x20f7cec VA: 0x759470fcec
	public Void .ctor() { }
	// RVA: 0x20f7d8c VA: 0x759470fd8c
	private Void <>xLuaBaseProxy_DoAttach(Unit P0) { }
}
```