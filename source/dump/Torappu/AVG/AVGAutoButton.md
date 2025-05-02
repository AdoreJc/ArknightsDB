# AVGAutoButton

**Namespace:** `Torappu.AVG`


## Fields

- `RectTransform _image`

- `GameObject _text`

- `Single _noPlayWidth`

- `Single _defaultWidth`

- `Single _stepWidth`

- `Single _stepCount`

- `Single _stepTime`

- `Vector2 _defaultPos`

- `Vector2 _posWithoutSkipBtn`

- `Tweener m_tweener`


## Methods

- `Void SetPos(Boolean)`

- `Void SetIsAutoPlaying(AVGAutoMode)`

- `Void _StopTween()`

- `Void <SetIsAutoPlaying>b__11_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGAutoButton : MonoBehaviour
{
	private RectTransform _image; // 0x18
	private GameObject _text; // 0x20
	private Single _noPlayWidth; // 0x28
	private Single _defaultWidth; // 0x2c
	private Single _stepWidth; // 0x30
	private Single _stepCount; // 0x34
	private Single _stepTime; // 0x38
	private Vector2 _defaultPos; // 0x3c
	private Vector2 _posWithoutSkipBtn; // 0x44
	private Tweener m_tweener; // 0x50


	// RVA: 0x3e9f38c VA: 0x75964b738c
	public Void SetPos(Boolean hasSkipBtn) { }
	// RVA: 0x3e9f3e8 VA: 0x75964b73e8
	public Void SetIsAutoPlaying(AVGAutoMode autoMode) { }
	// RVA: 0x3e9f64c VA: 0x75964b764c
	private Void _StopTween() { }
	// RVA: 0x3e9f684 VA: 0x75964b7684
	public Void .ctor() { }
	// RVA: 0x3e9f68c VA: 0x75964b768c
	private Void <SetIsAutoPlaying>b__11_1(Single val) { }
}
```