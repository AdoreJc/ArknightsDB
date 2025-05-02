# SandboxV2SquadTabItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasImage _imgBg`

- `Text _textSquadIdx`

- `Color _colorBgUnselect`

- `Color _colorBgSelect`

- `Color _colorTextUnselect`

- `Color _colorTextSelect`

- `GameObject _btnGo`

- `Int32 m_index`


## Properties

- `GameObject btnGo`


## Methods

- `GameObject get_btnGo()`

- `Void set_onItemClick(Action`1)`

- `Void Render(Int32, Boolean)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadTabItemView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imgBg; // 0x18
	private Text _textSquadIdx; // 0x20
	private Color _colorBgUnselect; // 0x28
	private Color _colorBgSelect; // 0x38
	private Color _colorTextUnselect; // 0x48
	private Color _colorTextSelect; // 0x58
	private GameObject _btnGo; // 0x68
	private Action`1 <onItemClick>k__BackingField; // 0x70
	private Int32 m_index; // 0x78
	private static DelegateBridge __Hotfix0_get_btnGo; // 0x0
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public GameObject btnGo { get; }
	private Action`1 onItemClick { get; set; }

	// RVA: 0x260f184 VA: 0x7594c27184
	public GameObject get_btnGo() { }
	// RVA: 0x261c238 VA: 0x7594c34238
	private Action`1 get_onItemClick() { }
	// RVA: 0x260edfc VA: 0x7594c26dfc
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x260ee80 VA: 0x7594c26e80
	public Void Render(Int32 index, Boolean isSelect) { }
	// RVA: 0x261c2a0 VA: 0x7594c342a0
	public Void EventOnItemClick() { }
	// RVA: 0x261c340 VA: 0x7594c34340
	public Void .ctor() { }
}
```