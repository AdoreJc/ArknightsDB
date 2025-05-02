# CommonSingleChooseCharGroupView

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `Text _txtTitle`

- `UIRecycleVerticalLayoutGroup _recycleLayout`

- `ScrollRect _scrollRect`

- `CancelDragIfFits _cancelDragIfFits`

- `CommonChooseCharCardView _cardViewPrefab`

- `Boolean m_hasInited`

- `Adapter m_adapter`


## Methods

- `T GetBuilder()`

- `Void Render(AbstractViewBuilder)`

- `Void _InitIfNot()`

- `Void <Render>b__11_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class CommonSingleChooseCharGroupView : MonoBehaviour, IHotfixable
{
	private Text _txtTitle; // 0x18
	private UIRecycleVerticalLayoutGroup _recycleLayout; // 0x20
	private ScrollRect _scrollRect; // 0x28
	private CancelDragIfFits _cancelDragIfFits; // 0x30
	private CommonChooseCharCardView _cardViewPrefab; // 0x38
	private Boolean m_hasInited; // 0x40
	private Adapter m_adapter; // 0x48
	private IList`1 m_views; // 0x50
	private static DelegateBridge __Hotfix0_GetBuilder; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x VA: 0x0
	public T GetBuilder() { }
	// RVA: 0x2c3d22c VA: 0x759525522c
	public Void Render(AbstractViewBuilder viewBuilder) { }
	// RVA: 0x2c3d390 VA: 0x7595255390
	private Void _InitIfNot() { }
	// RVA: 0x2c3d630 VA: 0x7595255630
	public Void .ctor() { }
	// RVA: 0x2c3d6a0 VA: 0x75952556a0
	private Void <Render>b__11_0() { }
}
```