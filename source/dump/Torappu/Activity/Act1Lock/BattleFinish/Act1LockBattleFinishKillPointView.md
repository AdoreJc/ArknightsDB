# Act1LockBattleFinishKillPointView

**Namespace:** `Torappu.Activity.Act1Lock.BattleFinish`


## Fields

- `AnimationWrapper _animWrapper`

- `String _animName`

- `RectTransform _panelSuc`

- `RectTransform _panelFail`

- `RectTransform _panelNoInfo`

- `Text _textEnemyNameSuc`

- `Text _textEnemyNameFail`

- `Text _textPoint`


## Methods

- `Void Render(FinalStageEnemyKillPointModel)`

- `Void ShowImmediately()`

- `IEnumerator ShowCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.BattleFinish
public class Act1LockBattleFinishKillPointView : MonoBehaviour, IHotfixable
{
	private AnimationWrapper _animWrapper; // 0x18
	private String _animName; // 0x20
	private RectTransform _panelSuc; // 0x28
	private RectTransform _panelFail; // 0x30
	private RectTransform _panelNoInfo; // 0x38
	private Text _textEnemyNameSuc; // 0x40
	private Text _textEnemyNameFail; // 0x48
	private Text _textPoint; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x33dc054 VA: 0x75959f4054
	public Void Render(FinalStageEnemyKillPointModel viewModel) { }
	// RVA: 0x33dc1ac VA: 0x75959f41ac
	public Void ShowImmediately() { }
	// RVA: 0x33dc224 VA: 0x75959f4224
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x33dc2f8 VA: 0x75959f42f8
	public Void .ctor() { }
}
```