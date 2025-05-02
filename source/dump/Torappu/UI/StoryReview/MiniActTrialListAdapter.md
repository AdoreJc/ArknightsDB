# MiniActTrialListAdapter

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `GameObject _itemTemplate`

- `IDragHandler parentScroll`


## Methods

- `Void set_onChapterClick(Action`1)`

- `Void set_onTrialCollect(Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActTrialListAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _itemTemplate; // 0x68
	public IDragHandler parentScroll; // 0x70
	private Action`1 <onChapterClick>k__BackingField; // 0x78
	private Action`2 <onTrialCollect>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_onChapterClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onChapterClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onTrialCollect; // 0x10
	private static DelegateBridge __Hotfix0_set_onTrialCollect; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onChapterClick { get; set; }
	private Action`2 onTrialCollect { get; set; }

	// RVA: 0x274b240 VA: 0x7594d63240
	private Action`1 get_onChapterClick() { }
	// RVA: 0x2748dfc VA: 0x7594d60dfc
	public Void set_onChapterClick(Action`1 value) { }
	// RVA: 0x274b2a8 VA: 0x7594d632a8
	private Action`2 get_onTrialCollect() { }
	// RVA: 0x2748e80 VA: 0x7594d60e80
	public Void set_onTrialCollect(Action`2 value) { }
	// RVA: 0x274b310 VA: 0x7594d63310
	public override Void UpdateView(Int32 position, GameObject view, MiniActTrialItemHolder holder, MiniActTrialItemModel data) { }
	// RVA: 0x274b478 VA: 0x7594d63478
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x274b534 VA: 0x7594d63534
	public Void .ctor() { }
}
```