# RoguelikeCharCardExpeditionPluginContext

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeSelectCharExpeditionConflictPanel _expeditionConflictPrefab`

- `String m_expeditionConflictToast`


## Methods

- `Boolean _IsInExpedition(Int32)`

- `Int32 <get_additionalComparers>b__8_0(RoguelikeCharCardViewModel, RoguelikeCharCardViewModel)`

- `RoguelikeCharCardViewPluginPriority <>xLuaBaseProxy_get_pluginPriority()`

- `Boolean <>xLuaBaseProxy_CheckCharSelectValid(RoguelikeSelectCharViewModel, RoguelikeCharCardViewModel, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharCardExpeditionPluginContext : RoguelikeCharCardViewPluginContext
{
	private RoguelikeSelectCharExpeditionConflictPanel _expeditionConflictPrefab; // 0x18
	private HashSet`1 m_expeditionCharList; // 0x20
	private String m_expeditionConflictToast; // 0x28
	private static DelegateBridge __Hotfix0__IsInExpedition; // 0x0
	private static DelegateBridge __Hotfix0_get_pluginPriority; // 0x8
	private static DelegateBridge __Hotfix0_get_additionalComparers; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_CheckCharSelectValid; // 0x20
	private static DelegateBridge __Hotfix0_GetPlugin; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override RoguelikeCharCardViewPluginPriority pluginPriority { get; }
	public override List`1 additionalComparers { get; }

	// RVA: 0x2ac2780 VA: 0x75950da780
	private Boolean _IsInExpedition(Int32 troopInstId) { }
	// RVA: 0x2ac2838 VA: 0x75950da838
	public override RoguelikeCharCardViewPluginPriority get_pluginPriority() { }
	// RVA: 0x2ac289c VA: 0x75950da89c
	public override List`1 get_additionalComparers() { }
	// RVA: 0x2ac2a50 VA: 0x75950daa50
	public override Void LoadData(String topicId) { }
	// RVA: 0x2ac2d38 VA: 0x75950dad38
	public override Boolean CheckCharSelectValid(RoguelikeSelectCharViewModel groupModel, RoguelikeCharCardViewModel charModel, out String invalidToast) { }
	// RVA: 0x2ac2e10 VA: 0x75950dae10
	public override IRoguelikeCharCardPlugin GetPlugin() { }
	// RVA: 0x2ac2f34 VA: 0x75950daf34
	public Void .ctor() { }
	// RVA: 0x2ac3064 VA: 0x75950db064
	private Int32 <get_additionalComparers>b__8_0(RoguelikeCharCardViewModel lhs, RoguelikeCharCardViewModel rhs) { }
	// RVA: 0x2ac310c VA: 0x75950db10c
	private RoguelikeCharCardViewPluginPriority <>xLuaBaseProxy_get_pluginPriority() { }
	// RVA: 0x2ac3178 VA: 0x75950db178
	private List`1 <>xLuaBaseProxy_get_additionalComparers() { }
	// RVA: 0x2ac31e0 VA: 0x75950db1e0
	private Boolean <>xLuaBaseProxy_CheckCharSelectValid(RoguelikeSelectCharViewModel P0, RoguelikeCharCardViewModel P1, out String P2) { }
}
```