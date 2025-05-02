# EnemyDuelPrepareModeCardView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Image _entryPicImg`

- `GameObject _extraRewardObj`

- `Text _modeNameText`

- `Text _modeEnNameText`

- `Text _highScoreText`

- `TwoStateToggle _avatarNameToggle`

- `TwoStateToggle _highScoreToggle`

- `GameObject _highScoreObj`

- `Text _highScoreDescText`

- `GameObject _lockObj`

- `GameObject _cardContentObj`

- `Text _lockText`

- `UIAnimationLocation _selectAnim`

- `UIAnimationLocation _loadAnim`

- `Boolean m_isInited`

- `Boolean m_isLoadAnimPlayed`

- `UIStateFinder m_stateFinder`

- `Int32 m_cacheSeqNum`

- `EnemyDuelPrepareSelectModeCardViewModel m_viewModel`

- `AnimationSwitchTween m_selectSwitchTween`

- `AnimationSwitchTween m_loadAnimSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void Render(Int32, EnemyDuelPrepareSelectModeCardViewModel, Boolean)`

- `Void EventOnClick()`

- `Void <Render>b__27_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareModeCardView : MonoBehaviour, IHotfixable
{
	private const Single CARD_LOAD_ANIM_TIME_UNIT; // 0x0
	private Image _entryPicImg; // 0x18
	private GameObject _extraRewardObj; // 0x20
	private Text _modeNameText; // 0x28
	private Text _modeEnNameText; // 0x30
	private Text[] _modePlayerCntTexts; // 0x38
	private Text[] _avatarNameTexts; // 0x40
	private Text[] _avatarDescTexts; // 0x48
	private Text _highScoreText; // 0x50
	private TwoStateToggle _avatarNameToggle; // 0x58
	private TwoStateToggle _highScoreToggle; // 0x60
	private GameObject _highScoreObj; // 0x68
	private Text _highScoreDescText; // 0x70
	private TwoStateToggle[] _multiPlayerToggles; // 0x78
	private GameObject _lockObj; // 0x80
	private GameObject _cardContentObj; // 0x88
	private Text _lockText; // 0x90
	private UIAnimationLocation _selectAnim; // 0x98
	private UIAnimationLocation _loadAnim; // 0xa8
	private Boolean m_isInited; // 0xb8
	private Boolean m_isLoadAnimPlayed; // 0xb9
	private UIStateFinder m_stateFinder; // 0xc0
	private Int32 m_cacheSeqNum; // 0xd0
	private EnemyDuelPrepareSelectModeCardViewModel m_viewModel; // 0xd8
	private AnimationSwitchTween m_selectSwitchTween; // 0xe0
	private AnimationSwitchTween m_loadAnimSwitchTween; // 0xe8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x299b720 VA: 0x7594fb3720
	private Void _InitIfNot() { }
	// RVA: 0x299b890 VA: 0x7594fb3890
	public Void Render(Int32 idx, EnemyDuelPrepareSelectModeCardViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x299bde8 VA: 0x7594fb3de8
	public Void EventOnClick() { }
	// RVA: 0x299bef0 VA: 0x7594fb3ef0
	public Void .ctor() { }
	// RVA: 0x299bf60 VA: 0x7594fb3f60
	private Void <Render>b__27_0() { }
}
```