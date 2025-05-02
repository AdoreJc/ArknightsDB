# SandboxV2SelectMultiSquadPluginLogic

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Methods

- `Void InitShuffleViewModel(SandboxV2ShuffleViewModel)`

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
public class SandboxV2SelectMultiSquadPluginLogic : SandboxV2SelectPluginLogic, IHotfixable
{
	private static DelegateBridge __Hotfix0_InitShuffleViewModel; // 0x0
	private static DelegateBridge __Hotfix0_OnEnsure; // 0x8
	private static DelegateBridge __Hotfix0_HandlerClick; // 0x10
	private static DelegateBridge __Hotfix0_ShuffleChar; // 0x18
	private static DelegateBridge __Hotfix0_IfShowIndex; // 0x20
	private static DelegateBridge __Hotfix0_IfFetchPlayerChar; // 0x28
	private static DelegateBridge __Hotfix0_SortRule; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2489674 VA: 0x7594aa1674
	public Void InitShuffleViewModel(SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x24896fc VA: 0x7594aa16fc
	public Void OnEnsure(SandboxV2CharListProperty property, Action onEnsure, Action dismissAction) { }
	// RVA: 0x24897b4 VA: 0x7594aa17b4
	public Void HandlerClick(Int32 instId, SandboxV2CharListProperty property) { }
	// RVA: 0x2489a88 VA: 0x7594aa1a88
	public Boolean ShuffleChar(SandboxV2CharViewModel viewModel, SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x2489b94 VA: 0x7594aa1b94
	public Boolean IfShowIndex() { }
	// RVA: 0x2489bfc VA: 0x7594aa1bfc
	public Boolean IfFetchPlayerChar() { }
	// RVA: 0x2489c60 VA: 0x7594aa1c60
	public Int32 SortRule(SandboxV2CharViewModel obj1, SandboxV2CharViewModel obj2) { }
	// RVA: 0x248a018 VA: 0x7594aa2018
	public Void .ctor() { }
}
```