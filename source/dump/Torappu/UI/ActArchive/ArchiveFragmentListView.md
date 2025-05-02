# ArchiveFragmentListView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveFragmentListAdapter _adapter`

- `Boolean m_hasInited`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveFragmentListView : DataBinder`1, IHotfixable
{
	private ArchiveFragmentListAdapter _adapter; // 0x20
	private Boolean m_hasInited; // 0x28
	private Action`1 <onItemClicked>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClicked { get; set; }

	// RVA: 0x3055268 VA: 0x759566d268
	private Action`1 get_onItemClicked() { }
	// RVA: 0x3053778 VA: 0x759566b778
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x30552d0 VA: 0x759566d2d0
	public override Void OnValueChanged(FragmentProperty property) { }
	// RVA: 0x30553c0 VA: 0x759566d3c0
	private Void _InitIfNot() { }
	// RVA: 0x305545c VA: 0x759566d45c
	public Void .ctor() { }
}
```