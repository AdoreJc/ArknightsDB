# HandBookV2EditorLineListItemView

**Namespace:** `Torappu.UI.HandBook.Editor`


## Fields

- `Image _imgSelected`

- `Text _textLine`

- `Int32 m_index`


## Methods

- `Void set_onClick(Action`1)`

- `Void ApplyData(Int32, String)`

- `Void OnItemClick()`

- `Void SetSelect(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook.Editor
public class HandBookV2EditorLineListItemView : MonoBehaviour
{
	private Image _imgSelected; // 0x18
	private Text _textLine; // 0x20
	private Action`1 <onClick>k__BackingField; // 0x28
	private Int32 m_index; // 0x30

	private Action`1 onClick { get; set; }

	// RVA: 0x2ee423c VA: 0x75954fc23c
	private Action`1 get_onClick() { }
	// RVA: 0x2ee4244 VA: 0x75954fc244
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2ee424c VA: 0x75954fc24c
	public Void ApplyData(Int32 index, String displayStr) { }
	// RVA: 0x2ee4280 VA: 0x75954fc280
	public Void OnItemClick() { }
	// RVA: 0x2ee42a0 VA: 0x75954fc2a0
	public Void SetSelect(Boolean isSelect) { }
	// RVA: 0x2ee42cc VA: 0x75954fc2cc
	public Void .ctor() { }
}
```