# HandBookGroupCharEdit

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `GameObject _isSelect`

- `Image _charHeadIcon`

- `Image _colorBack`

- `Boolean m_isSelected`

- `CharData cacheCharData`

- `ForceData cacheForceData`


## Properties

- `Single size`

- `Boolean isSelected`


## Methods

- `Void set_size(Single)`

- `Boolean get_isSelected()`

- `Void set_isSelected(Boolean)`

- `Void Render(CharData)`

- `Void SetSelect()`

- `Void LargeSize()`

- `Void LittleSize()`

- `Void RenderColor(String)`

- `Void NormalSize()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookGroupCharEdit : HandBookGroupCommonPosEdit
{
	private GameObject _isSelect; // 0x28
	private Image _charHeadIcon; // 0x30
	private Image _colorBack; // 0x38
	private Boolean m_isSelected; // 0x40
	public CharData cacheCharData; // 0x48
	public ForceData cacheForceData; // 0x50

	public Single size { set; }
	public Boolean isSelected { get; set; }

	// RVA: 0x2ec1014 VA: 0x75954d9014
	public Void set_size(Single value) { }
	// RVA: 0x2ec1094 VA: 0x75954d9094
	public Boolean get_isSelected() { }
	// RVA: 0x2ec109c VA: 0x75954d909c
	public Void set_isSelected(Boolean value) { }
	// RVA: 0x2ec11d0 VA: 0x75954d91d0
	public Void Render(CharData charData) { }
	// RVA: 0x2ec1298 VA: 0x75954d9298
	public Void SetSelect() { }
	// RVA: 0x2ec12b4 VA: 0x75954d92b4
	public Void LargeSize() { }
	// RVA: 0x2ec12e0 VA: 0x75954d92e0
	public Void LittleSize() { }
	// RVA: 0x2ec130c VA: 0x75954d930c
	public Void RenderColor(String color) { }
	// RVA: 0x2ec1390 VA: 0x75954d9390
	public Void NormalSize() { }
	// RVA: 0x2ec13b4 VA: 0x75954d93b4
	public override Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x2ec1624 VA: 0x75954d9624
	public override Void ApplyPos(Vector3 vect) { }
	// RVA: 0x2ec1640 VA: 0x75954d9640
	public Void .ctor() { }
}
```