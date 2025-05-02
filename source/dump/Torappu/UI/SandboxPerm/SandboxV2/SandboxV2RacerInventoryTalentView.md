# SandboxV2RacerInventoryTalentView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _canvasGroup`

- `Image _imgIcon`

- `Text _textDesc`

- `Text _textTitle`

- `GameObject _panelRefreshBtn`

- `UIAnimationLocation _learnedAnim`

- `UIStateFinder m_stateFinder`

- `Int32 m_cachedLearnTalentSequence`

- `Tween m_cachedLearnTween`


## Methods

- `Void Render(SandboxV2RacerTalentModel, Boolean, Int32)`

- `Void EventOnRefreshTalentClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerInventoryTalentView : MonoBehaviour, IHotfixable
{
	private const Single ALPHA_EMPTY; // 0x0
	private const Single ALPHA_NORMAL; // 0x0
	private CanvasGroup _canvasGroup; // 0x18
	private Image _imgIcon; // 0x20
	private Text _textDesc; // 0x28
	private Text _textTitle; // 0x30
	private GameObject _panelRefreshBtn; // 0x38
	private UIAnimationLocation _learnedAnim; // 0x40
	private UIStateFinder m_stateFinder; // 0x50
	private Int32 m_cachedLearnTalentSequence; // 0x60
	private Tween m_cachedLearnTween; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnRefreshTalentClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25dfb54 VA: 0x7594bf7b54
	public Void Render(SandboxV2RacerTalentModel model, Boolean showRefreshBtn, Int32 animSequenceNum) { }
	// RVA: 0x25e17c8 VA: 0x7594bf97c8
	public Void EventOnRefreshTalentClicked() { }
	// RVA: 0x25e186c VA: 0x7594bf986c
	public Void .ctor() { }
}
```