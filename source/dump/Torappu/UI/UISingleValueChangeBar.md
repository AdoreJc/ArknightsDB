# UISingleValueChangeBar

**Namespace:** `Torappu.UI`


## Fields

- `StretchProgressBar _progressBar`

- `Text _currentValue`

- `Text _maxValue`

- `Single _tweenTime`

- `Options m_options`

- `Tween m_tween`

- `Single m_startProgress`

- `Single m_endProgress`


## Methods

- `Void SetData(Options)`

- `Void StartTween(TweenCallback)`

- `Void _Render(Single)`

- `Void _ClearTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISingleValueChangeBar : MonoBehaviour
{
	private StretchProgressBar _progressBar; // 0x18
	private Text _currentValue; // 0x20
	private Text _maxValue; // 0x28
	private Single _tweenTime; // 0x30
	private Options m_options; // 0x34
	private Tween m_tween; // 0x40
	private Single m_startProgress; // 0x48
	private Single m_endProgress; // 0x4c


	// RVA: 0x2254898 VA: 0x759486c898
	public Void SetData(Options options) { }
	// RVA: 0x22549f4 VA: 0x759486c9f4
	public Void StartTween(TweenCallback onComplete) { }
	// RVA: 0x2254be8 VA: 0x759486cbe8
	private Void _Render(Single progress) { }
	// RVA: 0x22549bc VA: 0x759486c9bc
	private Void _ClearTween() { }
	// RVA: 0x2254cd0 VA: 0x759486ccd0
	public Void .ctor() { }
}
```