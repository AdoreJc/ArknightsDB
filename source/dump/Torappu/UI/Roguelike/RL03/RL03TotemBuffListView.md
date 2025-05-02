# RL03TotemBuffListView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RL03TotemListTitleItemView _titleItemPrefab`

- `RL03TotemListItemView _itemPrefab`

- `UIRecycleVerticalLayoutGroup _recycleList`

- `RL03TotemListAdapter m_adapter`

- `Boolean m_isInited`

- `Int32 m_cachedSequenceNum`


## Methods

- `Void set_onItemClick(Action`2)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffListView : DataBinder`1
{
	private RL03TotemListTitleItemView _titleItemPrefab; // 0x20
	private RL03TotemListItemView _itemPrefab; // 0x28
	private UIRecycleVerticalLayoutGroup _recycleList; // 0x30
	private RL03TotemListAdapter m_adapter; // 0x38
	private Boolean m_isInited; // 0x40
	private Int32 m_cachedSequenceNum; // 0x44
	private Action`2 <onItemClick>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`2 onItemClick { get; set; }

	// RVA: 0x2ba7af4 VA: 0x75951bfaf4
	public Void set_onItemClick(Action`2 value) { }
	// RVA: 0x2ba7b78 VA: 0x75951bfb78
	private Action`2 get_onItemClick() { }
	// RVA: 0x2ba7be0 VA: 0x75951bfbe0
	public override Void OnValueChanged(RL03TotemListViewProperty property) { }
	// RVA: 0x2ba7cd8 VA: 0x75951bfcd8
	private Void _InitIfNot() { }
	// RVA: 0x2ba8614 VA: 0x75951c0614
	public Void .ctor() { }
}
```