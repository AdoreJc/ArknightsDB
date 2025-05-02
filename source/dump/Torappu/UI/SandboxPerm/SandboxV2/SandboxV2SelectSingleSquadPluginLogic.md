# SandboxV2SelectSingleSquadPluginLogic

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
public class SandboxV2SelectSingleSquadPluginLogic : SandboxV2SelectPluginLogic, IHotfixable
{
	private static DelegateBridge __Hotfix0_InitShuffleViewModel; // 0x0
	private static DelegateBridge __Hotfix0_OnEnsure; // 0x8
	private static DelegateBridge __Hotfix0_HandlerClick; // 0x10
	private static DelegateBridge __Hotfix0_ShuffleChar; // 0x18
	private static DelegateBridge __Hotfix0_IfShowIndex; // 0x20
	private static DelegateBridge __Hotfix0_IfFetchPlayerChar; // 0x28
	private static DelegateBridge __Hotfix0_SortRule; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x24ad80c VA: 0x7594ac580c
	public Void InitShuffleViewModel(SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x24ad894 VA: 0x7594ac5894
	public Void OnEnsure(SandboxV2CharListProperty property, Action onEnsure, Action dismissAction) { }
	// RVA: 0x24ad94c VA: 0x7594ac594c
	public Void HandlerClick(Int32 instId, SandboxV2CharListProperty property) { }
	// RVA: 0x24adbe0 VA: 0x7594ac5be0
	public Boolean ShuffleChar(SandboxV2CharViewModel viewModel, SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x24adce8 VA: 0x7594ac5ce8
	public Boolean IfShowIndex() { }
	// RVA: 0x24add4c VA: 0x7594ac5d4c
	public Boolean IfFetchPlayerChar() { }
	// RVA: 0x24addb0 VA: 0x7594ac5db0
	public Int32 SortRule(SandboxV2CharViewModel obj1, SandboxV2CharViewModel obj2) { }
	// RVA: 0x24ae12c VA: 0x7594ac612c
	public Void .ctor() { }
}
```