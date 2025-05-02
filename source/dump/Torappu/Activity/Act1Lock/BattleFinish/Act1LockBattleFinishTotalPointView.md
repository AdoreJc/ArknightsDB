# Act1LockBattleFinishTotalPointView

**Namespace:** `Torappu.Activity.Act1Lock.BattleFinish`


## Fields

- `AnimationWrapper _animWrapper`

- `String _animClearPoint`

- `String _animTotalPoint`

- `CanvasGroup _canvasGroup`

- `Text _textClearPoint`

- `Text _textTotalPoint`

- `EasyInstancePool _enemyKillPoints`

- `Boolean <isShowing>k__BackingField`


## Properties

- `Boolean isShowing`


## Methods

- `Boolean get_isShowing()`

- `Void set_isShowing(Boolean)`

- `Void Render(FinalStagePointModel)`

- `Void ShowImmediately()`

- `IEnumerator ShowCoroutine()`

- `IEnumerator HideCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.BattleFinish
public class Act1LockBattleFinishTotalPointView : MonoBehaviour, IHotfixable
{
	private const Single FADE_TIME; // 0x0
	private AnimationWrapper _animWrapper; // 0x18
	private String _animClearPoint; // 0x20
	private String _animTotalPoint; // 0x28
	private CanvasGroup _canvasGroup; // 0x30
	private Text _textClearPoint; // 0x38
	private Text _textTotalPoint; // 0x40
	private EasyInstancePool _enemyKillPoints; // 0x48
	private Boolean <isShowing>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_isShowing; // 0x0
	private static DelegateBridge __Hotfix0_set_isShowing; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x18
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isShowing { get; set; }

	// RVA: 0x33dc634 VA: 0x75959f4634
	public Boolean get_isShowing() { }
	// RVA: 0x33dc69c VA: 0x75959f469c
	private Void set_isShowing(Boolean value) { }
	// RVA: 0x33dc71c VA: 0x75959f471c
	public Void Render(FinalStagePointModel viewModel) { }
	// RVA: 0x33dc948 VA: 0x75959f4948
	public Void ShowImmediately() { }
	// RVA: 0x33dcad0 VA: 0x75959f4ad0
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x33dcba4 VA: 0x75959f4ba4
	public IEnumerator HideCoroutine() { }
	// RVA: 0x33dcc78 VA: 0x75959f4c78
	public Void .ctor() { }
}
```