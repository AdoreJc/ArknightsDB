# RoguelikeCharSelectStateBean

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeSelectCharProperty property`

- `Action onQuitAction`

- `UIPageFinder m_pageFinder`

- `Input input`

- `Output output`


## Methods

- `Void AttachPluginContexts(List`1)`

- `Void DealWithInput(String)`

- `String _GetCharId(Int32)`

- `Void _GenSpInstInSquadData(RoguelikeCharCardViewModel)`

- `Boolean CheckViewModelValid(RoguelikeCharCardViewModel, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public RoguelikeSelectCharProperty property; // 0x18
	public Action`2 onCancelAction; // 0x20
	public Action`2 onSelectAction; // 0x28
	public Action`3 onFinishSelectAction; // 0x30
	public Action onQuitAction; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	public Input input; // 0x50
	public Output output; // 0x58
	private List`1 m_pluginContexts; // 0x60
	private static DelegateBridge __Hotfix0_AttachPluginContexts; // 0x0
	private static DelegateBridge __Hotfix0_DealWithInput; // 0x8
	private static DelegateBridge __Hotfix0__GetCharId; // 0x10
	private static DelegateBridge __Hotfix0__GenSpInstInSquadData; // 0x18
	private static DelegateBridge __Hotfix0_CheckViewModelValid; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ad2f88 VA: 0x75950eaf88
	public Void AttachPluginContexts(List`1 pluginContexts) { }
	// RVA: 0x2ad300c VA: 0x75950eb00c
	public Void DealWithInput(String topicId) { }
	// RVA: 0x2ad38c0 VA: 0x75950eb8c0
	private String _GetCharId(Int32 instId) { }
	// RVA: 0x2ad3674 VA: 0x75950eb674
	private Void _GenSpInstInSquadData(RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2ad39f4 VA: 0x75950eb9f4
	public Boolean CheckViewModelValid(RoguelikeCharCardViewModel charModel, out String invalidToast) { }
	// RVA: 0x2ad3bb8 VA: 0x75950ebbb8
	public Void .ctor() { }
}
```