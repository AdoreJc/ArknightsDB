# RoguelikeMenuRelicWindowItemView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `GameObject _relicPanel`

- `GameObject _trapPanel`

- `GameObject _exploreToolPanel`

- `RelicPart _relicPart`

- `TrapPart _trapPart`

- `ExploreToolPart _exploreToolPart`

- `Panel m_cachedCurrPanel`


## Methods

- `Void EventOnClicked()`

- `Void Render(IRoguelikeRelicViewModel)`

- `Panel _GetPanelTypeFromRelicItemType(RoguelikeMenuRelicItemType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuRelicWindowItemView : MonoBehaviour, IHotfixable
{
	private GameObject _relicPanel; // 0x18
	private GameObject _trapPanel; // 0x20
	private GameObject _exploreToolPanel; // 0x28
	private RelicPart _relicPart; // 0x30
	private TrapPart _trapPart; // 0x38
	private ExploreToolPart _exploreToolPart; // 0x40
	private Panel m_cachedCurrPanel; // 0x48
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__GetPanelTypeFromRelicItemType; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a74814 VA: 0x759508c814
	public Void EventOnClicked() { }
	// RVA: 0x2a744f8 VA: 0x759508c4f8
	public Void Render(IRoguelikeRelicViewModel viewModel) { }
	// RVA: 0x2a74f5c VA: 0x759508cf5c
	private Panel _GetPanelTypeFromRelicItemType(RoguelikeMenuRelicItemType relicItemType) { }
	// RVA: 0x2a75644 VA: 0x759508d644
	public Void .ctor() { }
}
```