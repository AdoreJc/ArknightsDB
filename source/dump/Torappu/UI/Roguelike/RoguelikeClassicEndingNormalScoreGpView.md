# RoguelikeClassicEndingNormalScoreGpView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textGpNum`

- `RectTransform _gpProgressBar`

- `Vector2 _progressBarSize`

- `GameObject _normalPart`

- `GameObject _maxPart`

- `RoguelikeClassicEndingNormalViewModel m_cachedModel`

- `Tween m_cachedTween`


## Methods

- `Void Render(RoguelikeClassicEndingNormalViewModel, Boolean)`

- `Void _GetGpRank(Int32, Int32, out, out)`

- `Void _SetGpText(Int32, Int32, Int32)`

- `Void _SetProgress(Int32, Int32, Int32, Int32)`

- `IEnumerator TweenToTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeClassicEndingNormalScoreGpView : MonoBehaviour, IHotfixable
{
	private const String GP_SCORE_PREFIX; // 0x0
	private const Single GP_SCORE_PROGRESS_DURATION; // 0x0
	private const Single GP_SCORE_PROGRESS_INTERVAL; // 0x0
	private Text _textGpNum; // 0x18
	private RectTransform _gpProgressBar; // 0x20
	private Vector2 _progressBarSize; // 0x28
	private GameObject _normalPart; // 0x30
	private GameObject _maxPart; // 0x38
	private RoguelikeClassicEndingNormalViewModel m_cachedModel; // 0x40
	private Tween m_cachedTween; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GetGpRank; // 0x8
	private static DelegateBridge __Hotfix0__SetGpText; // 0x10
	private static DelegateBridge __Hotfix0__SetProgress; // 0x18
	private static DelegateBridge __Hotfix0_TweenToTarget; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2a25f00 VA: 0x759503df00
	public Void Render(RoguelikeClassicEndingNormalViewModel viewModel, Boolean fastMode) { }
	// RVA: 0x2a260ac VA: 0x759503e0ac
	private Void _GetGpRank(Int32 gp, Int32 gpRatio, out Int32 rank, out Int32 remainder) { }
	// RVA: 0x2a2616c VA: 0x759503e16c
	private Void _SetGpText(Int32 gp, Int32 accumulation, Int32 maxAccumulation) { }
	// RVA: 0x2a262a0 VA: 0x759503e2a0
	private Void _SetProgress(Int32 gpScore, Int32 gpRatio, Int32 accumulation, Int32 maxAccumulation) { }
	// RVA: 0x2a26370 VA: 0x759503e370
	public IEnumerator TweenToTarget() { }
	// RVA: 0x2a26444 VA: 0x759503e444
	public Void .ctor() { }
}
```