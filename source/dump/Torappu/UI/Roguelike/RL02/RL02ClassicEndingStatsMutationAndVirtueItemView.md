# RL02ClassicEndingStatsMutationAndVirtueItemView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Image _imageIcon`

- `GameObject _pnlBkgMutation`

- `GameObject _pnlBkgVirtue`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(RoguelikeSquadBuffModel, String)`

- `Void Render(RoguelikeCharBuffModel, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ClassicEndingStatsMutationAndVirtueItemView : MonoBehaviour, IHotfixable
{
	private Image _imageIcon; // 0x18
	private GameObject _pnlBkgMutation; // 0x20
	private GameObject _pnlBkgVirtue; // 0x28
	private UIPageFinder m_pageFinder; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix1_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b5e01c VA: 0x759517601c
	public Void Render(RoguelikeSquadBuffModel virtueModel, String topicId) { }
	// RVA: 0x2b5e16c VA: 0x759517616c
	public Void Render(RoguelikeCharBuffModel mutationModel, String topicId) { }
	// RVA: 0x2b5e2c4 VA: 0x75951762c4
	public Void .ctor() { }
}
```