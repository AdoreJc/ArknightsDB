# RL02SelectCharCardMutationPluginContext

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `RoguelikeMenuButtonPlugin _purifyMenuPlugin`

- `String m_topicId`


## Methods

- `RoguelikeGameCharBuffType _GetMutationType(Int32)`

- `RoguelikeMenuButtonPlugin <>xLuaBaseProxy_GetCustomPendingEventSelectMenuPlugin(ShowConfig)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02SelectCharCardMutationPluginContext : RoguelikeCharCardViewPluginContext
{
	private RoguelikeMenuButtonPlugin _purifyMenuPlugin; // 0x18
	private EnumIntStructDictionary`2 m_charBuffDict; // 0x20
	private String m_topicId; // 0x28
	private static DelegateBridge __Hotfix0__GetMutationType; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_GetPlugin; // 0x10
	private static DelegateBridge __Hotfix0_GetCustomPendingEventSelectMenuPlugin; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b71f3c VA: 0x7595189f3c
	private RoguelikeGameCharBuffType _GetMutationType(Int32 troopInstId) { }
	// RVA: 0x2b71ff4 VA: 0x7595189ff4
	public override Void LoadData(String topicId) { }
	// RVA: 0x2b72224 VA: 0x759518a224
	public override IRoguelikeCharCardPlugin GetPlugin() { }
	// RVA: 0x2b72358 VA: 0x759518a358
	public override RoguelikeMenuButtonPlugin GetCustomPendingEventSelectMenuPlugin(ShowConfig showConfig) { }
	// RVA: 0x2b72448 VA: 0x759518a448
	public Void .ctor() { }
	// RVA: 0x2b7250c VA: 0x759518a50c
	private RoguelikeMenuButtonPlugin <>xLuaBaseProxy_GetCustomPendingEventSelectMenuPlugin(ShowConfig P0) { }
}
```