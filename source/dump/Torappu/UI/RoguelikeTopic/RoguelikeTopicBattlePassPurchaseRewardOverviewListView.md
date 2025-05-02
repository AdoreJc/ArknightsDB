# RoguelikeTopicBattlePassPurchaseRewardOverviewListView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Int32 _columnCount`

- `UIRecycleLayoutGroup _itemGroup`

- `RoguelikeTopicBattlePassPurchaseRewardOverviewRowView _rowPrefab`

- `Int32 _rowHeightEnd`

- `Int32 _rowHeightNormal`

- `RoguelikeTopicBattlePassPurchaseOverviewViewModel m_cachedModel`

- `RoguelikeTopicBattlePassStyle m_style`

- `Adapter m_adapter`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void Init(RoguelikeTopicBattlePassStyle)`

- `Void Render(RoguelikeTopicBattlePassPurchaseOverviewViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassPurchaseRewardOverviewListView : MonoBehaviour, IHotfixable
{
	private Int32 _columnCount; // 0x18
	private UIRecycleLayoutGroup _itemGroup; // 0x20
	private RoguelikeTopicBattlePassPurchaseRewardOverviewRowView _rowPrefab; // 0x28
	private Int32 _rowHeightEnd; // 0x30
	private Int32 _rowHeightNormal; // 0x34
	private RoguelikeTopicBattlePassPurchaseOverviewViewModel m_cachedModel; // 0x38
	private RoguelikeTopicBattlePassStyle m_style; // 0x40
	private Adapter m_adapter; // 0x48
	private Boolean m_inited; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2639a18 VA: 0x7594c51a18
	private Void _InitIfNot() { }
	// RVA: 0x2638a9c VA: 0x7594c50a9c
	public Void Init(RoguelikeTopicBattlePassStyle style) { }
	// RVA: 0x2638990 VA: 0x7594c50990
	public Void Render(RoguelikeTopicBattlePassPurchaseOverviewViewModel viewModel) { }
	// RVA: 0x2639c64 VA: 0x7594c51c64
	public Void .ctor() { }
}
```