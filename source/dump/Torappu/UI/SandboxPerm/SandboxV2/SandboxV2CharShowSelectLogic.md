# SandboxV2CharShowSelectLogic

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
public class SandboxV2CharShowSelectLogic : SandboxV2SelectPluginLogic, IHotfixable
{
	private static DelegateBridge __Hotfix0_InitShuffleViewModel; // 0x0
	private static DelegateBridge __Hotfix0_OnEnsure; // 0x8
	private static DelegateBridge __Hotfix0_HandlerClick; // 0x10
	private static DelegateBridge __Hotfix0_ShuffleChar; // 0x18
	private static DelegateBridge __Hotfix0_IfShowIndex; // 0x20
	private static DelegateBridge __Hotfix0_IfFetchPlayerChar; // 0x28
	private static DelegateBridge __Hotfix0_SortRule; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2489010 VA: 0x7594aa1010
	public Void InitShuffleViewModel(SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x2489094 VA: 0x7594aa1094
	public Void OnEnsure(SandboxV2CharListProperty property, Action onEnsure, Action dismissAction) { }
	// RVA: 0x248914c VA: 0x7594aa114c
	public Void HandlerClick(Int32 instId, SandboxV2CharListProperty property) { }
	// RVA: 0x2489398 VA: 0x7594aa1398
	public Boolean ShuffleChar(SandboxV2CharViewModel viewModel, SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x24894a4 VA: 0x7594aa14a4
	public Boolean IfShowIndex() { }
	// RVA: 0x2489508 VA: 0x7594aa1508
	public Boolean IfFetchPlayerChar() { }
	// RVA: 0x2489570 VA: 0x7594aa1570
	public Int32 SortRule(SandboxV2CharViewModel obj1, SandboxV2CharViewModel obj2) { }
	// RVA: 0x2489604 VA: 0x7594aa1604
	public Void .ctor() { }
}
```