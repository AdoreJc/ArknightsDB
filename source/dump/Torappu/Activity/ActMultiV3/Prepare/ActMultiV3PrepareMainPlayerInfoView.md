# ActMultiV3PrepareMainPlayerInfoView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `PlayerInfoGroup _topPlayerGroup`

- `PlayerInfoGroup _botPlayerGroup`

- `TwoStateToggle _topPlayerToggle`

- `TwoStateToggle _lastStepBtnToggle`

- `GameObject _kickBtnObj`

- `Text _pingTxt`

- `Text _closeTxt`

- `RectTransform _backBtnRect`

- `GameObject _partnerOfflineObj`

- `TwoStateToggle _tinyToggle`

- `UIAnimationLocation _fullPanelInAnim`

- `UIAnimationLocation _tinyPanelInAnim`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `Boolean m_isTiny`

- `Int32 m_cachedCdSeqNum`

- `Tween m_cachedCdTween`

- `ActMultiV3PrepareMainViewModelProperty m_cachedProp`

- `CountDownTask m_countDownTask`

- `Int64 m_cachedEndTs`

- `AnimationSwitchTween m_fullPanelSwitchTween`

- `AnimationSwitchTween m_tinyPanelSwitchTween`


## Methods

- `Void _InitIfNot()`

- `Void _Render(ActMultiV3PrepareMainPlayerInfoViewModel, ActMultiV3PrepareMainViewConfig)`

- `Void Update()`

- `Void _SetActiveToGameObjects(GameObject[], Boolean)`

- `Void _OnBackPress()`

- `Void EventOnExit()`

- `Void EventOnBack()`

- `Void Chat()`

- `Void EventOnKick()`

- `Void EventOnCheckNameCard()`

- `Void EventOnClickSquadEffect()`

- `Void UpdatePing(Int32)`

- `Void <OnValueChanged>b__29_0(TickValue)`

- `Void <OnValueChanged>b__29_1()`

- `Void <OnValueChanged>b__29_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainPlayerInfoView : ActMultiV3PrepareMainViewBase, IPingListener
{
	private const String COUNT_DOWN_FORMAT; // 0x0
	public PlayerInfoGroup _topPlayerGroup; // 0x20
	private PlayerInfoGroup _botPlayerGroup; // 0x28
	private GameObject[] _stageCheckObjs; // 0x30
	private GameObject[] _charPickObjs; // 0x38
	private TwoStateToggle _topPlayerToggle; // 0x40
	private TwoStateToggle _lastStepBtnToggle; // 0x48
	private GameObject _kickBtnObj; // 0x50
	private CanvasGroup[] _chatCdBlockers; // 0x58
	private GameObject[] _chatObjs; // 0x60
	private GameObject[] _chatNewPoints; // 0x68
	private Text _pingTxt; // 0x70
	private Text _closeTxt; // 0x78
	private RectTransform _backBtnRect; // 0x80
	private GameObject _partnerOfflineObj; // 0x88
	private TwoStateToggle _tinyToggle; // 0x90
	private UIAnimationLocation _fullPanelInAnim; // 0x98
	private UIAnimationLocation _tinyPanelInAnim; // 0xa8
	private Boolean m_isInited; // 0xb8
	private UIStateFinder m_stateFinder; // 0xc0
	private Boolean m_isTiny; // 0xd0
	private Int32 m_cachedCdSeqNum; // 0xd4
	private Tween m_cachedCdTween; // 0xd8
	private ActMultiV3PrepareMainViewModelProperty m_cachedProp; // 0xe0
	private CountDownTask m_countDownTask; // 0xe8
	private Int64 m_cachedEndTs; // 0xf0
	private AnimationSwitchTween m_fullPanelSwitchTween; // 0xf8
	private AnimationSwitchTween m_tinyPanelSwitchTween; // 0x100
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__SetActiveToGameObjects; // 0x20
	private static DelegateBridge __Hotfix0__OnBackPress; // 0x28
	private static DelegateBridge __Hotfix0_EventOnExit; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBack; // 0x38
	private static DelegateBridge __Hotfix0_Chat; // 0x40
	private static DelegateBridge __Hotfix0_EventOnKick; // 0x48
	private static DelegateBridge __Hotfix0_EventOnCheckNameCard; // 0x50
	private static DelegateBridge __Hotfix0_EventOnClickSquadEffect; // 0x58
	private static DelegateBridge __Hotfix0_UpdatePing; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x3163980 VA: 0x759577b980
	public override Void OnValueChanged(ActMultiV3PrepareMainViewModelProperty property) { }
	// RVA: 0x3163e34 VA: 0x759577be34
	private Void _InitIfNot() { }
	// RVA: 0x3163ff8 VA: 0x759577bff8
	private Void _Render(ActMultiV3PrepareMainPlayerInfoViewModel viewModel, ActMultiV3PrepareMainViewConfig config) { }
	// RVA: 0x316465c VA: 0x759577c65c
	private Void Update() { }
	// RVA: 0x3164574 VA: 0x759577c574
	private Void _SetActiveToGameObjects(GameObject[] objs, Boolean value) { }
	// RVA: 0x31646d8 VA: 0x759577c6d8
	private Void _OnBackPress() { }
	// RVA: 0x316480c VA: 0x759577c80c
	public Void EventOnExit() { }
	// RVA: 0x3164768 VA: 0x759577c768
	public Void EventOnBack() { }
	// RVA: 0x31648b0 VA: 0x759577c8b0
	public Void Chat() { }
	// RVA: 0x3164954 VA: 0x759577c954
	public Void EventOnKick() { }
	// RVA: 0x31649f8 VA: 0x759577c9f8
	public Void EventOnCheckNameCard() { }
	// RVA: 0x3164a9c VA: 0x759577ca9c
	public Void EventOnClickSquadEffect() { }
	// RVA: 0x3164b40 VA: 0x759577cb40
	public Void UpdatePing(Int32 ping) { }
	// RVA: 0x3164c58 VA: 0x759577cc58
	public Void .ctor() { }
	// RVA: 0x3164cc4 VA: 0x759577ccc4
	private Void <OnValueChanged>b__29_0(TickValue value) { }
	// RVA: 0x3164dd8 VA: 0x759577cdd8
	private Void <OnValueChanged>b__29_1() { }
	// RVA: 0x3164e50 VA: 0x759577ce50
	private Void <OnValueChanged>b__29_2() { }
}
```