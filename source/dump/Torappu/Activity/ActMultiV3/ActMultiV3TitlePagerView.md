# ActMultiV3TitlePagerView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `InertiaScrollViewPager _wheelPager`

- `UIRecycleLayoutGroup _content`

- `ActMultiV3TitleItemView _itemViewPrefab`

- `Boolean m_inited`

- `Boolean m_cachedIsBack`

- `Int64 m_dragContextID`

- `PagerAdapter m_adapter`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(ActMultiV3ManualTitleListModel, Boolean)`

- `Void Update()`

- `Void _InitIfNot()`

- `Void _ResetScrollIfNecessary(ActMultiV3ManualTitleListModel, Boolean)`

- `Void _OnScrollPagerStateChanged(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3TitlePagerView : MonoBehaviour, IHotfixable
{
	private InertiaScrollViewPager _wheelPager; // 0x18
	private UIRecycleLayoutGroup _content; // 0x20
	private ActMultiV3TitleItemView _itemViewPrefab; // 0x28
	private Boolean m_inited; // 0x30
	private Boolean m_cachedIsBack; // 0x31
	private Int64 m_dragContextID; // 0x38
	private PagerAdapter m_adapter; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__ResetScrollIfNecessary; // 0x18
	private static DelegateBridge __Hotfix0__OnScrollPagerStateChanged; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x311d6b8 VA: 0x75957356b8
	public Void Render(ActMultiV3ManualTitleListModel model, Boolean fastMode) { }
	// RVA: 0x311e870 VA: 0x7595736870
	private Void Update() { }
	// RVA: 0x311e124 VA: 0x7595736124
	private Void _InitIfNot() { }
	// RVA: 0x311e798 VA: 0x7595736798
	private Void _ResetScrollIfNecessary(ActMultiV3ManualTitleListModel model, Boolean fastMode) { }
	// RVA: 0x311eaf0 VA: 0x7595736af0
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x311ed18 VA: 0x7595736d18
	public Void .ctor() { }
}
```