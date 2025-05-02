# DialogDefaultPlugin

**Namespace:** `Torappu.Battle.Dialog`


## Methods

- `GameModeType <>xLuaBaseProxy_get_mode()`

- `String <>xLuaBaseProxy_GetBeforeBattleSignal()`

- `String <>xLuaBaseProxy_GetAfterBattleSignal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogDefaultPlugin : DialogControllerGameModePlugin
{
	private static DelegateBridge __Hotfix0_get_mode; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0_GetBeforeBattleSignal; // 0x10
	private static DelegateBridge __Hotfix0_GetAfterBattleSignal; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override GameModeType mode { get; }

	// RVA: 0x1d27940 VA: 0x759433f940
	public override GameModeType get_mode() { }
	// RVA: 0x1d279a4 VA: 0x759433f9a4
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x1d27a50 VA: 0x759433fa50
	public override String GetBeforeBattleSignal() { }
	// RVA: 0x1d27b94 VA: 0x759433fb94
	public override String GetAfterBattleSignal() { }
	// RVA: 0x1d27cd8 VA: 0x759433fcd8
	public Void .ctor() { }
	// RVA: 0x1d27d44 VA: 0x759433fd44
	private GameModeType <>xLuaBaseProxy_get_mode() { }
	// RVA: 0x1d27d48 VA: 0x759433fd48
	private Dictionary`2 <>xLuaBaseProxy_GetExecutors() { }
	// RVA: 0x1d27d4c VA: 0x759433fd4c
	private String <>xLuaBaseProxy_GetBeforeBattleSignal() { }
	// RVA: 0x1d27d50 VA: 0x759433fd50
	private String <>xLuaBaseProxy_GetAfterBattleSignal() { }
}
```