# SetDateItemView

**Namespace:** `Torappu.UI`


## Fields

- `Color _selectColor`

- `Color _unselectColor`

- `Text _showText`

- `Int32 m_pageIndex`


## Methods

- `Void Render(Param, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class SetDateItemView : MonoBehaviour, IHotfixable
{
	private Color _selectColor; // 0x18
	private Color _unselectColor; // 0x28
	private Text _showText; // 0x38
	private Int32 m_pageIndex; // 0x40
	private Action`1 m_onItemClicked; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x223cda8 VA: 0x7594854da8
	public Void Render(Param param, Boolean selected) { }
	// RVA: 0x223cedc VA: 0x7594854edc
	public Void EventOnClicked() { }
	// RVA: 0x223cf64 VA: 0x7594854f64
	public Void .ctor() { }
}
```