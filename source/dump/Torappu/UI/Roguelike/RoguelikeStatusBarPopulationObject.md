# RoguelikeStatusBarPopulationObject

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikePopBarView _popBarView`

- `RoguelikeMenuPopulationViewModel m_cachedModel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeStatusBarPopulationObject : RoguelikeMenuObject`1
{
	private RoguelikePopBarView _popBarView; // 0x28
	private RoguelikeMenuPopulationViewModel m_cachedModel; // 0x30
	private static DelegateBridge __Hotfix0_get_menuType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override RoguelikeMenuType menuType { get; }

	// RVA: 0x2a70dd8 VA: 0x7595088dd8
	public override RoguelikeMenuType get_menuType() { }
	// RVA: 0x2a70e40 VA: 0x7595088e40
	public override Void Render(RoguelikeMenuPopulationViewModel viewModel) { }
	// RVA: 0x2a70f18 VA: 0x7595088f18
	public Void .ctor() { }
}
```