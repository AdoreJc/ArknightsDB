# UIExpBar

**Namespace:** `Torappu.UI`


## Fields

- `StretchProgressBar _currentBar`

- `StretchProgressBar _additionBar`

- `Text _currentExp`

- `Text _limitExp`

- `Text _level`


## Properties

- `String currentExp`

- `String limitExp`

- `String level`

- `Single currentProgress`

- `Single additionProgress`


## Methods

- `String get_currentExp()`

- `Void set_currentExp(String)`

- `String get_limitExp()`

- `Void set_limitExp(String)`

- `String get_level()`

- `Void set_level(String)`

- `Single get_currentProgress()`

- `Void set_currentProgress(Single)`

- `Single get_additionProgress()`

- `Void set_additionProgress(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIExpBar : MonoBehaviour
{
	private StretchProgressBar _currentBar; // 0x18
	private StretchProgressBar _additionBar; // 0x20
	private Text _currentExp; // 0x28
	private Text _limitExp; // 0x30
	private Text _level; // 0x38

	public String currentExp { get; set; }
	public String limitExp { get; set; }
	public String level { get; set; }
	public Single currentProgress { get; set; }
	public Single additionProgress { get; set; }

	// RVA: 0x2246970 VA: 0x759485e970
	public String get_currentExp() { }
	// RVA: 0x2246994 VA: 0x759485e994
	public Void set_currentExp(String value) { }
	// RVA: 0x22469b8 VA: 0x759485e9b8
	public String get_limitExp() { }
	// RVA: 0x22469dc VA: 0x759485e9dc
	public Void set_limitExp(String value) { }
	// RVA: 0x2246a00 VA: 0x759485ea00
	public String get_level() { }
	// RVA: 0x2246aa4 VA: 0x759485eaa4
	public Void set_level(String value) { }
	// RVA: 0x2246b44 VA: 0x759485eb44
	public Single get_currentProgress() { }
	// RVA: 0x2246bcc VA: 0x759485ebcc
	public Void set_currentProgress(Single value) { }
	// RVA: 0x2246c64 VA: 0x759485ec64
	public Single get_additionProgress() { }
	// RVA: 0x2246cec VA: 0x759485ecec
	public Void set_additionProgress(Single value) { }
	// RVA: 0x2246d84 VA: 0x759485ed84
	public Void .ctor() { }
}
```