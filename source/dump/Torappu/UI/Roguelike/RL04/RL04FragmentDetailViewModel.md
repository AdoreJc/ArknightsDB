# RL04FragmentDetailViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Int32 selectIndex`

- `Boolean isFirst`

- `Boolean isLast`

- `Boolean isEnter`

- `Boolean hasCurrInspiration`

- `RL04FragmentDetailWeightViewModel weightModel`

- `RoguelikeFragmentDialogMode mode`

- `Int32 m_entrySelectIndex`


## Methods

- `Void LoadData(Options)`

- `Void SelectNextItem()`

- `Void SelectPrevItem()`

- `Int32 GetFocusItemIndex(Boolean)`

- `Void _RefreshStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentDetailViewModel : IHotfixable
{
	public List`1 fragmentList; // 0x10
	public Int32 selectIndex; // 0x18
	public Boolean isFirst; // 0x1c
	public Boolean isLast; // 0x1d
	public Boolean isEnter; // 0x1e
	public Boolean hasCurrInspiration; // 0x1f
	public RL04FragmentDetailWeightViewModel weightModel; // 0x20
	public RoguelikeFragmentDialogMode mode; // 0x28
	private Int32 m_entrySelectIndex; // 0x2c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SelectNextItem; // 0x8
	private static DelegateBridge __Hotfix0_SelectPrevItem; // 0x10
	private static DelegateBridge __Hotfix0_GetFocusItemIndex; // 0x18
	private static DelegateBridge __Hotfix0__RefreshStatus; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b1fbf0 VA: 0x7595137bf0
	public Void LoadData(Options input) { }
	// RVA: 0x2b20384 VA: 0x7595138384
	public Void SelectNextItem() { }
	// RVA: 0x2b204c4 VA: 0x75951384c4
	public Void SelectPrevItem() { }
	// RVA: 0x2b1ff68 VA: 0x7595137f68
	public Int32 GetFocusItemIndex(Boolean isRemoved) { }
	// RVA: 0x2b22854 VA: 0x759513a854
	private Void _RefreshStatus() { }
	// RVA: 0x2b22930 VA: 0x759513a930
	public Void .ctor() { }
}
```