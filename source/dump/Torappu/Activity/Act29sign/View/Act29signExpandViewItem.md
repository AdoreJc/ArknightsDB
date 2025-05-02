# Act29signExpandViewItem

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `GameObject _notSelectedView`

- `GameObject _selectedView`

- `GameObject _doneView`

- `GameObject _expandDoneView`

- `RectTransform _itemCardsContainer`

- `Single _rewardScale`

- `RectTransform _stepIconContainer`

- `RectTransform _topDescContainer`

- `RectTransform _topDescTextContainer`

- `RectTransform _topNumContainer`

- `RectTransform _btmDescContainer`

- `RectTransform _completeIconContainer`

- `UIAtlasImage _stepIcon`

- `HorizontalLayoutGroup _rewardLayoutGroup`

- `State m_state`


## Methods

- `Void Render(Model, Config)`

- `Void _ApplyConfig(Model, Config)`

- `Void _SetState(State)`

- `Void _RenderReward(List`1)`

- `Void _SetStepDescription(String)`

- `Void _RenderItemCard(UIItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signExpandViewItem : MonoBehaviour, IHotfixable
{
	private const Single ITEM_CARD_DISABLE; // 0x0
	private GameObject _notSelectedView; // 0x18
	private GameObject _selectedView; // 0x20
	private GameObject _doneView; // 0x28
	private GameObject _expandDoneView; // 0x30
	private RectTransform _itemCardsContainer; // 0x38
	private Single _rewardScale; // 0x40
	private Text[] _stepDescTexts; // 0x48
	private RectTransform _stepIconContainer; // 0x50
	private RectTransform _topDescContainer; // 0x58
	private RectTransform _topDescTextContainer; // 0x60
	private RectTransform _topNumContainer; // 0x68
	private RectTransform _btmDescContainer; // 0x70
	private RectTransform _completeIconContainer; // 0x78
	private UIAtlasImage _stepIcon; // 0x80
	private HorizontalLayoutGroup _rewardLayoutGroup; // 0x88
	private State m_state; // 0x90
	private List`1 m_itemCards; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__ApplyConfig; // 0x8
	private static DelegateBridge __Hotfix0__SetState; // 0x10
	private static DelegateBridge __Hotfix0__RenderReward; // 0x18
	private static DelegateBridge __Hotfix0__SetStepDescription; // 0x20
	private static DelegateBridge __Hotfix0__RenderItemCard; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x325dabc VA: 0x7595875abc
	public Void Render(Model model, Config config) { }
	// RVA: 0x325f70c VA: 0x759587770c
	private Void _ApplyConfig(Model model, Config config) { }
	// RVA: 0x325f4f4 VA: 0x75958774f4
	private Void _SetState(State state) { }
	// RVA: 0x325f364 VA: 0x7595877364
	private Void _RenderReward(List`1 bundleList) { }
	// RVA: 0x325f5bc VA: 0x75958775bc
	private Void _SetStepDescription(String text) { }
	// RVA: 0x325f920 VA: 0x7595877920
	private Void _RenderItemCard(UIItemViewModel viewModel) { }
	// RVA: 0x325fc24 VA: 0x7595877c24
	public Void .ctor() { }
}
```