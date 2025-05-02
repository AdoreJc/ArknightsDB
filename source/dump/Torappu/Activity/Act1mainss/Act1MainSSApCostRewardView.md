# Act1MainSSApCostRewardView

**Namespace:** `Torappu.Activity.Act1mainss`


## Fields

- `Single _rewardPresentDuration`

- `Single _rewardFadeDuration`

- `Transform _rewardItemHolder`

- `Single _rewardItemScale`

- `Text _rewardCountText`

- `GameObject _rewardCountPanel`

- `CanvasGroup _rewardGroup`

- `Image _rewardProgressFill`

- `Text _rewardProgressText`

- `GameObject _progressPanel`

- `GameObject _canClaimPanel`

- `UIItemCard m_itemCard`

- `Boolean m_cachedPresentCount`

- `Int32 m_presentIndex`

- `Tween m_presentTween`

- `Action <claimApRewardEvent>k__BackingField`


## Properties

- `Action claimApRewardEvent`


## Methods

- `Action get_claimApRewardEvent()`

- `Void set_claimApRewardEvent(Action)`

- `Void Render(Act1MainSSApCostRewardViewModel)`

- `Void OnClaimApRewardEvent()`

- `Void _GeneratePresentTween()`

- `Void _UpdateRewardItem(UIItemViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1mainss
public class Act1MainSSApCostRewardView : MonoBehaviour, IHotfixable
{
	private const String PROGRESS_FORMAT; // 0x0
	private const Int32 SHOW_COUNT_MAXIMUM_THRESHOLD; // 0x0
	private const String SHOW_COUNT_MAXIMUM_STRING; // 0x0
	private Single _rewardPresentDuration; // 0x18
	private Single _rewardFadeDuration; // 0x1c
	private Transform _rewardItemHolder; // 0x20
	private Single _rewardItemScale; // 0x28
	private Text _rewardCountText; // 0x30
	private GameObject _rewardCountPanel; // 0x38
	private CanvasGroup _rewardGroup; // 0x40
	private Image _rewardProgressFill; // 0x48
	private Text _rewardProgressText; // 0x50
	private GameObject _progressPanel; // 0x58
	private GameObject _canClaimPanel; // 0x60
	private UIItemCard m_itemCard; // 0x68
	private List`1 m_cachedPresentingItems; // 0x70
	private Boolean m_cachedPresentCount; // 0x78
	private Int32 m_presentIndex; // 0x7c
	private Tween m_presentTween; // 0x80
	private Action <claimApRewardEvent>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_claimApRewardEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_claimApRewardEvent; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClaimApRewardEvent; // 0x18
	private static DelegateBridge __Hotfix0__GeneratePresentTween; // 0x20
	private static DelegateBridge __Hotfix0__UpdateRewardItem; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action claimApRewardEvent { get; set; }

	// RVA: 0x3392720 VA: 0x75959aa720
	private Action get_claimApRewardEvent() { }
	// RVA: 0x3391d40 VA: 0x75959a9d40
	public Void set_claimApRewardEvent(Action value) { }
	// RVA: 0x3391dc4 VA: 0x75959a9dc4
	public Void Render(Act1MainSSApCostRewardViewModel viewModel) { }
	// RVA: 0x3393054 VA: 0x75959ab054
	public Void OnClaimApRewardEvent() { }
	// RVA: 0x3392c1c VA: 0x75959aac1c
	private Void _GeneratePresentTween() { }
	// RVA: 0x3392dd8 VA: 0x75959aadd8
	private Void _UpdateRewardItem(UIItemViewModel item, Boolean showCount) { }
	// RVA: 0x33930f0 VA: 0x75959ab0f0
	public Void .ctor() { }
}
```