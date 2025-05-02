# RoguelikeTopicBattlePassPurchaseWheelPickerView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `InertiaScrollViewPager _wheelPager`

- `UIRecycleLayoutGroup _content`

- `RoguelikeTopicBattlePassObjView _itemPrefab`

- `Single _itemWidth`

- `Boolean m_isInited`

- `ActionDelegate m_actionDelegate`

- `PagerAdapter m_adapter`

- `RoguelikeTopicBattlePassPurchaseViewModel m_cachedModel`

- `Int64 m_cachedWidgetId`

- `Int64 m_cachedDragId`


## Methods

- `Void _InitIfNot()`

- `Void Update()`

- `Void SetActionDelegate(ActionDelegate)`

- `Void Render(RoguelikeTopicBattlePassPurchaseViewModel)`

- `Void _OnScrollPagerStateChanged(State)`

- `Void _OnPageChangeStart()`

- `Void _OnPageChangeEnd(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassPurchaseWheelPickerView : MonoBehaviour, IHotfixable
{
	private InertiaScrollViewPager _wheelPager; // 0x18
	private UIRecycleLayoutGroup _content; // 0x20
	private RoguelikeTopicBattlePassObjView _itemPrefab; // 0x28
	private Single _itemWidth; // 0x30
	private Boolean m_isInited; // 0x34
	private ActionDelegate m_actionDelegate; // 0x38
	private PagerAdapter m_adapter; // 0x40
	private RoguelikeTopicBattlePassPurchaseViewModel m_cachedModel; // 0x48
	private Int64 m_cachedWidgetId; // 0x50
	private Int64 m_cachedDragId; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_SetActionDelegate; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__OnScrollPagerStateChanged; // 0x20
	private static DelegateBridge __Hotfix0__OnPageChangeStart; // 0x28
	private static DelegateBridge __Hotfix0__OnPageChangeEnd; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x263e978 VA: 0x7594c56978
	private Void _InitIfNot() { }
	// RVA: 0x263ebc0 VA: 0x7594c56bc0
	private Void Update() { }
	// RVA: 0x263d924 VA: 0x7594c55924
	public Void SetActionDelegate(ActionDelegate actionDelegate) { }
	// RVA: 0x263e110 VA: 0x7594c56110
	public Void Render(RoguelikeTopicBattlePassPurchaseViewModel viewModel) { }
	// RVA: 0x263ee44 VA: 0x7594c56e44
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x263efe8 VA: 0x7594c56fe8
	private Void _OnPageChangeStart() { }
	// RVA: 0x263ef34 VA: 0x7594c56f34
	private Void _OnPageChangeEnd(Int32 itemIndex) { }
	// RVA: 0x263f074 VA: 0x7594c57074
	public Void .ctor() { }
}
```