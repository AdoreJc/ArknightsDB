# Act3funPlugin

**Namespace:** `Torappu.Activity.Act3fun.Battle.UI`


## Fields

- `Act3funTopbarStatus _topbarStatus`

- `BattleController m_battleController`

- `UIController m_uiController`


## Methods

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_OnGameReady()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam)`

- `Void <>xLuaBaseProxy_HookBattleData(BattleData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3fun.Battle.UI
public class Act3funPlugin : Plugin
{
	private Act3funTopbarStatus _topbarStatus; // 0x28
	private BattleController m_battleController; // 0x30
	private UIController m_uiController; // 0x38
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x8
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x10
	private static DelegateBridge __Hotfix0_HookBattleFailedStateSwitch; // 0x18
	private static DelegateBridge __Hotfix0_HookBattleData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x32227d8 VA: 0x759583a7d8
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x32228b4 VA: 0x759583a8b4
	public override Void OnGameReady() { }
	// RVA: 0x3222b34 VA: 0x759583ab34
	public override Void UpdateGameInfo() { }
	// RVA: 0x3222c74 VA: 0x759583ac74
	public override Boolean HookBattleFailedStateSwitch(BattleFailedStateParam param) { }
	// RVA: 0x3222d7c VA: 0x759583ad7c
	public override Void HookBattleData(BattleData battleData) { }
	// RVA: 0x3222e64 VA: 0x759583ae64
	public Void .ctor() { }
	// RVA: 0x3222ed4 VA: 0x759583aed4
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x3222edc VA: 0x759583aedc
	private Void <>xLuaBaseProxy_OnGameReady() { }
	// RVA: 0x3222ee4 VA: 0x759583aee4
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x3222eec VA: 0x759583aeec
	private Boolean <>xLuaBaseProxy_HookBattleFailedStateSwitch(BattleFailedStateParam P0) { }
	// RVA: 0x3222ef8 VA: 0x759583aef8
	private Void <>xLuaBaseProxy_HookBattleData(BattleData P0) { }
}
```