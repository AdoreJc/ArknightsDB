# SquadTabView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `TwoStateToggle _toggle`

- `Text _name`

- `Text _nameUnselected`

- `TabClickEvent _onTabClick`

- `TabClickEvent _onRenameClick`

- `Int32 m_indexCache`


## Methods

- `Void Render(Int32, String, Boolean)`

- `Void EventOnTabClick()`

- `Void EventOnReNameClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadTabView : MonoBehaviour
{
	private TwoStateToggle _toggle; // 0x18
	private Text _name; // 0x20
	private Text _nameUnselected; // 0x28
	private TabClickEvent _onTabClick; // 0x30
	private TabClickEvent _onRenameClick; // 0x38
	private Int32 m_indexCache; // 0x40


	// RVA: 0x23cb41c VA: 0x75949e341c
	public Void Render(Int32 index, String name, Boolean isSelected) { }
	// RVA: 0x23cdd60 VA: 0x75949e5d60
	public Void EventOnTabClick() { }
	// RVA: 0x23cddbc VA: 0x75949e5dbc
	public Void EventOnReNameClick() { }
	// RVA: 0x23cde24 VA: 0x75949e5e24
	public Void .ctor() { }
}
```