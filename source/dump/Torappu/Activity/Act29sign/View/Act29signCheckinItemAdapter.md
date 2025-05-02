# Act29signCheckinItemAdapter

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `Act29signCheckinItemViewHolder _viewHolderPrefab`

- `UnityAction <onSpecialItemClicked>k__BackingField`


## Properties

- `UnityAction onSpecialItemClicked`


## Methods

- `Void set_onNormalItemClicked(UnityAction`1)`

- `UnityAction get_onSpecialItemClicked()`

- `Void set_onSpecialItemClicked(UnityAction)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signCheckinItemAdapter : RecycleLoopScrollAdapter`2
{
	private Act29signCheckinItemViewHolder _viewHolderPrefab; // 0x68
	private UnityAction`1 <onNormalItemClicked>k__BackingField; // 0x70
	private UnityAction <onSpecialItemClicked>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onNormalItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onNormalItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onSpecialItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onSpecialItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private UnityAction`1 onNormalItemClicked { get; set; }
	private UnityAction onSpecialItemClicked { get; set; }

	// RVA: 0x325fe4c VA: 0x7595877e4c
	private UnityAction`1 get_onNormalItemClicked() { }
	// RVA: 0x325feb4 VA: 0x7595877eb4
	public Void set_onNormalItemClicked(UnityAction`1 value) { }
	// RVA: 0x325ff38 VA: 0x7595877f38
	private UnityAction get_onSpecialItemClicked() { }
	// RVA: 0x325ffa0 VA: 0x7595877fa0
	public Void set_onSpecialItemClicked(UnityAction value) { }
	// RVA: 0x3260024 VA: 0x7595878024
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, Act29signSpecialCheckinItemViewModel data) { }
	// RVA: 0x3260594 VA: 0x7595878594
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x326068c VA: 0x759587868c
	public Void .ctor() { }
}
```