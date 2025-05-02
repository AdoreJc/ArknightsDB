# BattleFinishHomeView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `UIExpBar _playerExpBar`

- `UISingleValueChangeBar _campaignFeeBar`

- `BattleFinishInfoView _battleInfoView`

- `Text _pryIntro`

- `BattleFinishDropInfoView _dropInfoView`

- `Transform _pryDropRoot`

- `BattleFinishDropPryInfoView _pryDropViewPrefab`

- `BattleFinishIllustView _illustView`

- `Animator _favoutAnimator`

- `RectTransform _metaViewContainer`

- `BattleFinishDropRewardFrameHolder _frameHolder`

- `Boolean m_isShowingChar`

- `Boolean m_isLoadingAnimEnd`

- `Single m_animEndTime`

- `UIExpBarController m_expBarController`

- `BattleFinishMetaDisplayView m_metaDisplayView`

- `Host m_host`


## Methods

- `Void Init(Host)`

- `Void DoShowEffect()`

- `Void EventOnViewClicked()`

- `IEnumerator _FinishBattleActCoroutine()`

- `Void _RenderDrop()`

- `IEnumerator _RenderDropCoroutine()`

- `Void _TryToInitMetaDisplayView()`

- `Boolean _TryToShowMetaDisplayView()`

- `Void <DoShowEffect>b__21_0()`

- `Void <_FinishBattleActCoroutine>b__23_1(Output)`

- `Void <_FinishBattleActCoroutine>b__23_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishHomeView : MonoBehaviour, IHotfixable
{
	private const Single PASTTIME; // 0x0
	private UIExpBar _playerExpBar; // 0x18
	private UISingleValueChangeBar _campaignFeeBar; // 0x20
	private BattleFinishInfoView _battleInfoView; // 0x28
	private Text _pryIntro; // 0x30
	private BattleFinishDropInfoView _dropInfoView; // 0x38
	private Transform _pryDropRoot; // 0x40
	private BattleFinishDropPryInfoView _pryDropViewPrefab; // 0x48
	private BattleFinishIllustView _illustView; // 0x50
	private Animator _favoutAnimator; // 0x58
	private RectTransform _metaViewContainer; // 0x60
	private BattleFinishDropRewardFrameHolder _frameHolder; // 0x68
	private Boolean m_isShowingChar; // 0x70
	private Boolean m_isLoadingAnimEnd; // 0x71
	private Single m_animEndTime; // 0x74
	private UIExpBarController m_expBarController; // 0x78
	private List`1 m_pryDropViews; // 0x80
	private BattleFinishMetaDisplayView m_metaDisplayView; // 0x88
	private Host m_host; // 0x90
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_DoShowEffect; // 0x8
	private static DelegateBridge __Hotfix0_EventOnViewClicked; // 0x10
	private static DelegateBridge __Hotfix0__FinishBattleActCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__RenderDrop; // 0x20
	private static DelegateBridge __Hotfix0__RenderDropCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__TryToInitMetaDisplayView; // 0x30
	private static DelegateBridge __Hotfix0__TryToShowMetaDisplayView; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2e8f95c VA: 0x75954a795c
	public Void Init(Host host) { }
	// RVA: 0x2e90084 VA: 0x75954a8084
	public Void DoShowEffect() { }
	// RVA: 0x2e90268 VA: 0x75954a8268
	public Void EventOnViewClicked() { }
	// RVA: 0x2e90468 VA: 0x75954a8468
	private IEnumerator _FinishBattleActCoroutine() { }
	// RVA: 0x2e9053c VA: 0x75954a853c
	private Void _RenderDrop() { }
	// RVA: 0x2e907fc VA: 0x75954a87fc
	private IEnumerator _RenderDropCoroutine() { }
	// RVA: 0x2e8febc VA: 0x75954a7ebc
	private Void _TryToInitMetaDisplayView() { }
	// RVA: 0x2e90360 VA: 0x75954a8360
	private Boolean _TryToShowMetaDisplayView() { }
	// RVA: 0x2e90b20 VA: 0x75954a8b20
	public Void .ctor() { }
	// RVA: 0x2e90b90 VA: 0x75954a8b90
	private Void <DoShowEffect>b__21_0() { }
	// RVA: 0x2e90bc0 VA: 0x75954a8bc0
	private Void <_FinishBattleActCoroutine>b__23_1(Output output) { }
	// RVA: 0x2e90bc8 VA: 0x75954a8bc8
	private Void <_FinishBattleActCoroutine>b__23_0() { }
}
```