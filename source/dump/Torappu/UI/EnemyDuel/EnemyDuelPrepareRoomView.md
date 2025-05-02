# EnemyDuelPrepareRoomView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelPrepareBannerView _bannerView`

- `EnemyDuelPrepareModeDetailView _detailView`

- `Text _roomIdText`

- `Text _curPlayerNumText`

- `Text _maxPlayerNumText`

- `Text _roomEndTimeText`

- `Text _playerCntRequirementText`

- `EnemyDuelPrepareRoomPlayerCardAdapter _playerCardAdapter`

- `GameObject _guestWaitBtnObj`

- `GameObject _startBtnObj`

- `GameObject _lackOfPlayerObj`

- `GameObject _waitingPlayerReturnObj`

- `GridLayoutGroup _playerCardsGridLayout`

- `TwoStateToggle _npcOptionToggle`

- `UIAnimationLocation _enterAnim`

- `Boolean m_isInited`

- `String m_cacheModeId`

- `EnemyDuelPrepareRoomStatusViewModel m_statusViewModel`

- `AnimationSwitchTween m_enterSwitchTween`

- `CountDownTask m_roomEndTask`


## Methods

- `Void InitIfNot()`

- `Void Update()`

- `Void <OnValueChanged>b__24_0(TickValue)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareRoomView : DataBinder`1
{
	private EnemyDuelPrepareBannerView _bannerView; // 0x20
	private EnemyDuelPrepareModeDetailView _detailView; // 0x28
	private Text _roomIdText; // 0x30
	private Text _curPlayerNumText; // 0x38
	private Text _maxPlayerNumText; // 0x40
	private Text _roomEndTimeText; // 0x48
	private Text _playerCntRequirementText; // 0x50
	private EnemyDuelPrepareRoomPlayerCardAdapter _playerCardAdapter; // 0x58
	private GameObject[] _hostObjs; // 0x60
	private TwoStateToggle[] _hostToggles; // 0x68
	private GameObject _guestWaitBtnObj; // 0x70
	private GameObject _startBtnObj; // 0x78
	private GameObject _lackOfPlayerObj; // 0x80
	private GameObject _waitingPlayerReturnObj; // 0x88
	private GridLayoutGroup _playerCardsGridLayout; // 0x90
	private TwoStateToggle _npcOptionToggle; // 0x98
	private UIAnimationLocation _enterAnim; // 0xa0
	private Boolean m_isInited; // 0xb0
	private String m_cacheModeId; // 0xb8
	private EnemyDuelPrepareRoomStatusViewModel m_statusViewModel; // 0xc0
	private AnimationSwitchTween m_enterSwitchTween; // 0xc8
	private CountDownTask m_roomEndTask; // 0xd0
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x299982c VA: 0x7594fb182c
	public Void InitIfNot() { }
	// RVA: 0x29998fc VA: 0x7594fb18fc
	private Void Update() { }
	// RVA: 0x2999978 VA: 0x7594fb1978
	public override Void OnValueChanged(EnemyDuelPrepareRoomProperty property) { }
	// RVA: 0x299a2cc VA: 0x7594fb22cc
	public Void .ctor() { }
	// RVA: 0x299a35c VA: 0x7594fb235c
	private Void <OnValueChanged>b__24_0(TickValue value) { }
}
```