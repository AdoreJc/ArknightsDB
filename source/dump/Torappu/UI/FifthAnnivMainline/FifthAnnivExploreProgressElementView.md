# FifthAnnivExploreProgressElementView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `LayoutElement _layoutElement`

- `CanvasGroup _canvasDot`

- `SimpleLayoutContent _groupDot`

- `RectTransform _rectProgress`

- `UIColorGraphic _colorGraphic`

- `Boolean m_inited`

- `UISwitchTween m_expandTween`

- `Tween m_progressTween`

- `Adapter m_adapter`

- `Int32 m_cachedStageNodeCount`

- `Int32 m_cachedInitSeq`


## Properties

- `UIColorGraphic colorGraphic`


## Methods

- `UIColorGraphic get_colorGraphic()`

- `Void _InitIfNot()`

- `Void _SetProgress(Single, Boolean)`

- `Void Render(Int32, FifthAnnivExploreProgressViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreProgressElementView : MonoBehaviour, IHotfixable
{
	private const Single ANIM_DURATION; // 0x0
	private LayoutElement _layoutElement; // 0x18
	private CanvasGroup _canvasDot; // 0x20
	private SimpleLayoutContent _groupDot; // 0x28
	private RectTransform _rectProgress; // 0x30
	private UIColorGraphic _colorGraphic; // 0x38
	private Boolean m_inited; // 0x40
	private UISwitchTween m_expandTween; // 0x48
	private Tween m_progressTween; // 0x50
	private Adapter m_adapter; // 0x58
	private Int32 m_cachedStageNodeCount; // 0x60
	private Int32 m_cachedInitSeq; // 0x64
	private static DelegateBridge __Hotfix0_get_colorGraphic; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__SetProgress; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public UIColorGraphic colorGraphic { get; }

	// RVA: 0x2930b9c VA: 0x7594f48b9c
	public UIColorGraphic get_colorGraphic() { }
	// RVA: 0x2930c04 VA: 0x7594f48c04
	private Void _InitIfNot() { }
	// RVA: 0x2930e38 VA: 0x7594f48e38
	private Void _SetProgress(Single targetProgress, Boolean fastMode) { }
	// RVA: 0x2930fa0 VA: 0x7594f48fa0
	public Void Render(Int32 index, FifthAnnivExploreProgressViewModel viewModel) { }
	// RVA: 0x29310f0 VA: 0x7594f490f0
	public Void .ctor() { }
}
```