# EnemyDuelPrepareSelectModeView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `SimpleLayoutContent _modeCardLayout`

- `EnemyDuelPrepareBannerView _bannerView`

- `EnemyDuelPrepareModeDetailView _detailView`

- `Text _streamerNameText`

- `Text _streamerSubscribeText`

- `Image _streamerAvatarImg`

- `GameObject _extraRewardObj`

- `ScrollRect _modeScrollRect`

- `Int32 _minModeCardCnt`

- `Int32 _modeCardSlideThresholdCnt`

- `PrepareButtonView _matchPrepareBtn`

- `PrepareButtonView _roomPrepareBtn`

- `TwoStateToggle _soloGameBtnDescToggle`

- `UIAnimationLocation _modeSelectInAnim`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `EnemyDuelPrepareSelectModeViewModel m_viewModel`

- `ModeCardAdapter m_modeCardAdapter`

- `AnimationSwitchTween m_modeSelectInSwitchTween`

- `Tween m_modeBannerPicLoopTween`

- `PrepareButtonView m_curPrepareBtn`

- `Int32 m_bannerPreviewIdx`

- `Int32 m_cacheMainSeqNum`

- `Int32 m_cacheSelectSeqNum`


## Properties

- `Int32 curBannerIdx`


## Methods

- `Int32 get_curBannerIdx()`

- `Void _InitIfNot()`

- `Void EventOnCreateRoomClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareSelectModeView : DataBinder`1
{
	private SimpleLayoutContent _modeCardLayout; // 0x20
	private EnemyDuelPrepareBannerView _bannerView; // 0x28
	private EnemyDuelPrepareModeDetailView _detailView; // 0x30
	private TwoStateToggle[] _isRoomToggles; // 0x38
	private Text _streamerNameText; // 0x40
	private Text _streamerSubscribeText; // 0x48
	private Image _streamerAvatarImg; // 0x50
	private GameObject _extraRewardObj; // 0x58
	private ScrollRect _modeScrollRect; // 0x60
	private Int32 _minModeCardCnt; // 0x68
	private Int32 _modeCardSlideThresholdCnt; // 0x6c
	private PrepareButtonView _matchPrepareBtn; // 0x70
	private PrepareButtonView _roomPrepareBtn; // 0x78
	private TwoStateToggle _soloGameBtnDescToggle; // 0x80
	private UIAnimationLocation _modeSelectInAnim; // 0x88
	private Boolean m_isInited; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private EnemyDuelPrepareSelectModeViewModel m_viewModel; // 0xb0
	private ModeCardAdapter m_modeCardAdapter; // 0xb8
	private AnimationSwitchTween m_modeSelectInSwitchTween; // 0xc0
	private Tween m_modeBannerPicLoopTween; // 0xc8
	private PrepareButtonView m_curPrepareBtn; // 0xd0
	private Int32 m_bannerPreviewIdx; // 0xd8
	private Int32 m_cacheMainSeqNum; // 0xdc
	private Int32 m_cacheSelectSeqNum; // 0xe0
	private static DelegateBridge __Hotfix0_get_curBannerIdx; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCreateRoomClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Int32 curBannerIdx { get; }

	// RVA: 0x299f15c VA: 0x7594fb715c
	public Int32 get_curBannerIdx() { }
	// RVA: 0x299f1d0 VA: 0x7594fb71d0
	private Void _InitIfNot() { }
	// RVA: 0x299f3a4 VA: 0x7594fb73a4
	public override Void OnValueChanged(EnemyDuelPrepareSelectModeProperty property) { }
	// RVA: 0x299f958 VA: 0x7594fb7958
	public Void EventOnCreateRoomClick() { }
	// RVA: 0x299fa0c VA: 0x7594fb7a0c
	public Void .ctor() { }
}
```