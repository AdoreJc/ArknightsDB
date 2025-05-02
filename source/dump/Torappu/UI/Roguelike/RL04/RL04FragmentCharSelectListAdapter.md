# RL04FragmentCharSelectListAdapter

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GameObject _viewPrefab`


## Methods

- `Void set_selectedChar(List`1)`

- `Void set_onCardClicked(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentCharSelectListAdapter : LoopScrollAdapter`2
{
	private GameObject _viewPrefab; // 0x58
	private List`1 <selectedChar>k__BackingField; // 0x60
	private Action`1 <onCardClicked>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_selectedChar; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedChar; // 0x8
	private static DelegateBridge __Hotfix0_get_onCardClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onCardClicked; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_CreateView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public List`1 selectedChar { get; set; }
	public Action`1 onCardClicked { get; set; }

	// RVA: 0x2b1f44c VA: 0x759513744c
	public List`1 get_selectedChar() { }
	// RVA: 0x2b1d4cc VA: 0x75951354cc
	public Void set_selectedChar(List`1 value) { }
	// RVA: 0x2b1f4b4 VA: 0x75951374b4
	public Action`1 get_onCardClicked() { }
	// RVA: 0x2b1d448 VA: 0x7595135448
	public Void set_onCardClicked(Action`1 value) { }
	// RVA: 0x2b1f51c VA: 0x759513751c
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, RL04FragmentCharViewModel data) { }
	// RVA: 0x2b1f6d8 VA: 0x75951376d8
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2b1f798 VA: 0x7595137798
	public Void .ctor() { }
}
```