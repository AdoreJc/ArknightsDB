# RL04AlchemyFragmentListItemNormalViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04AlchemyFragmentItemViewModel m_fragmentItemViewModel`


## Properties

- `RL04AlchemyFragmentItemViewModel fragmentItemViewModel`

- `Boolean isSelected`

- `String instId`

- `Boolean isEmpty`


## Methods

- `RL04AlchemyFragmentItemViewModel get_fragmentItemViewModel()`

- `Boolean get_isSelected()`

- `String get_instId()`

- `Boolean get_isEmpty()`

- `Void LoadData(RL04AlchemyFragmentItemViewModel)`

- `Int32 CompareTo(RL04AlchemyFragmentListItemNormalViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyFragmentListItemNormalViewModel : IComparable`1, IHotfixable
{
	private RL04AlchemyFragmentItemViewModel m_fragmentItemViewModel; // 0x10
	private static DelegateBridge __Hotfix0_get_fragmentItemViewModel; // 0x0
	private static DelegateBridge __Hotfix0_get_isSelected; // 0x8
	private static DelegateBridge __Hotfix0_get_instId; // 0x10
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_CompareTo; // 0x28
	private static DelegateBridge __Hotfix0__TypeComparison; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public RL04AlchemyFragmentItemViewModel fragmentItemViewModel { get; }
	public Boolean isSelected { get; }
	public String instId { get; }
	public Boolean isEmpty { get; }

	// RVA: 0x2b00064 VA: 0x7595118064
	public RL04AlchemyFragmentItemViewModel get_fragmentItemViewModel() { }
	// RVA: 0x2b000cc VA: 0x75951180cc
	public Boolean get_isSelected() { }
	// RVA: 0x2b001c0 VA: 0x75951181c0
	public String get_instId() { }
	// RVA: 0x2b002d4 VA: 0x75951182d4
	public Boolean get_isEmpty() { }
	// RVA: 0x2b00364 VA: 0x7595118364
	public Void LoadData(RL04AlchemyFragmentItemViewModel itemViewModel) { }
	// RVA: 0x2b003e8 VA: 0x75951183e8
	public Int32 CompareTo(RL04AlchemyFragmentListItemNormalViewModel other) { }
	// RVA: 0x2b0055c VA: 0x759511855c
	private static Int32 _TypeComparison(RoguelikeFragmentType x, RoguelikeFragmentType y) { }
	// RVA: 0x2b00830 VA: 0x7595118830
	public Void .ctor() { }
}
```