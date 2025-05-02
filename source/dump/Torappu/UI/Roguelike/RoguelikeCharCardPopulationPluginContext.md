# RoguelikeCharCardPopulationPluginContext

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String m_topicId`

- `Int32 m_currPopulation`


## Methods

- `Int32 _CalculateSelectedPopulation(RoguelikeSelectCharViewModel)`

- `Boolean <>xLuaBaseProxy_CheckCharSelectValid(RoguelikeSelectCharViewModel, RoguelikeCharCardViewModel, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharCardPopulationPluginContext : RoguelikeCharCardViewPluginContext
{
	private String m_topicId; // 0x18
	private Int32 m_currPopulation; // 0x20
	private static DelegateBridge __Hotfix0_get_additionalComparers; // 0x0
	private static DelegateBridge __Hotfix0__CalculateSelectedPopulation; // 0x8
	private static DelegateBridge __Hotfix0_CheckCharSelectValid; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_GetPlugin; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override List`1 additionalComparers { get; }

	// RVA: 0x2ac3470 VA: 0x75950db470
	public override List`1 get_additionalComparers() { }
	// RVA: 0x2ac3688 VA: 0x75950db688
	private Int32 _CalculateSelectedPopulation(RoguelikeSelectCharViewModel groupModel) { }
	// RVA: 0x2ac37c8 VA: 0x75950db7c8
	public override Boolean CheckCharSelectValid(RoguelikeSelectCharViewModel groupModel, RoguelikeCharCardViewModel charModel, out String invalidToast) { }
	// RVA: 0x2ac3924 VA: 0x75950db924
	public override Void LoadData(String topicId) { }
	// RVA: 0x2ac3a08 VA: 0x75950dba08
	public override IRoguelikeCharCardPlugin GetPlugin() { }
	// RVA: 0x2ac3b2c VA: 0x75950dbb2c
	public Void .ctor() { }
	// RVA: 0x2ac3b98 VA: 0x75950dbb98
	private List`1 <>xLuaBaseProxy_get_additionalComparers() { }
	// RVA: 0x2ac3b9c VA: 0x75950dbb9c
	private Boolean <>xLuaBaseProxy_CheckCharSelectValid(RoguelikeSelectCharViewModel P0, RoguelikeCharCardViewModel P1, out String P2) { }
}
```