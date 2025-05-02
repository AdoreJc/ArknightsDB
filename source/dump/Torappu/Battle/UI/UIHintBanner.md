# UIHintBanner

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _text`

- `Image _background`

- `Sequence m_textSequence`

- `Sequence m_backgroundSequence`

- `Color m_textColor`

- `Color m_backgroundColor`


## Methods

- `Void OnInit()`

- `Void OnShow(String, Single, Single, Single, Sprite)`

- `Void <OnShow>b__7_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIHintBanner : MonoBehaviour
{
	private Text _text; // 0x18
	private Image _background; // 0x20
	private Sequence m_textSequence; // 0x28
	private Sequence m_backgroundSequence; // 0x30
	private Color m_textColor; // 0x38
	private Color m_backgroundColor; // 0x48


	// RVA: 0x2041d30 VA: 0x7594659d30
	public Void OnInit() { }
	// RVA: 0x2041d84 VA: 0x7594659d84
	public Void OnShow(String text, Single fadeIn, Single fadeOut, Single duration, Sprite background) { }
	// RVA: 0x2042160 VA: 0x759465a160
	public Void .ctor() { }
	// RVA: 0x2042168 VA: 0x759465a168
	private Void <OnShow>b__7_0() { }
}
```