# RL03SubTransExpeditionReturnView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `CanvasGroup _panelMainTrans`

- `AudioClickPlayer _clickAudio`

- `AudioClickPlayer _clickAudioClose`

- `Text _charText`

- `Text _detailText`

- `UIAnimationLocation _animEnter`

- `GameObject _pnlClose`

- `GameObject _pnlNext`

- `Boolean m_isInited`

- `Tween m_enterTween`

- `FadeSwitchTween m_mainTransSwitch`

- `ExpeditionReturnModel m_cachedModel`

- `Boolean m_waitForConfirm`

- `Boolean m_isLast`

- `Action <onLastConfirmed>k__BackingField`


## Properties

- `Action onLastConfirmed`


## Methods

- `Action get_onLastConfirmed()`

- `Void set_onLastConfirmed(Action)`

- `Void _InitIfNot()`

- `Void _RenderSingle(Int32, Int32)`

- `IEnumerator _TransCoroutineSingle(Int32, Int32)`

- `Void Render(ExpeditionReturnModel)`

- `IEnumerator TransCoroutine()`

- `Void Reset()`

- `Void Hide()`

- `Void OnConfirmClicked()`

- `Boolean <_TransCoroutineSingle>b__21_0()`

- `Boolean <TransCoroutine>b__23_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03SubTransExpeditionReturnView : MonoBehaviour, IHotfixable
{
	private const Single HIDE_TWEEN_DURATION; // 0x0
	private CanvasGroup _panelMainTrans; // 0x18
	private AudioClickPlayer _clickAudio; // 0x20
	private AudioClickPlayer _clickAudioClose; // 0x28
	private Text _charText; // 0x30
	private Text _detailText; // 0x38
	private UIAnimationLocation _animEnter; // 0x40
	private GameObject _pnlClose; // 0x50
	private GameObject _pnlNext; // 0x58
	private Boolean m_isInited; // 0x60
	private Tween m_enterTween; // 0x68
	private FadeSwitchTween m_mainTransSwitch; // 0x70
	private ExpeditionReturnModel m_cachedModel; // 0x78
	private Boolean m_waitForConfirm; // 0x80
	private Boolean m_isLast; // 0x81
	private Action <onLastConfirmed>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_onLastConfirmed; // 0x0
	private static DelegateBridge __Hotfix0_set_onLastConfirmed; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__RenderSingle; // 0x18
	private static DelegateBridge __Hotfix0__TransCoroutineSingle; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_TransCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_Reset; // 0x38
	private static DelegateBridge __Hotfix0_Hide; // 0x40
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Action onLastConfirmed { get; set; }

	// RVA: 0x2bb3b10 VA: 0x75951cbb10
	public Action get_onLastConfirmed() { }
	// RVA: 0x2bb2fcc VA: 0x75951cafcc
	public Void set_onLastConfirmed(Action value) { }
	// RVA: 0x2bb3b78 VA: 0x75951cbb78
	private Void _InitIfNot() { }
	// RVA: 0x2bb3c58 VA: 0x75951cbc58
	private Void _RenderSingle(Int32 index, Int32 totalCount) { }
	// RVA: 0x2bb3df0 VA: 0x75951cbdf0
	private IEnumerator _TransCoroutineSingle(Int32 index, Int32 totalCount) { }
	// RVA: 0x2bb3050 VA: 0x75951cb050
	public Void Render(ExpeditionReturnModel viewModel) { }
	// RVA: 0x2bb3998 VA: 0x75951cb998
	public IEnumerator TransCoroutine() { }
	// RVA: 0x2bb32a0 VA: 0x75951cb2a0
	public Void Reset() { }
	// RVA: 0x2bb3a44 VA: 0x75951cba44
	public Void Hide() { }
	// RVA: 0x2bb3f0c VA: 0x75951cbf0c
	public Void OnConfirmClicked() { }
	// RVA: 0x2bb3fbc VA: 0x75951cbfbc
	public Void .ctor() { }
	// RVA: 0x2bb402c VA: 0x75951cc02c
	private Boolean <_TransCoroutineSingle>b__21_0() { }
	// RVA: 0x2bb4040 VA: 0x75951cc040
	private Boolean <TransCoroutine>b__23_0() { }
}
```