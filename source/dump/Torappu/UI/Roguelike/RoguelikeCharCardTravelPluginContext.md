# RoguelikeCharCardTravelPluginContext

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeSelectCharTravelConflictPanel _travelConflictPrefab`

- `String m_travelConflictToast`


## Methods

- `Boolean _IsInTravel(Int32)`

- `Int32 <get_additionalComparers>b__8_0(RoguelikeCharCardViewModel, RoguelikeCharCardViewModel)`

- `RoguelikeCharCardViewPluginPriority <>xLuaBaseProxy_get_pluginPriority()`

- `Boolean <>xLuaBaseProxy_CheckCharSelectValid(RoguelikeSelectCharViewModel, RoguelikeCharCardViewModel, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharCardTravelPluginContext : RoguelikeCharCardViewPluginContext
{
	private RoguelikeSelectCharTravelConflictPanel _travelConflictPrefab; // 0x18
	private HashSet`1 m_travelCharList; // 0x20
	private String m_travelConflictToast; // 0x28
	private static DelegateBridge __Hotfix0__IsInTravel; // 0x0
	private static DelegateBridge __Hotfix0_get_pluginPriority; // 0x8
	private static DelegateBridge __Hotfix0_get_additionalComparers; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_CheckCharSelectValid; // 0x20
	private static DelegateBridge __Hotfix0_GetPlugin; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override RoguelikeCharCardViewPluginPriority pluginPriority { get; }
	public override List`1 additionalComparers { get; }

	// RVA: 0x2ac4280 VA: 0x75950dc280
	private Boolean _IsInTravel(Int32 troopInstId) { }
	// RVA: 0x2ac4338 VA: 0x75950dc338
	public override RoguelikeCharCardViewPluginPriority get_pluginPriority() { }
	// RVA: 0x2ac439c VA: 0x75950dc39c
	public override List`1 get_additionalComparers() { }
	// RVA: 0x2ac4554 VA: 0x75950dc554
	public override Void LoadData(String topicId) { }
	// RVA: 0x2ac4840 VA: 0x75950dc840
	public override Boolean CheckCharSelectValid(RoguelikeSelectCharViewModel groupModel, RoguelikeCharCardViewModel charModel, out String invalidToast) { }
	// RVA: 0x2ac4918 VA: 0x75950dc918
	public override IRoguelikeCharCardPlugin GetPlugin() { }
	// RVA: 0x2ac4a3c VA: 0x75950dca3c
	public Void .ctor() { }
	// RVA: 0x2ac4afc VA: 0x75950dcafc
	private Int32 <get_additionalComparers>b__8_0(RoguelikeCharCardViewModel lhs, RoguelikeCharCardViewModel rhs) { }
	// RVA: 0x2ac4ba4 VA: 0x75950dcba4
	private RoguelikeCharCardViewPluginPriority <>xLuaBaseProxy_get_pluginPriority() { }
	// RVA: 0x2ac4ba8 VA: 0x75950dcba8
	private List`1 <>xLuaBaseProxy_get_additionalComparers() { }
	// RVA: 0x2ac4bac VA: 0x75950dcbac
	private Boolean <>xLuaBaseProxy_CheckCharSelectValid(RoguelikeSelectCharViewModel P0, RoguelikeCharCardViewModel P1, out String P2) { }
}
```