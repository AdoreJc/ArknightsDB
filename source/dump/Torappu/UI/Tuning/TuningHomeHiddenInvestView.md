# TuningHomeHiddenInvestView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `GameObject _panelUncomplete`

- `GameObject _panelComplete`

- `Image _imgCharacter`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(TuningHomeHiddenInvestViewModel)`

- `Void EventOnStartInvestClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeHiddenInvestView : MonoBehaviour, IHotfixable
{
	private GameObject _panelUncomplete; // 0x18
	private GameObject _panelComplete; // 0x20
	private Image _imgCharacter; // 0x28
	private Text[] _textNpcName; // 0x30
	private UIStateFinder m_stateFinder; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnStartInvestClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x23264a8 VA: 0x759493e4a8
	public Void Render(TuningHomeHiddenInvestViewModel viewModel) { }
	// RVA: 0x2326674 VA: 0x759493e674
	public Void EventOnStartInvestClicked() { }
	// RVA: 0x23267a8 VA: 0x759493e7a8
	public Void .ctor() { }
}
```