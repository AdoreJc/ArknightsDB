# ActMultiV3BattleFinishCompleteInfoView

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _enterQuitAnim`

- `UIAnimationLocation _nextAnim`

- `UIAnimationLocation _hideAnim`

- `GameObject _btnNextRaycastGO`

- `GameObject _btnNextNormalPartGO`

- `GameObject _btnNextQuitPartGO`

- `GameObject _earlyQuitGO`

- `GameObject _selfQuitHintGO`

- `GameObject _mateQuitHintGO`

- `Text _textStageName`

- `GameObject _normalTitleGO`

- `GameObject _earlyQuitTitleGO`

- `Text _textModeName`

- `ActMultiV3BattleFinishRewardView _rewardView`

- `ActMultiV3BattleFinishIllustView _illustView`

- `ActMultiV3DifficultyIconView _diffIconPrefab`

- `RectTransform _diffIconContainer`

- `RectTransform _modeViewContainer`

- `Boolean m_hasInited`

- `Boolean m_hasInitAnim`

- `Tween m_animTween`

- `ActMultiV3BattleFinishModeViewBase m_modeView`

- `ActMultiV3DifficultyIconView m_diffIconView`

- `Action <onNextClick>k__BackingField`


## Properties

- `Action onNextClick`


## Methods

- `Action get_onNextClick()`

- `Void set_onNextClick(Action)`

- `IEnumerator HideCoroutine()`

- `Void _OnAnimEnterComplete()`

- `Void _InitIfNot()`

- `Void _CreateModeViewIfNeed(ActMultiV3BattleFinishViewModel)`

- `Void _InitAnimIfNot(Boolean)`

- `Void EventOnBtnNextClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishCompleteInfoView : ActMultiV3BattleFinishPhaseView
{
	private UIAnimationLocation _enterAnim; // 0x50
	private UIAnimationLocation _enterQuitAnim; // 0x60
	private UIAnimationLocation _nextAnim; // 0x70
	private UIAnimationLocation _hideAnim; // 0x80
	private GameObject _btnNextRaycastGO; // 0x90
	private GameObject _btnNextNormalPartGO; // 0x98
	private GameObject _btnNextQuitPartGO; // 0xa0
	private GameObject _earlyQuitGO; // 0xa8
	private GameObject _selfQuitHintGO; // 0xb0
	private GameObject _mateQuitHintGO; // 0xb8
	private Text _textStageName; // 0xc0
	private GameObject _normalTitleGO; // 0xc8
	private GameObject _earlyQuitTitleGO; // 0xd0
	private Text _textModeName; // 0xd8
	private ActMultiV3BattleFinishRewardView _rewardView; // 0xe0
	private ActMultiV3BattleFinishIllustView _illustView; // 0xe8
	private ActMultiV3DifficultyIconView _diffIconPrefab; // 0xf0
	private RectTransform _diffIconContainer; // 0xf8
	private ActMultiV3BattleFinishModeViewBase[] _modePrefabList; // 0x100
	private RectTransform _modeViewContainer; // 0x108
	private Boolean m_hasInited; // 0x110
	private Boolean m_hasInitAnim; // 0x111
	private Tween m_animTween; // 0x118
	private ActMultiV3BattleFinishModeViewBase m_modeView; // 0x120
	private ActMultiV3DifficultyIconView m_diffIconView; // 0x128
	private Action <onNextClick>k__BackingField; // 0x130
	private static DelegateBridge __Hotfix0_get_onNextClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onNextClick; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__OnAnimEnterComplete; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__CreateModeViewIfNeed; // 0x38
	private static DelegateBridge __Hotfix0__InitAnimIfNot; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBtnNextClick; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action onNextClick { get; set; }

	// RVA: 0x317b540 VA: 0x7595793540
	private Action get_onNextClick() { }
	// RVA: 0x317b5a8 VA: 0x75957935a8
	public Void set_onNextClick(Action value) { }
	// RVA: 0x317b62c VA: 0x759579362c
	public override IEnumerator ShowCoroutine() { }
	// RVA: 0x317b700 VA: 0x7595793700
	public IEnumerator HideCoroutine() { }
	// RVA: 0x317b7d4 VA: 0x75957937d4
	private Void _OnAnimEnterComplete() { }
	// RVA: 0x317b844 VA: 0x7595793844
	protected override Void OnInit() { }
	// RVA: 0x317bcb4 VA: 0x7595793cb4
	private Void _InitIfNot() { }
	// RVA: 0x317bda8 VA: 0x7595793da8
	private Void _CreateModeViewIfNeed(ActMultiV3BattleFinishViewModel viewModel) { }
	// RVA: 0x317bb8c VA: 0x7595793b8c
	private Void _InitAnimIfNot(Boolean isEarlyQuit) { }
	// RVA: 0x317bfe4 VA: 0x7595793fe4
	public Void EventOnBtnNextClick() { }
	// RVA: 0x317c094 VA: 0x7595794094
	public Void .ctor() { }
}
```