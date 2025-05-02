# Act1ArcadeBadgeBookGroupView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Text _groupDescText`

- `GameObject _showTailPanel`

- `GameObject _hideTailPanel`

- `SimpleLayoutContent _groupItemContent`

- `GridLayoutGroup _contentLayout`

- `Vector2 _showTailCellSize`

- `Vector2 _hideTailCellSize`

- `CrossAppShareStartLayoutContent _shareLayoutContent`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `ScrollRect <parentScroll>k__BackingField`


## Properties

- `ScrollRect parentScroll`


## Methods

- `ScrollRect get_parentScroll()`

- `Void set_parentScroll(ScrollRect)`

- `Void Render(String, Act1ArcadeBadgeBookGroupViewModel, BadgeBookLayoutMode)`

- `RectTransform GetItemRectByIndex(Int32)`

- `CrossAppShareTextModel GenerateGroupNameTextModel()`

- `CrossAppShareLayoutContentModel GenerateGroupLayoutContentModel()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookGroupView : MonoBehaviour, IHotfixable
{
	private List`1 _groupNameTexts; // 0x18
	private Text _groupDescText; // 0x20
	private GameObject _showTailPanel; // 0x28
	private GameObject _hideTailPanel; // 0x30
	private SimpleLayoutContent _groupItemContent; // 0x38
	private GridLayoutGroup _contentLayout; // 0x40
	private Vector2 _showTailCellSize; // 0x48
	private Vector2 _hideTailCellSize; // 0x50
	private CrossAppShareStartLayoutContent _shareLayoutContent; // 0x58
	private Boolean m_hasInited; // 0x60
	private Adapter m_adapter; // 0x68
	private ScrollRect <parentScroll>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_parentScroll; // 0x0
	private static DelegateBridge __Hotfix0_set_parentScroll; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_GetItemRectByIndex; // 0x18
	private static DelegateBridge __Hotfix0_GenerateGroupNameTextModel; // 0x20
	private static DelegateBridge __Hotfix0_GenerateGroupLayoutContentModel; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ScrollRect parentScroll { get; set; }

	// RVA: 0x33f4f08 VA: 0x7595a0cf08
	private ScrollRect get_parentScroll() { }
	// RVA: 0x33f4f70 VA: 0x7595a0cf70
	public Void set_parentScroll(ScrollRect value) { }
	// RVA: 0x33f4ff4 VA: 0x7595a0cff4
	public Void Render(String actId, Act1ArcadeBadgeBookGroupViewModel model, BadgeBookLayoutMode layoutMode) { }
	// RVA: 0x33f54f0 VA: 0x7595a0d4f0
	public RectTransform GetItemRectByIndex(Int32 index) { }
	// RVA: 0x33f55f4 VA: 0x7595a0d5f4
	public CrossAppShareTextModel GenerateGroupNameTextModel() { }
	// RVA: 0x33f56c4 VA: 0x7595a0d6c4
	public CrossAppShareLayoutContentModel GenerateGroupLayoutContentModel() { }
	// RVA: 0x33f5280 VA: 0x7595a0d280
	private Void _InitIfNot() { }
	// RVA: 0x33f582c VA: 0x7595a0d82c
	public Void .ctor() { }
}
```