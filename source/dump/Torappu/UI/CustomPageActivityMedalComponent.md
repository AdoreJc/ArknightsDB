# CustomPageActivityMedalComponent

**Namespace:** `Torappu.UI`


## Fields

- `Text _textProgress`

- `Slider _progressSlider`

- `Color _progressColor`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CustomPageActivityMedalComponent : CustomPageActivityComponent, IHotfixable
{
	private static readonly Color PROGRESS_DEFAULT_COLOR; // 0x0
	private Text _textProgress; // 0x20
	private Slider _progressSlider; // 0x28
	private Color _progressColor; // 0x30
	private static DelegateBridge __Hotfix0_get_param; // 0x10
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override String param { get; }

	// RVA: 0x226a2cc VA: 0x75948822cc
	public override String get_param() { }
	// RVA: 0x226a358 VA: 0x7594882358
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x226a530 VA: 0x7594882530
	public Void .ctor() { }
	// RVA: 0x226a5bc VA: 0x75948825bc
	private static Void .cctor() { }
}
```