# Act1LockBattleFinishView

**Namespace:** `Torappu.Activity.Act1Lock.BattleFinish`


## Fields

- `UIFullScreenImage _blurBackground`

- `UIExpBar _playerExpBar`

- `BattleFinishInfoView _battleInfoView`

- `BattleFinishDropInfoView _dropInfoView`

- `BattleFinishIllustView _illustView`

- `Animator _favorAnimator`

- `RectTransform _panelResult`

- `CanvasGroup _dropInfoCanvas`

- `Act1LockBattleFinishTotalPointView _pointView`

- `Act1LockBattleFinishDefendView _defendView`

- `Act1LockBattleFinishDefendView _defendReplaceView`

- `Act1LockBattleFinishViewModel m_viewModel`

- `InternalState m_state`

- `UIExpBarController m_expBarController`

- `Coroutine m_updateStateCoroutine`

- `Coroutine m_showPointViewCoroutine`


## Methods

- `Void EventOnPageClicked()`

- `Void _EventOnConfirmDefendClicked()`

- `Void _EventOnCancelDefendClicked()`

- `Void _EventOnDefendSucClicked()`

- `Void OnDestroy()`

- `Void _Init()`

- `IEnumerator _UpdateStateCoroutine()`

- `IEnumerator _ShowDefendView()`

- `IEnumerator _ShowIllustAndBattleInfo()`

- `IEnumerator _ShowFinalStagePoint()`

- `IEnumerator _WaitFinalStagePoint()`

- `IEnumerator _ShowDropInfo()`

- `Void <OnInit>b__19_0()`

- `Void <_EventOnConfirmDefendClicked>b__21_0(Act1LockSetDefendResponse)`

- `Boolean <_ShowDefendView>b__27_0()`

- `Boolean <_ShowDefendView>b__27_1()`

- `Boolean <_ShowFinalStagePoint>b__29_0()`

- `Boolean <_ShowFinalStagePoint>b__29_1()`

- `Void <_ShowDropInfo>b__31_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.BattleFinish
public class Act1LockBattleFinishView : ActivityBattleFinishView
{
	private const Single COMMON_WAIT_TIME; // 0x0
	private const Single WAIT_FINAL_STAGE_POINT_TIME; // 0x0
	private UIFullScreenImage _blurBackground; // 0x30
	private UIExpBar _playerExpBar; // 0x38
	private BattleFinishInfoView _battleInfoView; // 0x40
	private BattleFinishDropInfoView _dropInfoView; // 0x48
	private BattleFinishIllustView _illustView; // 0x50
	private Animator _favorAnimator; // 0x58
	private RectTransform _panelResult; // 0x60
	private CanvasGroup _dropInfoCanvas; // 0x68
	private Act1LockBattleFinishTotalPointView _pointView; // 0x70
	private Act1LockBattleFinishDefendView _defendView; // 0x78
	private Act1LockBattleFinishDefendView _defendReplaceView; // 0x80
	private Act1LockBattleFinishViewModel m_viewModel; // 0x88
	private InternalState m_state; // 0x90
	private UIExpBarController m_expBarController; // 0x98
	private Coroutine m_updateStateCoroutine; // 0xa0
	private Coroutine m_showPointViewCoroutine; // 0xa8
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_EventOnPageClicked; // 0x8
	private static DelegateBridge __Hotfix0__EventOnConfirmDefendClicked; // 0x10
	private static DelegateBridge __Hotfix0__EventOnCancelDefendClicked; // 0x18
	private static DelegateBridge __Hotfix0__EventOnDefendSucClicked; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__Init; // 0x30
	private static DelegateBridge __Hotfix0__UpdateStateCoroutine; // 0x38
	private static DelegateBridge __Hotfix0__ShowDefendView; // 0x40
	private static DelegateBridge __Hotfix0__ShowIllustAndBattleInfo; // 0x48
	private static DelegateBridge __Hotfix0__ShowFinalStagePoint; // 0x50
	private static DelegateBridge __Hotfix0__WaitFinalStagePoint; // 0x58
	private static DelegateBridge __Hotfix0__ShowDropInfo; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x33dd370 VA: 0x75959f5370
	protected override Void OnInit() { }
	// RVA: 0x33dd7b8 VA: 0x75959f57b8
	public Void EventOnPageClicked() { }
	// RVA: 0x33dd8c0 VA: 0x75959f58c0
	private Void _EventOnConfirmDefendClicked() { }
	// RVA: 0x33ddadc VA: 0x75959f5adc
	private Void _EventOnCancelDefendClicked() { }
	// RVA: 0x33ddb60 VA: 0x75959f5b60
	private Void _EventOnDefendSucClicked() { }
	// RVA: 0x33ddbe4 VA: 0x75959f5be4
	private Void OnDestroy() { }
	// RVA: 0x33dd454 VA: 0x75959f5454
	private Void _Init() { }
	// RVA: 0x33ddca8 VA: 0x75959f5ca8
	private IEnumerator _UpdateStateCoroutine() { }
	// RVA: 0x33ddd54 VA: 0x75959f5d54
	private IEnumerator _ShowDefendView() { }
	// RVA: 0x33dde00 VA: 0x75959f5e00
	private IEnumerator _ShowIllustAndBattleInfo() { }
	// RVA: 0x33ddeac VA: 0x75959f5eac
	private IEnumerator _ShowFinalStagePoint() { }
	// RVA: 0x33ddf58 VA: 0x75959f5f58
	private IEnumerator _WaitFinalStagePoint() { }
	// RVA: 0x33de004 VA: 0x75959f6004
	private IEnumerator _ShowDropInfo() { }
	// RVA: 0x33de0b0 VA: 0x75959f60b0
	public Void .ctor() { }
	// RVA: 0x33de160 VA: 0x75959f6160
	private Void <OnInit>b__19_0() { }
	// RVA: 0x33de1d8 VA: 0x75959f61d8
	private Void <_EventOnConfirmDefendClicked>b__21_0(Act1LockSetDefendResponse response) { }
	// RVA: 0x33de210 VA: 0x75959f6210
	private Boolean <_ShowDefendView>b__27_0() { }
	// RVA: 0x33de22c VA: 0x75959f622c
	private Boolean <_ShowDefendView>b__27_1() { }
	// RVA: 0x33de23c VA: 0x75959f623c
	private Boolean <_ShowFinalStagePoint>b__29_0() { }
	// RVA: 0x33de260 VA: 0x75959f6260
	private Boolean <_ShowFinalStagePoint>b__29_1() { }
	// RVA: 0x33de270 VA: 0x75959f6270
	private Void <_ShowDropInfo>b__31_0() { }
}
```