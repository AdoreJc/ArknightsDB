# BattlePluginExternalHost

**Namespace:** `Torappu.Battle`


## Fields

- `BattleTutorialCommandPostChecker m_checker`


## Methods

- `Void OnGameInit(Options)`

- `Void OnGameOver(GameResult)`

- `Void OnGameReset(BattleController)`

- `Void OnGameReady()`

- `Void OnGameStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattlePluginExternalHost : IBattleModule, IHotfixable
{
	private BattleTutorialCommandPostChecker m_checker; // 0x10
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x0
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x8
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x10
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x18
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3fd4a90 VA: 0x75965eca90
	public Void OnGameInit(Options levelOptions) { }
	// RVA: 0x3fd4c94 VA: 0x75965ecc94
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x3fd4d48 VA: 0x75965ecd48
	public Void OnGameReset(BattleController controller) { }
	// RVA: 0x3fd4dc0 VA: 0x75965ecdc0
	public Void OnGameReady() { }
	// RVA: 0x3fd4e24 VA: 0x75965ece24
	public Void OnGameStart() { }
	// RVA: 0x3fd4e88 VA: 0x75965ece88
	public Void .ctor() { }
}
```