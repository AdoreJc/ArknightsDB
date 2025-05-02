# Act24sideBattleFinishView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `UIFullScreenImage _blurBackground`

- `UIExpBar _playerExpBar`

- `Act24sideBattleFinishInfoView _battleInfoView`

- `BattleFinishDropInfoView _dropInfoView`

- `Act24sideBattleFinishMeldingDropInfoView _meldingDropInfoView`

- `Transform _meldingDropRoot`

- `BattleFinishIllustView _illustView`

- `Animator _favoutAnimator`

- `Act24sideBattleFinishViewModel m_viewModel`

- `UIExpBarController m_expBarController`

- `Boolean m_isLoadingAnimEnd`

- `Single m_animEndTime`

- `Act24sideBattleFinishMeldingDropInfoView m_meldingDropInfoView`


## Methods

- `Void _Render()`

- `IEnumerator _FinishBattleActCoroutine()`

- `Void _RenderDrop()`

- `IEnumerator _RenderDropCoroutine()`

- `Void EventOnPageClicked()`

- `Void <_Render>b__15_0()`

- `Void <_FinishBattleActCoroutine>b__16_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleFinishView : ActivityBattleFinishView
{
	private const Single PASTTIME; // 0x0
	private UIFullScreenImage _blurBackground; // 0x30
	private UIExpBar _playerExpBar; // 0x38
	private Act24sideBattleFinishInfoView _battleInfoView; // 0x40
	private BattleFinishDropInfoView _dropInfoView; // 0x48
	private Act24sideBattleFinishMeldingDropInfoView _meldingDropInfoView; // 0x50
	private Transform _meldingDropRoot; // 0x58
	private BattleFinishIllustView _illustView; // 0x60
	private Animator _favoutAnimator; // 0x68
	private Act24sideBattleFinishViewModel m_viewModel; // 0x70
	private UIExpBarController m_expBarController; // 0x78
	private Boolean m_isLoadingAnimEnd; // 0x80
	private Single m_animEndTime; // 0x84
	private Act24sideBattleFinishMeldingDropInfoView m_meldingDropInfoView; // 0x88
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__FinishBattleActCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__RenderDrop; // 0x18
	private static DelegateBridge __Hotfix0__RenderDropCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_EventOnPageClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3291e34 VA: 0x75958a9e34
	protected override Void OnInit() { }
	// RVA: 0x32925e8 VA: 0x75958aa5e8
	private Void _Render() { }
	// RVA: 0x329279c VA: 0x75958aa79c
	private IEnumerator _FinishBattleActCoroutine() { }
	// RVA: 0x3292870 VA: 0x75958aa870
	private Void _RenderDrop() { }
	// RVA: 0x3292978 VA: 0x75958aa978
	private IEnumerator _RenderDropCoroutine() { }
	// RVA: 0x3292a4c VA: 0x75958aaa4c
	public Void EventOnPageClicked() { }
	// RVA: 0x3292af0 VA: 0x75958aaaf0
	public Void .ctor() { }
	// RVA: 0x3292c0c VA: 0x75958aac0c
	private Void <_Render>b__15_0() { }
	// RVA: 0x3292c74 VA: 0x75958aac74
	private Void <_FinishBattleActCoroutine>b__16_0() { }
}
```