# SandboxV2CharStatusItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _topLineGo`

- `GameObject _selectBgGo`

- `Text _textStatus`

- `Color _colorSelect`

- `Color _colorUnselect`

- `SandboxV2CharFilter m_charStatus`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(Int32, SandboxV2CharFilter, Boolean)`

- `Void EventOnBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharStatusItemView : MonoBehaviour, IHotfixable
{
	private GameObject _topLineGo; // 0x18
	private GameObject _selectBgGo; // 0x20
	private Text _textStatus; // 0x28
	private Color _colorSelect; // 0x30
	private Color _colorUnselect; // 0x40
	private SandboxV2CharFilter m_charStatus; // 0x50
	private Action`1 <onItemClick>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBtnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClick { get; set; }

	// RVA: 0x260dd68 VA: 0x7594c25d68
	private Action`1 get_onItemClick() { }
	// RVA: 0x260ddd0 VA: 0x7594c25dd0
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x260de54 VA: 0x7594c25e54
	public Void Render(Int32 position, SandboxV2CharFilter charAvailStatus, Boolean isSelect) { }
	// RVA: 0x260dfb4 VA: 0x7594c25fb4
	public Void EventOnBtnClick() { }
	// RVA: 0x260e054 VA: 0x7594c26054
	public Void .ctor() { }
}
```