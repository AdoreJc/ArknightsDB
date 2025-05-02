# UIFontSizeVerticalFitter

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _minFontSize`

- `Int32 _maxFontSize`

- `Text m_text`

- `RectTransform m_rectTransform`


## Properties

- `Int32 minFontSize`

- `Int32 maxFontSize`

- `Text text`

- `RectTransform rectTransform`


## Methods

- `Int32 get_minFontSize()`

- `Void set_minFontSize(Int32)`

- `Int32 get_maxFontSize()`

- `Void set_maxFontSize(Int32)`

- `Text get_text()`

- `RectTransform get_rectTransform()`

- `Void AutoFit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIFontSizeVerticalFitter : MonoBehaviour
{
	private Int32 _minFontSize; // 0x18
	private Int32 _maxFontSize; // 0x1c
	private Text m_text; // 0x20
	private RectTransform m_rectTransform; // 0x28

	public Int32 minFontSize { get; set; }
	public Int32 maxFontSize { get; set; }
	public Text text { get; }
	public RectTransform rectTransform { get; }

	// RVA: 0x21d4ebc VA: 0x75947ecebc
	public Int32 get_minFontSize() { }
	// RVA: 0x21d4ec4 VA: 0x75947ecec4
	public Void set_minFontSize(Int32 value) { }
	// RVA: 0x21d4ee4 VA: 0x75947ecee4
	public Int32 get_maxFontSize() { }
	// RVA: 0x21d4eec VA: 0x75947eceec
	public Void set_maxFontSize(Int32 value) { }
	// RVA: 0x21d4f0c VA: 0x75947ecf0c
	public Text get_text() { }
	// RVA: 0x21d4fb4 VA: 0x75947ecfb4
	public RectTransform get_rectTransform() { }
	// RVA: 0x21d505c VA: 0x75947ed05c
	public Void AutoFit() { }
	// RVA: 0x21d528c VA: 0x75947ed28c
	public Void .ctor() { }
}
```