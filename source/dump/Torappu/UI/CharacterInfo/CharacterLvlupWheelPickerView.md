# CharacterLvlupWheelPickerView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `InertiaScrollViewPager _wheelPager`

- `UIRecycleLayoutGroup _content`

- `CharacterLvlupWheelItemView _itemPrefab`

- `Color _colorAttainableNum`

- `Color _colorAttainableShadow`

- `Color _colorAttainableNumSelected`

- `Color _colorAttainableShadowSelected`

- `Color _colorUnattainableNum`

- `Color _colorUnattainableShadow`

- `Color _colorUnattainableNumSelected`

- `Color _colorUnattainableShadowSelected`

- `Boolean m_isInited`

- `PagerAdapter m_adapter`

- `Boolean m_isScrolling`

- `ColorParam m_colorParam`

- `ActionDelegate m_actionDelegate`

- `Int64 m_dragContextID`


## Methods

- `Void SetActionDelegate(ActionDelegate)`

- `Void Render(CharacterLvlupWheelViewModel)`

- `Void Update()`

- `Void _InitIfNot()`

- `Void _OnScrollPagerStateChanged(State)`

- `Void _OnPageChangeEnd(Int32)`

- `Void _OnItemClicked(Int32)`

- `Void _ResetScrollIfNecessary(CharacterLvlupWheelViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupWheelPickerView : MonoBehaviour, IHotfixable
{
	private InertiaScrollViewPager _wheelPager; // 0x18
	private UIRecycleLayoutGroup _content; // 0x20
	private CharacterLvlupWheelItemView _itemPrefab; // 0x28
	private Color _colorAttainableNum; // 0x30
	private Color _colorAttainableShadow; // 0x40
	private Color _colorAttainableNumSelected; // 0x50
	private Color _colorAttainableShadowSelected; // 0x60
	private Color _colorUnattainableNum; // 0x70
	private Color _colorUnattainableShadow; // 0x80
	private Color _colorUnattainableNumSelected; // 0x90
	private Color _colorUnattainableShadowSelected; // 0xa0
	private Boolean m_isInited; // 0xb0
	private PagerAdapter m_adapter; // 0xb8
	private Boolean m_isScrolling; // 0xc0
	private ColorParam m_colorParam; // 0xc4
	private ActionDelegate m_actionDelegate; // 0x148
	private Int64 m_dragContextID; // 0x150
	private List`1 m_maxAttainableFrameList; // 0x158
	private static DelegateBridge __Hotfix0_SetActionDelegate; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnScrollPagerStateChanged; // 0x20
	private static DelegateBridge __Hotfix0__OnPageChangeEnd; // 0x28
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x30
	private static DelegateBridge __Hotfix0__ResetScrollIfNecessary; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d76024 VA: 0x759538e024
	public Void SetActionDelegate(ActionDelegate actionDelegate) { }
	// RVA: 0x2d75bb4 VA: 0x759538dbb4
	public Void Render(CharacterLvlupWheelViewModel viewModel) { }
	// RVA: 0x2d7a368 VA: 0x7595392368
	private Void Update() { }
	// RVA: 0x2d79ca8 VA: 0x7595391ca8
	private Void _InitIfNot() { }
	// RVA: 0x2d7a6b4 VA: 0x75953926b4
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x2d7a798 VA: 0x7595392798
	private Void _OnPageChangeEnd(Int32 itemIndex) { }
	// RVA: 0x2d7a844 VA: 0x7595392844
	private Void _OnItemClicked(Int32 pageIndex) { }
	// RVA: 0x2d7a290 VA: 0x7595392290
	private Void _ResetScrollIfNecessary(CharacterLvlupWheelViewModel viewModel) { }
	// RVA: 0x2d7a8ec VA: 0x75953928ec
	public Void .ctor() { }
}
```