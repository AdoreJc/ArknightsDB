# UIDebugLocalTimePanel

**Namespace:** `Torappu.UI.DevTester`


## Fields

- `Text _textTime`

- `Text _textTs`

- `Slider _sliderSec`

- `Slider _sliderHour`

- `Boolean m_isInited`


## Methods

- `Void EventOnResetClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DevTester
public class UIDebugLocalTimePanel : MonoBehaviour
{
	private const Single CENTER_NORM_VAL; // 0x0
	private const Single SEC_SLIDER_UNIT; // 0x0
	private const Single HOUR_SLIDER_UNIT; // 0x0
	private const Single SLIDER_CHANGE_THRESHOLD; // 0x0
	private Text _textTime; // 0x18
	private Text _textTs; // 0x20
	private Slider _sliderSec; // 0x28
	private Slider _sliderHour; // 0x30
	private Boolean m_isInited; // 0x38


	// RVA: 0x29bb164 VA: 0x7594fd3164
	public Void EventOnResetClicked() { }
	// RVA: 0x29bb168 VA: 0x7594fd3168
	public Void .ctor() { }
}
```