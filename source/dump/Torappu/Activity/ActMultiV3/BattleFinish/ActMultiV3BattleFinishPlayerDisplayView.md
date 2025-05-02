# ActMultiV3BattleFinishPlayerDisplayView

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `UIAnimationLocation _enterAnim`

- `Text _textStageCode`

- `ActMultiV3BattleFinishIllustView _myIllustView`

- `ActMultiV3BattleFinishIllustView _partnerIllustView`

- `ActMultiV3DifficultyIconView _diffIconPrefab`

- `RectTransform _diffIconContainer`

- `GameObject _reverseBgGO`

- `GameObject _reverseTagGO`

- `GameObject _newPhotoGO`

- `Image _imgModeIcon`

- `Text _textFinishTime`

- `ActMultiV3ShortNameCardView _nameCardPrefab`

- `RectTransform _myNameCardContainer`

- `RectTransform _partnerNameCardContainer`

- `GameObject _btnContinueMatchGO`

- `GameObject _btnContinueCoopGO`

- `GameObject _btnReturnRoomGO`

- `GameObject _btnCompleteTrainingGO`

- `UIAnimationLocation _animGotLike`

- `UIAnimationLocation _animGiveLike`

- `UIAnimationLocation _animPartnerWave`

- `Boolean m_hasInit`

- `Boolean m_cacheGotLike`

- `Boolean m_cachePartnerWave`

- `Tween m_enterTween`

- `Tween m_gotLikeTween`

- `Tween m_givenLikeTween`

- `Tween m_partnerWaveTween`

- `ActMultiV3DifficultyIconView m_diffIconView`

- `ActMultiV3ShortNameCardView m_selfNameCardView`

- `ActMultiV3ShortNameCardView m_partnerNameCardView`

- `Action <onReturnToHome>k__BackingField`

- `Action <onContinueCoop>k__BackingField`

- `Action <onReturnToRoom>k__BackingField`

- `Action <onReturnToMatch>k__BackingField`

- `Action <onBtnLikeClick>k__BackingField`


## Properties

- `Action onReturnToHome`

- `Action onContinueCoop`

- `Action onReturnToRoom`

- `Action onReturnToMatch`

- `Action onBtnLikeClick`


## Methods

- `Action get_onReturnToHome()`

- `Void set_onReturnToHome(Action)`

- `Action get_onContinueCoop()`

- `Void set_onContinueCoop(Action)`

- `Action get_onReturnToRoom()`

- `Void set_onReturnToRoom(Action)`

- `Action get_onReturnToMatch()`

- `Void set_onReturnToMatch(Action)`

- `Action get_onBtnLikeClick()`

- `Void set_onBtnLikeClick(Action)`

- `Void _InitIfNot()`

- `Void UpdateBtnRoomVisible(ActMultiV3BattleFinishViewModel)`

- `Void PlayGotLikeAnimIfNeed()`

- `Void PlayGiveLikeAnimIfNeed()`

- `Void PlayPartnerWaveAnimIfNeed()`

- `Void EventOnBtnReturnHome()`

- `Void EventOnBtnLikeClick()`

- `Void EventOnBtnReturnRoom()`

- `Void EventOnBtnContinueCoop()`

