# FifthAnnivExploreTopMenuProgressView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `SimpleLayoutContent _progressContent`

- `UIColorGraphic _colorGraphic`

- `UIAnimationLocation _animLoop`

- `Boolean m_inited`

- `Adapter m_progressAdapter`

- `FifthAnnivExploreProgressViewModel m_cachedProgressViewModel`

- `Tween m_loopTween`

- `Action <onClick>k__BackingField`


## Properties

- `Action onClick`


## Methods

- `Void _InitIfNot()`

- `Void set_onClick(Action)`

- `Action get_onClick()`

- `Void OnClick()`

- `Void Render(FifthAnnivExploreProgressViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreTopMenuProgressView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _progressContent; // 0x18
	private UIColorGraphic _colorGraphic; // 0x20
	private UIAnimationLocation _animLoop; // 0x28
	private Boolean m_inited; // 0x38
	private Adapter m_progressAdapter; // 0x40
	private FifthAnnivExploreProgressViewModel m_cachedProgressViewModel; // 0x48
	private Tween m_loopTween; // 0x50
	private Action <onClick>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onClick; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action onClick { get; set; }

	// RVA: 0x2932acc VA: 0x7594f4aacc
	private Void _InitIfNot() { }
	// RVA: 0x2932cdc VA: 0x7594f4acdc
	public Void set_onClick(Action value) { }
	// RVA: 0x2932d60 VA: 0x7594f4ad60
	private Action get_onClick() { }
	// RVA: 0x2932dc8 VA: 0x7594f4adc8
	public Void OnClick() { }
	// RVA: 0x2932e64 VA: 0x7594f4ae64
	public Void Render(FifthAnnivExploreProgressViewModel viewModel) { }
	// RVA: 0x2932f1c VA: 0x7594f4af1c
	public Void .ctor() { }
}
```