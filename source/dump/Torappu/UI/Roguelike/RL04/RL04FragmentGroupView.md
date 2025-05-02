# RL04FragmentGroupView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GameObject _panelTitle`

- `GameObject _panelFragment`

- `GameObject _panelFragmentDetail`

- `GameObject _panelFragmentSummary`

- `GameObject _panelFoodUsed`

- `GameObject _panelFoodUnused`

- `SimpleLayoutContent _summaryContent`

- `SimpleLayoutContent _detailContent`

- `ILoadAsset <loader>k__BackingField`

- `Boolean m_hasInited`

- `Adapter m_detailAdapter`

- `Adapter m_summaryAdapter`


## Properties

- `ILoadAsset loader`


## Methods

- `ILoadAsset get_loader()`

- `Void set_loader(ILoadAsset)`

- `Void set_onItemClicked(Action`1)`

- `Void Render(RL04FragmentItemGroupViewModel, RoguelikeFragmentDialogListType)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentGroupView : MonoBehaviour, IHotfixable
{
	private GameObject _panelTitle; // 0x18
	private GameObject _panelFragment; // 0x20
	private GameObject _panelFragmentDetail; // 0x28
	private GameObject _panelFragmentSummary; // 0x30
	private TitleConfig[] _titleConfigList; // 0x38
	private GameObject _panelFoodUsed; // 0x40
	private GameObject _panelFoodUnused; // 0x48
	private SimpleLayoutContent _summaryContent; // 0x50
	private SimpleLayoutContent _detailContent; // 0x58
	private ILoadAsset <loader>k__BackingField; // 0x60
	private Action`1 <onItemClicked>k__BackingField; // 0x68
	private Boolean m_hasInited; // 0x70
	private Adapter m_detailAdapter; // 0x78
	private Adapter m_summaryAdapter; // 0x80
	private List`1 m_cachedFragmentList; // 0x88
	private static DelegateBridge __Hotfix0_get_loader; // 0x0
	private static DelegateBridge __Hotfix0_set_loader; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private ILoadAsset loader { get; set; }
	private Action`1 onItemClicked { get; set; }

	// RVA: 0x2b2560c VA: 0x759513d60c
	private ILoadAsset get_loader() { }
	// RVA: 0x2b25674 VA: 0x759513d674
	public Void set_loader(ILoadAsset value) { }
	// RVA: 0x2b256f8 VA: 0x759513d6f8
	private Action`1 get_onItemClicked() { }
	// RVA: 0x2b25760 VA: 0x759513d760
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x2b257e4 VA: 0x759513d7e4
	public Void Render(RL04FragmentItemGroupViewModel viewModel, RoguelikeFragmentDialogListType fragmentListType) { }
	// RVA: 0x2b259f4 VA: 0x759513d9f4
	private Void _InitIfNot() { }
	// RVA: 0x2b25ba8 VA: 0x759513dba8
	public Void .ctor() { }
}
```