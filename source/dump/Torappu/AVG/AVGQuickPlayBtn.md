# AVGQuickPlayBtn

**Namespace:** `Torappu.AVG`


## Fields

- `GameObject _selected`

- `AVGQuickPlay _quickPlayPanel`

- `Boolean m_isSelected`


## Properties

- `Boolean isSelected`


## Methods

- `Boolean get_isSelected()`

- `Void set_isSelected(Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGQuickPlayBtn : MonoBehaviour
{
	private GameObject _selected; // 0x18
	private AVGQuickPlay _quickPlayPanel; // 0x20
	private Boolean m_isSelected; // 0x28

	public Boolean isSelected { get; set; }

	// RVA: 0x3e7318c VA: 0x759648b18c
	public Boolean get_isSelected() { }
	// RVA: 0x3e72b6c VA: 0x759648ab6c
	public Void set_isSelected(Boolean value) { }
	// RVA: 0x3e73194 VA: 0x759648b194
	public Void OnClick() { }
	// RVA: 0x3e731c8 VA: 0x759648b1c8
	public Void .ctor() { }
}
```