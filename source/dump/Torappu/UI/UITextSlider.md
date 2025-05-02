# UITextSlider

**Namespace:** `Torappu.UI`


## Fields

- `Slider _slider`

- `Image _sliderFillImage`

- `Text _text`

- `TextMode _textMode`


## Properties

- `Single value`

- `Color color`


## Methods

- `Single get_value()`

- `Void set_value(Single)`

- `Color get_color()`

- `Void set_color(Color)`

- `Void SetRawText(String, Single)`

- `Void SetFillAreaColor(Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UITextSlider : MonoBehaviour
{
	protected Slider _slider; // 0x18
	protected Image _sliderFillImage; // 0x20
	private Text _text; // 0x28
	private TextMode _textMode; // 0x30

	public Single value { get; set; }
	public Color color { get; set; }

	// RVA: 0x22579dc VA: 0x759486f9dc
	public Single get_value() { }
	// RVA: 0x2257a00 VA: 0x759486fa00
	public Void set_value(Single value) { }
	// RVA: 0x2257bc8 VA: 0x759486fbc8
	public Color get_color() { }
	// RVA: 0x2257c4c VA: 0x759486fc4c
	public Void set_color(Color value) { }
	// RVA: 0x2257d58 VA: 0x759486fd58
	public virtual Void SetSliderColorByProgress(Single progress) { }
	// RVA: 0x2257d5c VA: 0x759486fd5c
	public virtual Void SetValue(Single current, Single maximum) { }
	// RVA: 0x2258060 VA: 0x7594870060
	public Void SetRawText(String text, Single value) { }
	// RVA: 0x2258118 VA: 0x7594870118
	public Void SetFillAreaColor(Color color) { }
	// RVA: 0x22581dc VA: 0x75948701dc
	public Void .ctor() { }
}
```