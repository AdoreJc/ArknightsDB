# ActVecBreakOffenseBattleFinishAnimationView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `GameObject _panelNormal`

- `GameObject _panelFinal`

- `GameObject _panelResult`

- `UIAnimationLocation _normalEnterAnim`

- `UIAnimationLocation _finalEnterAnim`

- `UIAnimationLocation _nextAnim`

- `Text _normalLevelText`

- `Text _finalLevelText`

- `ActVecBreakOffenseBattleFinishResultView _resultView`

- `Action onNextClick`

- `Action onCloseClick`

- `Boolean m_isInited`

- `Tween m_animTween`

- `Tween m_nextTween`

- `Boolean m_enableClick`

- `ActVecBreakOffenseBattleFinishViewModel m_viewModel`


## Methods

- `Void _InitAnimIfNot(VecBreakBattleFinishAnimationType)`

- `Void OnRender(ActVecBreakOffenseBattleFinishViewModel)`

- `IEnumerator ShowCoroutine()`

- `IEnumerator ShowNextCoroutine()`

- `Void OnNextClick()`

- `Void OnCloseClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class ActVecBreakOffenseBattleFinishAnimationView : MonoBehaviour, IHotfixable
{
	private const Single NORMAL_ANIM_NEXT_CLICK_ENABLE_INTERVAL; // 0x0
	private const Single FINAL_ANIM_NEXT_CLICK_ENABLE_INTERVAL; // 0x0
	private const Single RESULT_ANIM_SHOW_NOTIFICATION_INTERVAL; // 0x0
	private const Single RESULT_ANIM_CLOSE_CLICK_ENABLE_INTERVAL; // 0x0
	private GameObject _panelNormal; // 0x18
	private GameObject _panelFinal; // 0x20
	private GameObject _panelResult; // 0x28
	private UIAnimationLocation _normalEnterAnim; // 0x30
	private UIAnimationLocation _finalEnterAnim; // 0x40
	private UIAnimationLocation _nextAnim; // 0x50
	private Text _normalLevelText; // 0x60
	private Text _finalLevelText; // 0x68
	private ActVecBreakOffenseBattleFinishResultView _resultView; // 0x70
	public Action onNextClick; // 0x78
	public Action onCloseClick; // 0x80
	private Boolean m_isInited; // 0x88
	private Tween m_animTween; // 0x90
	private Tween m_nextTween; // 0x98
	private Boolean m_enableClick; // 0xa0
	private ActVecBreakOffenseBattleFinishViewModel m_viewModel; // 0xa8
	private static DelegateBridge __Hotfix0__InitAnimIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_ShowNextCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_OnNextClick; // 0x20
	private static DelegateBridge __Hotfix0_OnCloseClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x22a2dd0 VA: 0x75948badd0
	private Void _InitAnimIfNot(VecBreakBattleFinishAnimationType animationType) { }
	// RVA: 0x22a2ebc VA: 0x75948baebc
	public Void OnRender(ActVecBreakOffenseBattleFinishViewModel viewModel) { }
	// RVA: 0x22a30d4 VA: 0x75948bb0d4
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x22a31a8 VA: 0x75948bb1a8
	public IEnumerator ShowNextCoroutine() { }
	// RVA: 0x22a327c VA: 0x75948bb27c
	public Void OnNextClick() { }
	// RVA: 0x22a3308 VA: 0x75948bb308
	public Void OnCloseClick() { }
	// RVA: 0x22a3394 VA: 0x75948bb394
	public Void .ctor() { }
}
```