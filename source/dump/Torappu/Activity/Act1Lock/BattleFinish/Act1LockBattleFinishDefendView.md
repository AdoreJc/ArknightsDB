# Act1LockBattleFinishDefendView

**Namespace:** `Torappu.Activity.Act1Lock.BattleFinish`


## Fields

- `CanvasGroup _canvasGroup`

- `CanvasGroup _defendSucCanvasGroup`

- `AnimationWrapper _animWrapper`

- `String _animDefendSuc`

- `UIFullScreenImage _blurBkg`

- `Text _textStageCode`

- `Text _textStageName`

- `Text _textDefendSucStageCode`

- `Text _textDefendSucStageName`

- `Text _textCharCntBefore`

- `Text _textCharCntAfter`

- `Text _textDesc`

- `EasyInstancePool _charsBefore`

- `EasyInstancePool _charsAfter`

- `RectTransform _panelDefendSuc`

- `UIRenderTextureImage _defendSucBlurBkg`

- `InterlockStageDefendModel m_cacheModel`

- `Action <onConfirmClicked>k__BackingField`

- `Action <onCancelClicked>k__BackingField`

- `Action <onDefendSucClicked>k__BackingField`


## Properties

- `Action onConfirmClicked`

- `Action onCancelClicked`

- `Action onDefendSucClicked`


## Methods

- `Action get_onConfirmClicked()`

- `Void set_onConfirmClicked(Action)`

- `Action get_onCancelClicked()`

- `Void set_onCancelClicked(Action)`

- `Action get_onDefendSucClicked()`

- `Void set_onDefendSucClicked(Action)`

- `Void EventOnConfirmClicked()`

- `Void EventOnCancelClicked()`

- `Void EventOnDefendSucClicked()`

- `Void Render(InterlockStageDefendModel)`

- `IEnumerator ShowCoroutine()`

- `IEnumerator ShowDefendSucCoroutine()`

- `Void Hide()`

- `Void _RenderDefend()`

- `Void _RenderReplace()`

- `Void <Hide>b__37_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.BattleFinish
public class Act1LockBattleFinishDefendView : MonoBehaviour, IHotfixable
{
	private const Single FADE_TIME; // 0x0
	private CanvasGroup _canvasGroup; // 0x18
	private CanvasGroup _defendSucCanvasGroup; // 0x20
	private AnimationWrapper _animWrapper; // 0x28
	private String _animDefendSuc; // 0x30
	private UIFullScreenImage _blurBkg; // 0x38
	private List`1 _battleRanks; // 0x40
	private Text _textStageCode; // 0x48
	private Text _textStageName; // 0x50
	private Text _textDefendSucStageCode; // 0x58
	private Text _textDefendSucStageName; // 0x60
	private Text _textCharCntBefore; // 0x68
	private Text _textCharCntAfter; // 0x70
	private Text _textDesc; // 0x78
	private EasyInstancePool _charsBefore; // 0x80
	private EasyInstancePool _charsAfter; // 0x88
	private RectTransform _panelDefendSuc; // 0x90
	private UIRenderTextureImage _defendSucBlurBkg; // 0x98
	private InterlockStageDefendModel m_cacheModel; // 0xa0
	private Action <onConfirmClicked>k__BackingField; // 0xa8
	private Action <onCancelClicked>k__BackingField; // 0xb0
	private Action <onDefendSucClicked>k__BackingField; // 0xb8
	private static DelegateBridge __Hotfix0_get_onConfirmClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onConfirmClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onCancelClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onCancelClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onDefendSucClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onDefendSucClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnDefendSucClicked; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x48
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_ShowDefendSucCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_Hide; // 0x60
	private static DelegateBridge __Hotfix0__RenderDefend; // 0x68
	private static DelegateBridge __Hotfix0__RenderReplace; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Action onConfirmClicked { get; set; }
	public Action onCancelClicked { get; set; }
	public Action onDefendSucClicked { get; set; }

	// RVA: 0x33dad28 VA: 0x75959f2d28
	public Action get_onConfirmClicked() { }
	// RVA: 0x33dad90 VA: 0x75959f2d90
	public Void set_onConfirmClicked(Action value) { }
	// RVA: 0x33dae14 VA: 0x75959f2e14
	public Action get_onCancelClicked() { }
	// RVA: 0x33dae7c VA: 0x75959f2e7c
	public Void set_onCancelClicked(Action value) { }
	// RVA: 0x33daf00 VA: 0x75959f2f00
	public Action get_onDefendSucClicked() { }
	// RVA: 0x33daf68 VA: 0x75959f2f68
	public Void set_onDefendSucClicked(Action value) { }
	// RVA: 0x33dafec VA: 0x75959f2fec
	public Void EventOnConfirmClicked() { }
	// RVA: 0x33db088 VA: 0x75959f3088
	public Void EventOnCancelClicked() { }
	// RVA: 0x33db124 VA: 0x75959f3124
	public Void EventOnDefendSucClicked() { }
	// RVA: 0x33db1c0 VA: 0x75959f31c0
	public Void Render(InterlockStageDefendModel viewModel) { }
	// RVA: 0x33db804 VA: 0x75959f3804
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x33db8d8 VA: 0x75959f38d8
	public IEnumerator ShowDefendSucCoroutine() { }
	// RVA: 0x33db9ac VA: 0x75959f39ac
	public Void Hide() { }
	// RVA: 0x33db614 VA: 0x75959f3614
	private Void _RenderDefend() { }
	// RVA: 0x33db384 VA: 0x75959f3384
	private Void _RenderReplace() { }
	// RVA: 0x33dbabc VA: 0x75959f3abc
	public Void .ctor() { }
	// RVA: 0x33dbb2c VA: 0x75959f3b2c
	private Void <Hide>b__37_0() { }
}
```