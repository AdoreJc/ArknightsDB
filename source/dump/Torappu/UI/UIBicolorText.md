# UIBicolorText

**Namespace:** `Torappu.UI`


## Fields

- `Text _text`

- `Color _colorHilight`

- `Color _colorNormal`

- `Boolean m_isHilight`

- `Boolean m_isInited`


## Properties

- `Text text`

- `Boolean isHilight`


## Methods

- `Text get_text()`

- `Void _InitIfNot()`

- `Boolean get_isHilight()`

- `Void set_isHilight(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIBicolorText : MonoBehaviour
{
	private Text _text; // 0x18
	private Color _colorHilight; // 0x20
	private Color _colorNormal; // 0x30
	private Boolean m_isHilight; // 0x40
	private Boolean m_isInited; // 0x41

	public Text text { get; }
	public Boolean isHilight { get; set; }

	// RVA: 0x2241534 VA: 0x7594859534
	public Text get_text() { }
	// RVA: 0x224153c VA: 0x759485953c
	private Void _InitIfNot() { }
	// RVA: 0x22415bc VA: 0x75948595bc
	public Boolean get_isHilight() { }
	// RVA: 0x2241550 VA: 0x7594859550
	public Void set_isHilight(Boolean value) { }
	// RVA: 0x22415e4 VA: 0x75948595e4
	public Void .ctor() { }
}
```