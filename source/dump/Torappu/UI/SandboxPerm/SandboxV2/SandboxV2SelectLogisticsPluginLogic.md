# SandboxV2SelectLogisticsPluginLogic

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Methods

- `Void InitShuffleViewModel(SandboxV2ShuffleViewModel)`

- `Void OnEnsure(SandboxV2CharListProperty, Action, Action)`

- `Void HandlerClick(Int32, SandboxV2CharListProperty)`

- `Boolean ShuffleChar(SandboxV2CharViewModel, SandboxV2ShuffleViewModel)`

- `Boolean IfShowIndex()`

- `Int32 SortRule(SandboxV2CharViewModel, SandboxV2CharViewModel)`

- `Boolean IfFetchPlayerChar()`

- `Void _HandleSetSupplyService(String, List`1, Action, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SelectLogisticsPluginLogic : SandboxV2SelectPluginLogic, IHotfixable
{
	private static DelegateBridge __Hotfix0_InitShuffleViewModel; // 0x0
	private static DelegateBridge __Hotfix0_OnEnsure; // 0x8
	private static DelegateBridge __Hotfix0_HandlerClick; // 0x10
	private static DelegateBridge __Hotfix0_ShuffleChar; // 0x18
	private static DelegateBridge __Hotfix0_IfShowIndex; // 0x20
	private static DelegateBridge __Hotfix0_SortRule; // 0x28
	private static DelegateBridge __Hotfix0_IfFetchPlayerChar; // 0x30
	private static DelegateBridge __Hotfix0__HandleSetSupplyService; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x24ac6e4 VA: 0x7594ac46e4
	public Void InitShuffleViewModel(SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x24ac768 VA: 0x7594ac4768
	public Void OnEnsure(SandboxV2CharListProperty property, Action onEnsure, Action dismissAction) { }
	// RVA: 0x24acc88 VA: 0x7594ac4c88
	public Void HandlerClick(Int32 instId, SandboxV2CharListProperty property) { }
	// RVA: 0x24ad268 VA: 0x7594ac5268
	public Boolean ShuffleChar(SandboxV2CharViewModel viewModel, SandboxV2ShuffleViewModel shuffleViewModel) { }
	// RVA: 0x24ad390 VA: 0x7594ac5390
	public Boolean IfShowIndex() { }
	// RVA: 0x24ad3f8 VA: 0x7594ac53f8
	public Int32 SortRule(SandboxV2CharViewModel obj1, SandboxV2CharViewModel obj2) { }
	// RVA: 0x24ad6ec VA: 0x7594ac56ec
	public Boolean IfFetchPlayerChar() { }
	// RVA: 0x24ac9f8 VA: 0x7594ac49f8
	private Void _HandleSetSupplyService(String topicId, List`1 charInstIds, Action onEnsure, Action dismissAction) { }
	// RVA: 0x24ad758 VA: 0x7594ac5758
	public Void .ctor() { }
}
```