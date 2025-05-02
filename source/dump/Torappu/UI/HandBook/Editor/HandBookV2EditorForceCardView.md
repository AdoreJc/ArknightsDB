# HandBookV2EditorForceCardView

**Namespace:** `Torappu.UI.HandBook.Editor`


## Fields

- `Text _textForceName`

- `Text _textForceCode`

- `Image _imgCollect`

- `Image _imgCharCount`

- `Text _textCharCount`

- `CanvasGroup _canvasGroup`

- `GameObject _selectGo`

- `HandBookV2ForceData m_forceData`

- `Vector2 m_startPos`


## Properties

- `String editCardColor`

- `Vector2 pos`

- `Single scale`


## Methods

- `String get_editCardColor()`

- `Void Render(HandBookV2ForceData)`

- `Void _UpdateColor()`

- `Void UpdateColor(Nullable`1, Nullable`1)`

- `Void _ClearColor()`

- `Void SetRaycast(Boolean)`

- `Void SetVisible(Boolean)`

- `Vector2 get_pos()`

- `Void set_pos(Vector2)`

- `Single get_scale()`

- `Void set_scale(Single)`

- `Void SetSelect(Boolean)`

- `Void OnBeginMove()`

- `Void OnMove(Vector2)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook.Editor
public class HandBookV2EditorForceCardView : MonoBehaviour
{
	private Text _textForceName; // 0x18
	private Text _textForceCode; // 0x20
	private Image _imgCollect; // 0x28
	private Image _imgCharCount; // 0x30
	private Text _textCharCount; // 0x38
	private CanvasGroup _canvasGroup; // 0x40
	private GameObject _selectGo; // 0x48
	private HandBookV2ForceData m_forceData; // 0x50
	private Nullable`1 m_editColor; // 0x58
	private Nullable`1 m_editCardColor; // 0x6c
	private Vector2 m_startPos; // 0x80

	public String editCardColor { get; }
	public Vector2 pos { get; set; }
	public Single scale { get; set; }

	// RVA: 0x2ee2974 VA: 0x75954fa974
	public String get_editCardColor() { }
	// RVA: 0x2ee2a08 VA: 0x75954faa08
	public Void Render(HandBookV2ForceData forceData) { }
	// RVA: 0x2ee2d34 VA: 0x75954fad34
	public Void _UpdateColor() { }
	// RVA: 0x2ee2e80 VA: 0x75954fae80
	public Void UpdateColor(Nullable`1 color, Nullable`1 cardColor) { }
	// RVA: 0x2ee2c20 VA: 0x75954fac20
	private Void _ClearColor() { }
	// RVA: 0x2ee2ea4 VA: 0x75954faea4
	public Void SetRaycast(Boolean canRaycast) { }
	// RVA: 0x2ee2ec4 VA: 0x75954faec4
	public Void SetVisible(Boolean isVisible) { }
	// RVA: 0x2ee2ef0 VA: 0x75954faef0
	public Vector2 get_pos() { }
	// RVA: 0x2ee2f10 VA: 0x75954faf10
	public Void set_pos(Vector2 value) { }
	// RVA: 0x2ee2f48 VA: 0x75954faf48
	public Single get_scale() { }
	// RVA: 0x2ee2f68 VA: 0x75954faf68
	public Void set_scale(Single value) { }
	// RVA: 0x2ee2fa0 VA: 0x75954fafa0
	public Void SetSelect(Boolean isSelect) { }
	// RVA: 0x2ee2fb0 VA: 0x75954fafb0
	public Void OnBeginMove() { }
	// RVA: 0x2ee31f0 VA: 0x75954fb1f0
	public Void OnMove(Vector2 delta) { }
	// RVA: 0x2ee334c VA: 0x75954fb34c
	public Void OnClick() { }
	// RVA: 0x2ee3470 VA: 0x75954fb470
	public Void .ctor() { }
}
```