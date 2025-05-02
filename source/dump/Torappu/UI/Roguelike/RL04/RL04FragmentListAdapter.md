# RL04FragmentListAdapter

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GameObject _itemPrefab`

- `Int32 m_cachedFocusSequence`

- `RoguelikeFragmentDialogListType m_cachedListType`

- `ILoadAsset <loader>k__BackingField`


## Properties

- `ILoadAsset loader`


## Methods

- `ILoadAsset get_loader()`

- `Void set_loader(ILoadAsset)`

- `Void set_onItemClicked(Action`1)`

- `Void RenderFragmentList(RL04FragmentViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentListAdapter : LoopScrollAdapter`2, IHotfixable
{
	private GameObject _itemPrefab; // 0x58
	private Int32 m_cachedFocusSequence; // 0x60
	private RoguelikeFragmentDialogListType m_cachedListType; // 0x64
	private ILoadAsset <loader>k__BackingField; // 0x68
	private Action`1 <onItemClicked>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_loader; // 0x0
	private static DelegateBridge __Hotfix0_set_loader; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_RenderFragmentList; // 0x20
	private static DelegateBridge __Hotfix0_CreateView; // 0x28
	private static DelegateBridge __Hotfix0_UpdateView; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ILoadAsset loader { get; set; }
	private Action`1 onItemClicked { get; set; }

	// RVA: 0x2b25ea4 VA: 0x759513dea4
	private ILoadAsset get_loader() { }
	// RVA: 0x2b25f0c VA: 0x759513df0c
	public Void set_loader(ILoadAsset value) { }
	// RVA: 0x2b25f90 VA: 0x759513df90
	private Action`1 get_onItemClicked() { }
	// RVA: 0x2b25ff8 VA: 0x759513dff8
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x2b2607c VA: 0x759513e07c
	public Void RenderFragmentList(RL04FragmentViewModel model) { }
	// RVA: 0x2b26290 VA: 0x759513e290
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2b26350 VA: 0x759513e350
	public override Void UpdateView(Int32 position, GameObject viewObj, ViewHolder holder, RL04FragmentItemGroupViewModel data) { }
	// RVA: 0x2b264d8 VA: 0x759513e4d8
	public Void .ctor() { }
}
```