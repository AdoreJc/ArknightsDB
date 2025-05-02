# Act1ArcadeBadgeBookItemTailView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Text _nameText`

- `Text _buffRangeDescText`

- `SimpleLayoutContent _tierContent`

- `UIWrappedScrollRect _scrollRect`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `ScrollRect <parentScroll>k__BackingField`


## Properties

- `ScrollRect parentScroll`


## Methods

- `ScrollRect get_parentScroll()`

- `Void set_parentScroll(ScrollRect)`

- `Void Render(String, Act1ArcadeBadgeBookItemViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookItemTailView : MonoBehaviour, IHotfixable
{
	private Text _nameText; // 0x18
	private Text _buffRangeDescText; // 0x20
	private SimpleLayoutContent _tierContent; // 0x28
	private UIWrappedScrollRect _scrollRect; // 0x30
	private Boolean m_hasInited; // 0x38
	private Adapter m_adapter; // 0x40
	private ScrollRect <parentScroll>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_parentScroll; // 0x0
	private static DelegateBridge __Hotfix0_set_parentScroll; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ScrollRect parentScroll { get; set; }

	// RVA: 0x33f6f0c VA: 0x7595a0ef0c
	private ScrollRect get_parentScroll() { }
	// RVA: 0x33f6f74 VA: 0x7595a0ef74
	public Void set_parentScroll(ScrollRect value) { }
	// RVA: 0x33f6ff8 VA: 0x7595a0eff8
	public Void Render(String actId, Act1ArcadeBadgeBookItemViewModel model) { }
	// RVA: 0x33f7150 VA: 0x7595a0f150
	private Void _InitIfNot() { }
	// RVA: 0x33f7400 VA: 0x7595a0f400
	public Void .ctor() { }
}
```