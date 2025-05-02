# BuildingFloatVisitAlertView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `GameObject _panelActive`

- `GameObject _panelInactive`

- `Text _textSocialPtActive`

- `Text _textDesc`

- `UIAnimationLocation _animShow`

- `UIAnimationLocation _animHide`

- `Boolean m_isShowing`

- `VisitAlertViewModel m_viewModel`


## Methods

- `Void Show(VisitAlertViewModel)`

- `Void _RenderContent()`

- `Void <Show>b__9_0()`

- `Void <Show>b__9_1(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatVisitAlertView : MonoBehaviour
{
	private const Single SHOW_CONTENT_TIME; // 0x0
	private GameObject _panelActive; // 0x18
	private GameObject _panelInactive; // 0x20
	private Text _textSocialPtActive; // 0x28
	private Text _textDesc; // 0x30
	private UIAnimationLocation _animShow; // 0x38
	private UIAnimationLocation _animHide; // 0x48
	private Boolean m_isShowing; // 0x58
	private VisitAlertViewModel m_viewModel; // 0x60


	// RVA: 0x3e2f9bc VA: 0x75964479bc
	public Void Show(VisitAlertViewModel viewModel) { }
	// RVA: 0x3e2fa90 VA: 0x7596447a90
	private Void _RenderContent() { }
	// RVA: 0x3e2fbac VA: 0x7596447bac
	public Void .ctor() { }
	// RVA: 0x3e2fbb4 VA: 0x7596447bb4
	private Void <Show>b__9_0() { }
	// RVA: 0x3e2fcc0 VA: 0x7596447cc0
	private Void <Show>b__9_1(String _) { }
}
```