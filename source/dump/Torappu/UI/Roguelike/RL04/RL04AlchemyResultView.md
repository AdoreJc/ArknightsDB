# RL04AlchemyResultView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `GameObject _objRewardSingle`

- `RectTransform _backBtnForSingleReward`

- `GameObject _objRewardMultiChoice`

- `GameObject _objSsrRewards`

- `SimpleLayoutContent _ssrListContent`

- `GameObject _objOtherRewards`

- `RoguelikeRewardListLayout _otherListLayout`

- `UIIntEvent _onOtherRewardItemClick`

- `UIAnimationLocation _entryAnim`

- `CanvasGroup _canvasGroup`

- `Text _txtTitle`

- `RoguelikeRewardStyle <rewardUiStyle>k__BackingField`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `Boolean m_cachedOtherListLayoutInited`

- `Boolean m_cachedSsrListLayoutInited`

- `SsrRewardsAdapter m_ssrRewardsAdapter`

- `ShowHideSwitchTween m_switchTween`


## Properties

- `RoguelikeRewardStyle rewardUiStyle`


## Methods

- `RoguelikeRewardStyle get_rewardUiStyle()`

- `Void set_rewardUiStyle(RoguelikeRewardStyle)`

- `Void Show(RL04AlchemyResultViewModel)`

- `Void Hide()`

- `Void OnClickBackBtn()`

- `Void OnOtherRewardItemClick(Int32)`

- `Void _ShowView(Boolean)`

- `Void _RenderTitle(ResultState, Boolean)`

- `Void _RenderRewardData(RL04AlchemyResultViewModel)`

- `Void _PlayAlchemyResultAudio(ResultState)`

- `Void _RenderOtherRewards(RoguelikeRewardListViewModel)`

- `Void _InitOtherListLayout(String)`

- `Void _RenderSsrRewards(List`1)`

- `Void _InitSsrListLayout()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyResultView : MonoBehaviour, IHotfixable
{
	private GameObject _objRewardSingle; // 0x18
	private RectTransform _backBtnForSingleReward; // 0x20
	private GameObject _objRewardMultiChoice; // 0x28
	private GameObject _objSsrRewards; // 0x30
	private SimpleLayoutContent _ssrListContent; // 0x38
	private GameObject _objOtherRewards; // 0x40
	private RoguelikeRewardListLayout _otherListLayout; // 0x48
	private UIIntEvent _onOtherRewardItemClick; // 0x50
	private UIAnimationLocation _entryAnim; // 0x58
	private CanvasGroup _canvasGroup; // 0x68
	private Text _txtTitle; // 0x70
	private RoguelikeRewardStyle <rewardUiStyle>k__BackingField; // 0x78
	private Boolean m_isInited; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private Boolean m_cachedOtherListLayoutInited; // 0x98
	private Boolean m_cachedSsrListLayoutInited; // 0x99
	private List`1 m_cachedSsrItemViewList; // 0xa0
	private SsrRewardsAdapter m_ssrRewardsAdapter; // 0xa8
	private ShowHideSwitchTween m_switchTween; // 0xb0
	private static DelegateBridge __Hotfix0_get_rewardUiStyle; // 0x0
	private static DelegateBridge __Hotfix0_set_rewardUiStyle; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge __Hotfix0_OnClickBackBtn; // 0x20
	private static DelegateBridge __Hotfix0_OnOtherRewardItemClick; // 0x28
	private static DelegateBridge __Hotfix0__ShowView; // 0x30
	private static DelegateBridge __Hotfix0__RenderTitle; // 0x38
	private static DelegateBridge __Hotfix0__RenderRewardData; // 0x40
	private static DelegateBridge __Hotfix0__PlayAlchemyResultAudio; // 0x48
	private static DelegateBridge __Hotfix0__RenderOtherRewards; // 0x50
	private static DelegateBridge __Hotfix0__InitOtherListLayout; // 0x58
	private static DelegateBridge __Hotfix0__RenderSsrRewards; // 0x60
	private static DelegateBridge __Hotfix0__InitSsrListLayout; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public RoguelikeRewardStyle rewardUiStyle { get; set; }

	// RVA: 0x2b0b358 VA: 0x7595123358
	public RoguelikeRewardStyle get_rewardUiStyle() { }
	// RVA: 0x2b0a7f4 VA: 0x75951227f4
	public Void set_rewardUiStyle(RoguelikeRewardStyle value) { }
	// RVA: 0x2b0a6bc VA: 0x75951226bc
	public Void Show(RL04AlchemyResultViewModel viewModel) { }
	// RVA: 0x2b0a788 VA: 0x7595122788
	public Void Hide() { }
	// RVA: 0x2b0b838 VA: 0x7595123838
	public Void OnClickBackBtn() { }
	// RVA: 0x2b0b938 VA: 0x7595123938
	public Void OnOtherRewardItemClick(Int32 index) { }
	// RVA: 0x2b0b4c4 VA: 0x75951234c4
	private Void _ShowView(Boolean show) { }
	// RVA: 0x2b0b5ac VA: 0x75951235ac
	private Void _RenderTitle(ResultState status, Boolean isMultiChoice) { }
	// RVA: 0x2b0b6fc VA: 0x75951236fc
	private Void _RenderRewardData(RL04AlchemyResultViewModel viewModel) { }
	// RVA: 0x2b0bacc VA: 0x7595123acc
	private Void _PlayAlchemyResultAudio(ResultState resultState) { }
	// RVA: 0x2b0bc98 VA: 0x7595123c98
	private Void _RenderOtherRewards(RoguelikeRewardListViewModel otherRewardListViewModel) { }
	// RVA: 0x2b0bd4c VA: 0x7595123d4c
	private Void _InitOtherListLayout(String topicId) { }
	// RVA: 0x2b0bbf4 VA: 0x7595123bf4
	private Void _RenderSsrRewards(List`1 ssrRewardListViewModel) { }
	// RVA: 0x2b0be68 VA: 0x7595123e68
	private Void _InitSsrListLayout() { }
	// RVA: 0x2b0b3c0 VA: 0x75951233c0
	private Void _InitIfNot() { }
	// RVA: 0x2b0c01c VA: 0x759512401c
	public Void .ctor() { }
}
```