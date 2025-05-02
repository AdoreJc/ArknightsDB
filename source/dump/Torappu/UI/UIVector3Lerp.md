# UIVector3Lerp

**Namespace:** `Torappu.UI`


## Fields

- `Mode _mode`

- `Vector3 _from`

- `Vector3 _to`

- `RectTransform _target`


## Properties

- `RectTransform rectTransform`


## Methods

- `RectTransform get_rectTransform()`

- `Void RecordFrom()`

- `Void ApplyFrom()`

- `Void RecordTo()`

- `Void ApplyTo()`

- `Void Lerp(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIVector3Lerp : MonoBehaviour
{
	private Mode _mode; // 0x18
	private Vector3 _from; // 0x1c
	private Vector3 _to; // 0x28
	private RectTransform _target; // 0x38

	public RectTransform rectTransform { get; }

	// RVA: 0x21cd0fc VA: 0x75947e50fc
	public RectTransform get_rectTransform() { }
	// RVA: 0x21cd1a4 VA: 0x75947e51a4
	public Void RecordFrom() { }
	// RVA: 0x21cd1fc VA: 0x75947e51fc
	public Void ApplyFrom() { }
	// RVA: 0x21cd260 VA: 0x75947e5260
	public Void RecordTo() { }
	// RVA: 0x21cd2b8 VA: 0x75947e52b8
	public Void ApplyTo() { }
	// RVA: 0x21cba00 VA: 0x75947e3a00
	public Void Lerp(Single value) { }
	// RVA: 0x21cd31c VA: 0x75947e531c
	public Void .ctor() { }
}
```