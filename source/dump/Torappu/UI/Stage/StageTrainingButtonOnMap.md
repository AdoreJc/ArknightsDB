# StageTrainingButtonOnMap

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _panelActive`

- `GameObject _panelChainedLock`

- `Text _textChainedLock`

- `GameObject _panelSingleLock`

- `Single _itemScaler`

- `RectTransform _itemCardSlotMain`

- `RectTransform _itemCardSlotSub`

- `ViewModelCache m_cache`

- `Boolean m_isinited`

- `UIItemCard m_itemCardMain`

- `UIItemCard m_itemCardSub`

- `UIItemViewModel m_diamondViewModel`

- `UIItemViewModel m_charViewModel`


## Methods

- `Void _RenderMain(StageTrainingButtonHolder)`

- `Void _RenderRewards(StageViewModel)`

- `UIItemCard _CreateItemCard(RectTransform)`

- `String _ParseChainedLockedStr(String)`

- `Boolean <>xLuaBaseProxy_TryLockStage(StageButtonOnMapHolder, StageViewModel, ZoneViewModel, Boolean)`

- `Void <>xLuaBaseProxy_RenderStage(StageButtonOnMapHolder, StageViewModel, ZoneViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageTrainingButtonOnMap : StageButtonOnMap
{
	private GameObject _panelActive; // 0xd8
	private GameObject _panelChainedLock; // 0xe0
	private Text _textChainedLock; // 0xe8
	private GameObject _panelSingleLock; // 0xf0
	private Single _itemScaler; // 0xf8
	private RectTransform _itemCardSlotMain; // 0x100
	private RectTransform _itemCardSlotSub; // 0x108
	private ViewModelCache m_cache; // 0x110
	private Boolean m_isinited; // 0x113
	private UIItemCard m_itemCardMain; // 0x118
	private UIItemCard m_itemCardSub; // 0x120
	private UIItemViewModel m_diamondViewModel; // 0x128
	private UIItemViewModel m_charViewModel; // 0x130
	private static DelegateBridge __Hotfix0_TryLockStage; // 0x0
	private static DelegateBridge __Hotfix0_RenderStage; // 0x8
	private static DelegateBridge __Hotfix0__RenderMain; // 0x10
	private static DelegateBridge __Hotfix0__RenderRewards; // 0x18
	private static DelegateBridge __Hotfix0__CreateItemCard; // 0x20
	private static DelegateBridge __Hotfix0__ParseChainedLockedStr; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2fb0c60 VA: 0x75955c8c60
	protected override Boolean TryLockStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x2fb0cfc VA: 0x75955c8cfc
	public override Void RenderStage(StageButtonOnMapHolder rawHolder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x2fb0fc8 VA: 0x75955c8fc8
	private Void _RenderMain(StageTrainingButtonHolder holder) { }
	// RVA: 0x2fb10a8 VA: 0x75955c90a8
	private Void _RenderRewards(StageViewModel viewModel) { }
	// RVA: 0x2fb1574 VA: 0x75955c9574
	private UIItemCard _CreateItemCard(RectTransform container) { }
	// RVA: 0x2fb13e4 VA: 0x75955c93e4
	private String _ParseChainedLockedStr(String stageId) { }
	// RVA: 0x2fb16e8 VA: 0x75955c96e8
	public Void .ctor() { }
	// RVA: 0x2fb1760 VA: 0x75955c9760
	private Boolean <>xLuaBaseProxy_TryLockStage(StageButtonOnMapHolder P0, StageViewModel P1, ZoneViewModel P2, Boolean P3) { }
	// RVA: 0x2fb1768 VA: 0x75955c9768
	private Void <>xLuaBaseProxy_RenderStage(StageButtonOnMapHolder P0, StageViewModel P1, ZoneViewModel P2, Boolean P3) { }
}
```