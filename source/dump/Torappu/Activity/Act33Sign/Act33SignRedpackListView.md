# Act33SignRedpackListView

**Namespace:** `Torappu.Activity.Act33Sign`


## Fields

- `SimpleLayoutContent _redpackContent`

- `CanvasGroup _canvasGroup`

- `UIBlurFloatPanel _blurPanel`

- `Act33SignRedpackListAdapter m_adapter`


## Methods

- `Void _RenderList(Act33SignRedpackViewModel)`

- `Void CloseView()`

- `Void Show(Act33SignRedpackViewModel)`

- `Void Hide()`

- `Void <Hide>b__10_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act33Sign
public class Act33SignRedpackListView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _redpackContent; // 0x18
	private CanvasGroup _canvasGroup; // 0x20
	private UIBlurFloatPanel _blurPanel; // 0x28
	private Act33SignRedpackListAdapter m_adapter; // 0x30
	private const Single ALPHA_ONE; // 0x0
	private const Single ALPHA_ZERO; // 0x0
	private const Single TWEEN_DURATION; // 0x0
	private static DelegateBridge __Hotfix0__RenderList; // 0x0
	private static DelegateBridge __Hotfix0_CloseView; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3256894 VA: 0x759586e894
	private Void _RenderList(Act33SignRedpackViewModel viewModel) { }
	// RVA: 0x3256b9c VA: 0x759586eb9c
	public Void CloseView() { }
	// RVA: 0x3254d80 VA: 0x759586cd80
	public Void Show(Act33SignRedpackViewModel viewModel) { }
	// RVA: 0x325505c VA: 0x759586d05c
	public Void Hide() { }
	// RVA: 0x3256c0c VA: 0x759586ec0c
	public Void .ctor() { }
	// RVA: 0x3256c7c VA: 0x759586ec7c
	private Void <Hide>b__10_0() { }
}
```