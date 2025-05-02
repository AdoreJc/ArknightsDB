# SandboxV2AdminMainScienceTypeSelectItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _icon`

- `GameObject _selected`

- `Slider _progress`

- `Slider _selectedProgress`

- `GameObject _normalPart`

- `GameObject _lockPart`

- `GameObject _splitPart`

- `Button _btn`

- `Int32 m_idx`

- `Boolean m_isLocked`


## Methods

- `Void add_eClick(Action`1)`

- `Void remove_eClick(Action`1)`

- `Void Render(Int32, SandboxV2AdminMainScienceTypeItemData, Int32)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainScienceTypeSelectItem : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private GameObject _selected; // 0x20
	private Slider _progress; // 0x28
	private Slider _selectedProgress; // 0x30
	private GameObject _normalPart; // 0x38
	private GameObject _lockPart; // 0x40
	private GameObject _splitPart; // 0x48
	private Button _btn; // 0x50
	private Int32 m_idx; // 0x58
	private Boolean m_isLocked; // 0x5c
	private Action`1 eClick; // 0x60
	private static DelegateBridge __Hotfix0_add_eClick; // 0x0
	private static DelegateBridge __Hotfix0_remove_eClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x24e6320 VA: 0x7594afe320
	public Void add_eClick(Action`1 value) { }
	// RVA: 0x24e6414 VA: 0x7594afe414
	public Void remove_eClick(Action`1 value) { }
	// RVA: 0x24e6508 VA: 0x7594afe508
	public Void Render(Int32 idx, SandboxV2AdminMainScienceTypeItemData data, Int32 selected) { }
	// RVA: 0x24e66c0 VA: 0x7594afe6c0
	public Void EventOnClick() { }
	// RVA: 0x24e6750 VA: 0x7594afe750
	public Void .ctor() { }
}
```