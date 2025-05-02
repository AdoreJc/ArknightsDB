# HandBookGroupForceEdit

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `InputField _colorStr`

- `Text _forceId`

- `Image _forceColor`

- `TwoStateToggle _isThisGroupToggle`

- `UIStringEvent onClick`

- `UIStringEvent onFocusView`

- `UIStringEvent onSaveFocusView`

- `UIStringEvent onDeleteFocusView`

- `ForceData m_cacheForceData`


## Methods

- `Void Render(ForceData)`

- `Void OnColorEdit(String)`

- `Void OnClick()`

- `Void OnDelete()`

- `Void OnFocus()`

- `Void OnSaveFocus()`

- `Void OnAddColor()`

- `Void OnToggleClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookGroupForceEdit : MonoBehaviour
{
	private InputField _colorStr; // 0x18
	private Text _forceId; // 0x20
	private Image _forceColor; // 0x28
	private TwoStateToggle _isThisGroupToggle; // 0x30
	public UIStringEvent onClick; // 0x38
	public UIStringEvent onFocusView; // 0x40
	public UIStringEvent onSaveFocusView; // 0x48
	public UIStringEvent onDeleteFocusView; // 0x50
	private ForceData m_cacheForceData; // 0x58


	// RVA: 0x2ec4b38 VA: 0x75954dcb38
	public Void Render(ForceData forceData) { }
	// RVA: 0x2ec4c34 VA: 0x75954dcc34
	public Void OnColorEdit(String color) { }
	// RVA: 0x2ec4cac VA: 0x75954dccac
	public Void OnClick() { }
	// RVA: 0x2ec4d0c VA: 0x75954dcd0c
	public Void OnDelete() { }
	// RVA: 0x2ec4d6c VA: 0x75954dcd6c
	public Void OnFocus() { }
	// RVA: 0x2ec4dcc VA: 0x75954dcdcc
	public Void OnSaveFocus() { }
	// RVA: 0x2ec4e2c VA: 0x75954dce2c
	public Void OnAddColor() { }
	// RVA: 0x2ec4e8c VA: 0x75954dce8c
	public Void OnToggleClick() { }
	// RVA: 0x2ec4ebc VA: 0x75954dcebc
	public Void .ctor() { }
}
```