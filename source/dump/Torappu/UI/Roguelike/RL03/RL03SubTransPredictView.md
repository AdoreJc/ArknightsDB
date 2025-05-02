# RL03SubTransPredictView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `CanvasGroup _panelMainTrans`

- `AudioClickPlayer _clickAudio`

- `UIAnimationLocation _animEnter`

- `TotemView _totemView`

- `ChaosView _chaosView`

- `Text _textDescription`

- `Boolean m_isInited`

- `Tween m_enterTween`

- `FadeSwitchTween m_mainTransSwitch`

- `Boolean m_isTotemPredict`


## Methods

- `Void _InitIfNot()`

- `Void Render(PredictModel)`

- `IEnumerator TransCoroutine()`

- `Void Reset()`

- `Void Hide()`

- `Boolean <TransCoroutine>b__15_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03SubTransPredictView : MonoBehaviour, IHotfixable
{
	private const Single HIDE_TWEEN_DURATION; // 0x0
	private CanvasGroup _panelMainTrans; // 0x18
	private AudioClickPlayer _clickAudio; // 0x20
	private UIAnimationLocation _animEnter; // 0x28
	private TotemView _totemView; // 0x38
	private ChaosView _chaosView; // 0x40
	private Text _textDescription; // 0x48
	private Boolean m_isInited; // 0x50
	private Tween m_enterTween; // 0x58
	private FadeSwitchTween m_mainTransSwitch; // 0x60
	private Boolean m_isTotemPredict; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_TransCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0_Hide; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2bb562c VA: 0x75951cd62c
	private Void _InitIfNot() { }
	// RVA: 0x2bb496c VA: 0x75951cc96c
	public Void Render(PredictModel predictModel) { }
	// RVA: 0x2bb54b8 VA: 0x75951cd4b8
	public IEnumerator TransCoroutine() { }
	// RVA: 0x2bb4c44 VA: 0x75951ccc44
	public Void Reset() { }
	// RVA: 0x2bb5564 VA: 0x75951cd564
	public Void Hide() { }
	// RVA: 0x2bb570c VA: 0x75951cd70c
	public Void .ctor() { }
	// RVA: 0x2bb577c VA: 0x75951cd77c
	private Boolean <TransCoroutine>b__15_0() { }
}
```