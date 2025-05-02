# EnemyDuelPrepareRoomPlayerCardView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Image _avatarImg`

- `Text _nameText`

- `GameObject _hostObj`

- `GameObject _selfObj`

- `GameObject _offlineObj`

- `GameObject _battleFinishingObj`

- `GameObject _optionRootObj`

- `CanvasGroup _optionCanvasGroup`

- `TwoStateToggle _hostOptionsToggle`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _optionInAnim`

- `UIAnimationLocation _optionOutAnim`

- `Boolean m_isInited`

- `Boolean m_isChecking`

- `Boolean m_isEmpty`

- `Boolean m_isSelf`

- `Boolean m_isHostVision`

- `Int32 m_cacheIdx`

- `UIStateFinder m_stateFinder`

- `AnimationSwitchTween m_enterAnimSwitchTween`

- `AnimationSwitchTween m_optionInSwitchTween`

- `AnimationSwitchTween m_optionOutSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void Render(EnemyDuelPrepareRoomPlayerCardViewModel, Boolean, Boolean)`

- `Void _SetEnterAnim(Boolean, Boolean, Boolean)`

- `Void _SetIsChecking(Boolean, Boolean)`

- `Void EventOnClick()`

- `Void EventOnSendFriendRequestClick()`

- `Void EventOnCheckNameCardClick()`

- `Void EventOnKickClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareRoomPlayerCardView : MonoBehaviour, IHotfixable
{
	private Image _avatarImg; // 0x18
	private Text _nameText; // 0x20
	private GameObject[] _playerObjs; // 0x28
	private GameObject[] _firstEmptyObjs; // 0x30
	private GameObject _hostObj; // 0x38
	private GameObject _selfObj; // 0x40
	private GameObject _offlineObj; // 0x48
	private GameObject _battleFinishingObj; // 0x50
	private GameObject _optionRootObj; // 0x58
	private CanvasGroup _optionCanvasGroup; // 0x60
	private TwoStateToggle _hostOptionsToggle; // 0x68
	private Text[] _friendOptionTexts; // 0x70
	private TwoStateToggle[] _friendOptionToggles; // 0x78
	private UIAnimationLocation _enterAnim; // 0x80
	private UIAnimationLocation _optionInAnim; // 0x90
	private UIAnimationLocation _optionOutAnim; // 0xa0
	private Boolean m_isInited; // 0xb0
	private Boolean m_isChecking; // 0xb1
	private Boolean m_isEmpty; // 0xb2
	private Boolean m_isSelf; // 0xb3
	private Boolean m_isHostVision; // 0xb4
	private Int32 m_cacheIdx; // 0xb8
	private UIStateFinder m_stateFinder; // 0xc0
	private AnimationSwitchTween m_enterAnimSwitchTween; // 0xd0
	private AnimationSwitchTween m_optionInSwitchTween; // 0xd8
	private AnimationSwitchTween m_optionOutSwitchTween; // 0xe0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__SetEnterAnim; // 0x10
	private static DelegateBridge __Hotfix0__SetIsChecking; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x20
	private static DelegateBridge __Hotfix0_EventOnSendFriendRequestClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnCheckNameCardClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnKickClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2998fcc VA: 0x7594fb0fcc
	private Void _InitIfNot() { }
	// RVA: 0x2998ad8 VA: 0x7594fb0ad8
	public Void Render(EnemyDuelPrepareRoomPlayerCardViewModel viewModel, Boolean isCheckingAvatar, Boolean isHostVision) { }
	// RVA: 0x2999280 VA: 0x7594fb1280
	private Void _SetEnterAnim(Boolean prevIsEmpty, Boolean isEmpty, Boolean isReset) { }
	// RVA: 0x299913c VA: 0x7594fb113c
	private Void _SetIsChecking(Boolean isChecking, Boolean isReset) { }
	// RVA: 0x2999374 VA: 0x7594fb1374
	public Void EventOnClick() { }
	// RVA: 0x299947c VA: 0x7594fb147c
	public Void EventOnSendFriendRequestClick() { }
	// RVA: 0x299958c VA: 0x7594fb158c
	public Void EventOnCheckNameCardClick() { }
	// RVA: 0x299969c VA: 0x7594fb169c
	public Void EventOnKickClick() { }
	// RVA: 0x29997b4 VA: 0x7594fb17b4
	public Void .ctor() { }
}
```