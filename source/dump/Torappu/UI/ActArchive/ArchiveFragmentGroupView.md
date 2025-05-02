# ArchiveFragmentGroupView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _panelTitle`

- `GameObject _panelFragment`

- `SimpleLayoutContent _fragmentContent`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `Boolean m_cachedShowSwitchAnim`

- `String m_cachedSelectedItemId`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Void Render(ArchiveFragmentGroupModel, Boolean, String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveFragmentGroupView : MonoBehaviour, IHotfixable
{
	private GameObject _panelTitle; // 0x18
	private GameObject _panelFragment; // 0x20
	private SimpleLayoutContent _fragmentContent; // 0x28
	private TitleConfig[] _titleConfigList; // 0x30
	private Boolean m_hasInited; // 0x38
	private Adapter m_adapter; // 0x40
	private List`1 m_itemModelList; // 0x48
	private Boolean m_cachedShowSwitchAnim; // 0x50
	private String m_cachedSelectedItemId; // 0x58
	private Action`1 <onItemClicked>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClicked { get; set; }

	// RVA: 0x30539ec VA: 0x759566b9ec
	private Action`1 get_onItemClicked() { }
	// RVA: 0x3053a54 VA: 0x759566ba54
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x3053ad8 VA: 0x759566bad8
	public Void Render(ArchiveFragmentGroupModel model, Boolean showSwitchAnim, String selectedItemId) { }
	// RVA: 0x3053c98 VA: 0x759566bc98
	private Void _InitIfNot() { }
	// RVA: 0x3053dfc VA: 0x759566bdfc
	public Void .ctor() { }
}
```