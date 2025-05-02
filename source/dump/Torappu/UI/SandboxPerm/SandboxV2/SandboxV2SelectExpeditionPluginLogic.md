# SandboxV2SelectExpeditionPluginLogic

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Methods

- `Void InitShuffleViewModel(SandboxV2ShuffleViewModel)`

- `Void _HandleExpeditionService(String, ExpeditionOption, List`1, Action)`

- `Void _OpenSecondaryPage(String)`

- `Void _OpenDialog(String)`

- `Void OnEnsure(SandboxV2CharListProperty, Action, Action)`

- `Void HandlerClick(Int32, SandboxV2CharListProperty)`

- `Boolean ShuffleChar(SandboxV2CharViewModel, SandboxV2ShuffleViewModel)`

- `Boolean IfShowIndex()`

- `Boolean IfFetchPlayerChar()`

- `Int32 SortRule(SandboxV2CharViewModel, SandboxV2CharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SelectExpeditionPluginLogic : SandboxV2SelectPluginLogic, IHotfixable
{
	private static DelegateBridge __Hotfix0_InitShuffleViewModel; // 0x0
	private static DelegateBridge __Hotfix0__HandleExpeditionService; // 0x8
	private static DelegateBridge __Hotfix0__OpenSecondaryPage; // 0x10
	private static DelegateBridge __Hotfix0__OpenDialog; // 0x18
	private static DelegateBridge __Hotfix0_OnEnsure; // 0x20
	private static DelegateBridge __Hotfix0_HandlerClick; // 0x28
	private static DelegateBridge __Hotfix0_ShuffleChar; // 0x30
	private static DelegateBridge __Hotfix0_IfShowIndex; // 0x38
	private static DelegateBridge __Hotfix0_IfFetchPlayerChar; // 0x40
	private static DelegateBridge __Hotfix0_SortRule; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x248a088 VA: 0x7594aa2088
	public Void InitShuffleViewModel(SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x248a10c VA: 0x7594aa210c
	private Void _HandleExpeditionService(String topicId, ExpeditionOption expeditionOption, List`1 charInstIds, Action onEnsure) { }
	// RVA: 0x248a3d4 VA: 0x7594aa23d4
	private Void _OpenSecondaryPage(String topicId) { }
	// RVA: 0x248a5d8 VA: 0x7594aa25d8
	private Void _OpenDialog(String topicId) { }
	// RVA: 0x248a8c4 VA: 0x7594aa28c4
	public Void OnEnsure(SandboxV2CharListProperty property, Action onEnsure, Action dismissAction) { }
	// RVA: 0x248ab78 VA: 0x7594aa2b78
	public Void HandlerClick(Int32 instId, SandboxV2CharListProperty property) { }
	// RVA: 0x248ae3c VA: 0x7594aa2e3c
	public Boolean ShuffleChar(SandboxV2CharViewModel viewModel, SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x248af00 VA: 0x7594aa2f00
	public Boolean IfShowIndex() { }
	// RVA: 0x248af68 VA: 0x7594aa2f68
	public Boolean IfFetchPlayerChar() { }
	// RVA: 0x248afcc VA: 0x7594aa2fcc
	public Int32 SortRule(SandboxV2CharViewModel obj1, SandboxV2CharViewModel obj2) { }
	// RVA: 0x248b2f8 VA: 0x7594aa32f8
	public Void .ctor() { }
}
```