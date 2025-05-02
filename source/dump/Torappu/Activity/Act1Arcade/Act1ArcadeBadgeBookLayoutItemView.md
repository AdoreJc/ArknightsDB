# Act1ArcadeBadgeBookLayoutItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeBadgeBookItemHeadView _headView`

- `Act1ArcadeBadgeBookItemTailView _tailView`

- `ScrollRect <parentScroll>k__BackingField`


## Properties

- `ScrollRect parentScroll`


## Methods

- `ScrollRect get_parentScroll()`

- `Void set_parentScroll(ScrollRect)`

- `Void Render(String, Act1ArcadeBadgeBookItemViewModel, BadgeBookLayoutMode)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookLayoutItemView : MonoBehaviour, IHotfixable
{
	private Act1ArcadeBadgeBookItemHeadView _headView; // 0x18
	private Act1ArcadeBadgeBookItemTailView _tailView; // 0x20
	private ScrollRect <parentScroll>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_parentScroll; // 0x0
	private static DelegateBridge __Hotfix0_set_parentScroll; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private ScrollRect parentScroll { get; set; }

	// RVA: 0x33f7b74 VA: 0x7595a0fb74
	private ScrollRect get_parentScroll() { }
	// RVA: 0x33f5cf8 VA: 0x7595a0dcf8
	public Void set_parentScroll(ScrollRect value) { }
	// RVA: 0x33f5d7c VA: 0x7595a0dd7c
	public Void Render(String actId, Act1ArcadeBadgeBookItemViewModel model, BadgeBookLayoutMode layoutMode) { }
	// RVA: 0x33f7bdc VA: 0x7595a0fbdc
	public Void .ctor() { }
}
```