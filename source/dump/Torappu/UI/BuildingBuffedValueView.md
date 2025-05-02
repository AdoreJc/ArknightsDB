# BuildingBuffedValueView

**Namespace:** `Torappu.UI`


## Fields

- `Image _imgBkg`

- `Text _text`


## Properties

- `Color bkgColor`

- `Color textColor`


## Methods

- `Void set_bkgColor(Color)`

- `Void set_textColor(Color)`

- `Void Render(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class BuildingBuffedValueView : MonoBehaviour
{
	private Image _imgBkg; // 0x18
	private Text _text; // 0x20

	public Color bkgColor { set; }
	public Color textColor { set; }

	// RVA: 0x2103be8 VA: 0x759471bbe8
	public Void set_bkgColor(Color value) { }
	// RVA: 0x2103c0c VA: 0x759471bc0c
	public Void set_textColor(Color value) { }
	// RVA: 0x2103c30 VA: 0x759471bc30
	public Void Render(String text) { }
	// RVA: 0x2103c54 VA: 0x759471bc54
	public Void .ctor() { }
}
```