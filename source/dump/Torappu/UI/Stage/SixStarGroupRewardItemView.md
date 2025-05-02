# SixStarGroupRewardItemView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _panelSelected`

- `RectTransform _itemCardContainer`

- `Single _itemCardScale`

- `Text _textName`

- `Text _textAp`

- `String m_cachedStageId`

- `UIStateFinder m_stateFinder`

- `UIItemCard m_itemCard`

- `Boolean m_hasInited`


## Methods

- `Void Render(StageViewModel, Boolean)`

- `Void EventOnRewardClicked()`

- `Void _InitIfNot()`

- `Void _EventOnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarGroupRewardItemView : MonoBehaviour, IHotfixable
{
	private const String AP_COST_FORMAT; // 0x0
	private GameObject _panelSelected; // 0x18
	private RectTransform _itemCardContainer; // 0x20
	private Single _itemCardScale; // 0x28
	private Text _textName; // 0x30
	private Text _textAp; // 0x38
	private String m_cachedStageId; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private UIItemCard m_itemCard; // 0x58
	private Boolean m_hasInited; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnRewardClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__EventOnItemCardClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f1a448 VA: 0x7595532448
	public Void Render(StageViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x2f1a858 VA: 0x7595532858
	public Void EventOnRewardClicked() { }
	// RVA: 0x2f1a650 VA: 0x7595532650
	private Void _InitIfNot() { }
	// RVA: 0x2f1a948 VA: 0x7595532948
	private Void _EventOnItemCardClicked(Int32 _) { }
	// RVA: 0x2f1aa50 VA: 0x7595532a50
	public Void .ctor() { }
}
```