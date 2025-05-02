# RL04NormalModePlugin

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `GameObject _panelNodeUpgrade`

- `GameObject _panelUnComplete`

- `GameObject _panelAllComplete`

- `UIPageFinder m_pageFinder`

- `Int32 m_dialogInst`


## Methods

- `Void OnNodeUpgradeClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04NormalModePlugin : RoguelikeTopicNormalModeViewPlugin
{
	private GameObject _panelNodeUpgrade; // 0x18
	private GameObject _panelUnComplete; // 0x20
	private GameObject _panelAllComplete; // 0x28
	private UIPageFinder m_pageFinder; // 0x30
	private Int32 m_dialogInst; // 0x40
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnNodeUpgradeClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x26ef514 VA: 0x7594d07514
	public override Void Init(RoguelikeTopicNormalModeView view) { }
	// RVA: 0x26ef58c VA: 0x7594d0758c
	public override Void Render(RoguelikeTopicModeViewModel viewModel) { }
	// RVA: 0x26efa64 VA: 0x7594d07a64
	public Void OnNodeUpgradeClick() { }
	// RVA: 0x26efc84 VA: 0x7594d07c84
	public Void .ctor() { }
}
```