- `Void EventOnBtnReturnMatch()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishPlayerDisplayView : ActMultiV3BattleFinishPhaseView
{
	private UIAnimationLocation _enterAnim; // 0x50
	private Text _textStageCode; // 0x60
	private ActMultiV3BattleFinishIllustView _myIllustView; // 0x68
	private ActMultiV3BattleFinishIllustView _partnerIllustView; // 0x70
	private ActMultiV3DifficultyIconView _diffIconPrefab; // 0x78
	private RectTransform _diffIconContainer; // 0x80
	private GameObject[] _starRatingGOList; // 0x88
	private ActMultiV3BattleFinishResultViewBase[] _resultViewList; // 0x90
	private GameObject _reverseBgGO; // 0x98
	private GameObject _reverseTagGO; // 0xa0
	private GameObject _newPhotoGO; // 0xa8
	private Image _imgModeIcon; // 0xb0
	private Text _textFinishTime; // 0xb8
	private ActMultiV3ShortNameCardView _nameCardPrefab; // 0xc0
	private RectTransform _myNameCardContainer; // 0xc8
	private RectTransform _partnerNameCardContainer; // 0xd0
	private GameObject _btnContinueMatchGO; // 0xd8
	private GameObject _btnContinueCoopGO; // 0xe0
	private GameObject _btnReturnRoomGO; // 0xe8
	private GameObject _btnCompleteTrainingGO; // 0xf0
	private UIAnimationLocation _animGotLike; // 0xf8
	private UIAnimationLocation _animGiveLike; // 0x108
	private UIAnimationLocation _animPartnerWave; // 0x118
	private Boolean m_hasInit; // 0x128
	private Boolean m_cacheGotLike; // 0x129
	private Boolean m_cachePartnerWave; // 0x12a
	private Tween m_enterTween; // 0x130
	private Tween m_gotLikeTween; // 0x138
	private Tween m_givenLikeTween; // 0x140
	private Tween m_partnerWaveTween; // 0x148
	private ActMultiV3DifficultyIconView m_diffIconView; // 0x150
	private ActMultiV3ShortNameCardView m_selfNameCardView; // 0x158
	private ActMultiV3ShortNameCardView m_partnerNameCardView; // 0x160
	private Action <onReturnToHome>k__BackingField; // 0x168
	private Action <onContinueCoop>k__BackingField; // 0x170
	private Action <onReturnToRoom>k__BackingField; // 0x178
	private Action <onReturnToMatch>k__BackingField; // 0x180
	private Action <onBtnLikeClick>k__BackingField; // 0x188
	private static DelegateBridge __Hotfix0_get_onReturnToHome; // 0x0
	private static DelegateBridge __Hotfix0_set_onReturnToHome; // 0x8
	private static DelegateBridge __Hotfix0_get_onContinueCoop; // 0x10
	private static DelegateBridge __Hotfix0_set_onContinueCoop; // 0x18
	private static DelegateBridge __Hotfix0_get_onReturnToRoom; // 0x20
	private static DelegateBridge __Hotfix0_set_onReturnToRoom; // 0x28
	private static DelegateBridge __Hotfix0_get_onReturnToMatch; // 0x30
	private static DelegateBridge __Hotfix0_set_onReturnToMatch; // 0x38
	private static DelegateBridge __Hotfix0_get_onBtnLikeClick; // 0x40
	private static DelegateBridge __Hotfix0_set_onBtnLikeClick; // 0x48
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_OnInit; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x60
	private static DelegateBridge __Hotfix0_UpdateBtnRoomVisible; // 0x68
	private static DelegateBridge __Hotfix0_PlayGotLikeAnimIfNeed; // 0x70
	private static DelegateBridge __Hotfix0_PlayGiveLikeAnimIfNeed; // 0x78
	private static DelegateBridge __Hotfix0_PlayPartnerWaveAnimIfNeed; // 0x80
	private static DelegateBridge __Hotfix0_EventOnBtnReturnHome; // 0x88
	private static DelegateBridge __Hotfix0_EventOnBtnLikeClick; // 0x90
	private static DelegateBridge __Hotfix0_EventOnBtnReturnRoom; // 0x98
	private static DelegateBridge __Hotfix0_EventOnBtnContinueCoop; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnBtnReturnMatch; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	private Action onReturnToHome { get; set; }
	private Action onContinueCoop { get; set; }
	private Action onReturnToRoom { get; set; }
	private Action onReturnToMatch { get; set; }
	private Action onBtnLikeClick { get; set; }

	// RVA: 0x317f704 VA: 0x7595797704
	private Action get_onReturnToHome() { }
	// RVA: 0x317f76c VA: 0x759579776c
	public Void set_onReturnToHome(Action value) { }
	// RVA: 0x317f7f0 VA: 0x75957977f0
	private Action get_onContinueCoop() { }
	// RVA: 0x317f858 VA: 0x7595797858
	public Void set_onContinueCoop(Action value) { }
	// RVA: 0x317f8dc VA: 0x75957978dc
	private Action get_onReturnToRoom() { }
	// RVA: 0x317f944 VA: 0x7595797944
	public Void set_onReturnToRoom(Action value) { }
	// RVA: 0x317f9c8 VA: 0x75957979c8
	private Action get_onReturnToMatch() { }
	// RVA: 0x317fa30 VA: 0x7595797a30
	public Void set_onReturnToMatch(Action value) { }
	// RVA: 0x317fab4 VA: 0x7595797ab4
	private Action get_onBtnLikeClick() { }
	// RVA: 0x317fb1c VA: 0x7595797b1c
	public Void set_onBtnLikeClick(Action value) { }
	// RVA: 0x317fba0 VA: 0x7595797ba0
	public override IEnumerator ShowCoroutine() { }
	// RVA: 0x317fc74 VA: 0x7595797c74
	protected override Void OnInit() { }
	// RVA: 0x31803b0 VA: 0x75957983b0
	private Void _InitIfNot() { }
	// RVA: 0x3180d54 VA: 0x7595798d54
	public Void UpdateBtnRoomVisible(ActMultiV3BattleFinishViewModel viewModel) { }
	// RVA: 0x3180e7c VA: 0x7595798e7c
	public Void PlayGotLikeAnimIfNeed() { }
	// RVA: 0x3181044 VA: 0x7595799044
	public Void PlayGiveLikeAnimIfNeed() { }
	// RVA: 0x31811fc VA: 0x75957991fc
	public Void PlayPartnerWaveAnimIfNeed() { }
	// RVA: 0x31813d4 VA: 0x75957993d4
	public Void EventOnBtnReturnHome() { }
	// RVA: 0x3181470 VA: 0x7595799470
	public Void EventOnBtnLikeClick() { }
	// RVA: 0x318150c VA: 0x759579950c
	public Void EventOnBtnReturnRoom() { }
	// RVA: 0x31815a8 VA: 0x75957995a8
	public Void EventOnBtnContinueCoop() { }
	// RVA: 0x3181644 VA: 0x7595799644
	public Void EventOnBtnReturnMatch() { }
	// RVA: 0x31816e0 VA: 0x75957996e0
	public Void .ctor() { }
}
```