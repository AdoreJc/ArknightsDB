# RL04MenuInspirationWindow

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _itemIconImg`

- `Text _itemName`

- `Text _itemUsage`

- `UIPageFinder m_pageFinder`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04MenuInspirationWindow : RoguelikeMenuWindow`1
{
	private Image _itemIconImg; // 0x28
	private Text _itemName; // 0x30
	private Text _itemUsage; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private static DelegateBridge __Hotfix0_get_selectType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2b2dee4 VA: 0x7595145ee4
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2b2df4c VA: 0x7595145f4c
	public override Void Render(RL04MenuInspirationViewModel viewModel) { }
	// RVA: 0x2b2e14c VA: 0x759514614c
	public Void .ctor() { }
}
```