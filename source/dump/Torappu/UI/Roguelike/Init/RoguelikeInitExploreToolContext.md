# RoguelikeInitExploreToolContext

**Namespace:** `Torappu.UI.Roguelike.Init`


## Methods

- `Void _AddExploreTool(String, RoguelikeTopicItemModel)`

- `Void <OnSelect>b__7_0(RoguelikeSelectInitialExploreToolResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitExploreToolContext : RoguelikeInitOptionContext
{
	private List`1 m_list; // 0x28
	private List`1 m_exploreTools; // 0x30
	private static DelegateBridge __Hotfix0_Load; // 0x0
	private static DelegateBridge __Hotfix0_get_name; // 0x8
	private static DelegateBridge __Hotfix0_get_list; // 0x10
	private static DelegateBridge __Hotfix0_OnSelect; // 0x18
	private static DelegateBridge __Hotfix0__AddExploreTool; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override String name { get; }
	public override List`1 list { get; }

	// RVA: 0x2b7f710 VA: 0x7595197710
	public override Void Load(PlayerRoguelikePendingEvent evt) { }
	// RVA: 0x2b7fdc0 VA: 0x7595197dc0
	public override String get_name() { }
	// RVA: 0x2b7fe4c VA: 0x7595197e4c
	public override List`1 get_list() { }
	// RVA: 0x2b7feb4 VA: 0x7595197eb4
	public override Void OnSelect(Int32 idx) { }
	// RVA: 0x2b7faec VA: 0x7595197aec
	private Void _AddExploreTool(String index, RoguelikeTopicItemModel itemData) { }
	// RVA: 0x2b80150 VA: 0x7595198150
	public Void .ctor() { }
	// RVA: 0x2b80260 VA: 0x7595198260
	private Void <OnSelect>b__7_0(RoguelikeSelectInitialExploreToolResponse response) { }
}
```