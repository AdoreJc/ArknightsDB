# ColorTemplate

**Namespace:** `Torappu.Battle.DevelopTools`


## Fields

- `Slider _rSlider`

- `Slider _gSlider`

- `Slider _bSlider`

- `Image _colorShow`


## Methods

- `Void OnInit(Action`1, Color)`

- `Void Start()`

- `Void _EventOnSliderValueChanged(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.DevelopTools
public class ColorTemplate : MonoBehaviour
{
	private Slider _rSlider; // 0x18
	private Slider _gSlider; // 0x20
	private Slider _bSlider; // 0x28
	private Image _colorShow; // 0x30
	private Action`1 m_callback; // 0x38


	// RVA: 0x1d2c6e8 VA: 0x75943446e8
	public Void OnInit(Action`1 callback, Color initColor) { }
	// RVA: 0x1d2c7c8 VA: 0x75943447c8
	private Void Start() { }
	// RVA: 0x1d2c900 VA: 0x7594344900
	private Void _EventOnSliderValueChanged(Single value) { }
	// RVA: 0x1d2c9cc VA: 0x75943449cc
	public Void .ctor() { }
}
```