# SandboxV2RiftDifficultySelectView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2RiftDifficultyItem _prefab`

- `Single _difficultyItemWidthMin`

- `Single _difficultyItemWidthMax`

- `GameObject _difficultyDescPanel`

- `Text _difficultyDesc`

- `TwoStateToggle _confirmToggle`

- `SimpleLayoutContent _rewardContent`

- `GameObject _leftArrow`

- `GameObject _rightArrow`

- `InertiaScrollViewPager _scrollViewPager`

- `UIRecycleLayoutGroup _difficultyContent`

- `UIAnimationLocation _scrollPagerUpdatingAnim`

- `RectTransform _backPressArea`

- `ScrollRect _rewardRect`

- `Boolean m_hasInited`

- `DifficultyAdapter m_adapter`

- `RewardAdapter m_rewardAdapter`

- `UIStateFinder m_stateFinder`

- `SandboxV2RiftDifficultySelectViewModel m_viewModel`

- `UISwitchTween m_updatingTween`

- `Int32 m_cachedSequenceNum`


## Methods

- `Void Update()`

- `Void _RenderByPagerIndexWhenStable(Int32)`

- `Void _RenderByPagerIndexWhenChanged(Int32, Int32)`

- `Void _InitIfNot()`

- `Void _OnDifficultyItemClicked(Int32)`

- `Void _OnScrollPagerStateChanged(State)`

- `Void OnConfirmDifficultyLevel()`

- `Void OnLeftArrowClicked()`

- `Void OnRightArrowClicked()`

- `Void OnCloseState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftDifficultySelectView : DataBinder`1
{
	private static readonly Option REWARD_ITEM_CARD_OPTION; // 0x0
	private SandboxV2RiftDifficultyItem _prefab; // 0x20
	private Single _difficultyItemWidthMin; // 0x28
	private Single _difficultyItemWidthMax; // 0x2c
	private GameObject _difficultyDescPanel; // 0x30
	private Text _difficultyDesc; // 0x38
	private TwoStateToggle _confirmToggle; // 0x40
	private SimpleLayoutContent _rewardContent; // 0x48
	private GameObject _leftArrow; // 0x50
	private GameObject _rightArrow; // 0x58
	private InertiaScrollViewPager _scrollViewPager; // 0x60
	private UIRecycleLayoutGroup _difficultyContent; // 0x68
	private UIAnimationLocation _scrollPagerUpdatingAnim; // 0x70
	private RectTransform _backPressArea; // 0x80
	private ScrollRect _rewardRect; // 0x88
	private Boolean m_hasInited; // 0x90
	private DifficultyAdapter m_adapter; // 0x98
	private RewardAdapter m_rewardAdapter; // 0xa0
	private List`1 m_cachedRewards; // 0xa8
	private UIStateFinder m_stateFinder; // 0xb0
	private SandboxV2RiftDifficultySelectViewModel m_viewModel; // 0xc0
	private UISwitchTween m_updatingTween; // 0xc8
	private Int32 m_cachedSequenceNum; // 0xd0
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0__RenderByPagerIndexWhenStable; // 0x30
	private static DelegateBridge __Hotfix0__RenderByPagerIndexWhenChanged; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__OnDifficultyItemClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnScrollPagerStateChanged; // 0x50
	private static DelegateBridge __Hotfix0_OnConfirmDifficultyLevel; // 0x58
	private static DelegateBridge __Hotfix0_OnLeftArrowClicked; // 0x60
	private static DelegateBridge __Hotfix0_OnRightArrowClicked; // 0x68
	private static DelegateBridge __Hotfix0_OnCloseState; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x25fc4ac VA: 0x7594c144ac
	public Void Update() { }
	// RVA: 0x25fc744 VA: 0x7594c14744
	public override Void OnValueChanged(SandboxV2RiftDifficultySelectProperty property) { }
	// RVA: 0x25fccdc VA: 0x7594c14cdc
	private Void _RenderByPagerIndexWhenStable(Int32 selectLevel) { }
	// RVA: 0x25fcc28 VA: 0x7594c14c28
	private Void _RenderByPagerIndexWhenChanged(Int32 selectLevel, Int32 maxLevel) { }
	// RVA: 0x25fc8cc VA: 0x7594c148cc
	private Void _InitIfNot() { }
	// RVA: 0x25fd274 VA: 0x7594c15274
	private Void _OnDifficultyItemClicked(Int32 index) { }
	// RVA: 0x25fd380 VA: 0x7594c15380
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x25fd518 VA: 0x7594c15518
	public Void OnConfirmDifficultyLevel() { }
	// RVA: 0x25fd670 VA: 0x7594c15670
	public Void OnLeftArrowClicked() { }
	// RVA: 0x25fd794 VA: 0x7594c15794
	public Void OnRightArrowClicked() { }
	// RVA: 0x25fd8d4 VA: 0x7594c158d4
	public Void OnCloseState() { }
	// RVA: 0x25fd988 VA: 0x7594c15988
	public Void .ctor() { }
	// RVA: 0x25fda30 VA: 0x7594c15a30
	private static Void .cctor() { }
}
```