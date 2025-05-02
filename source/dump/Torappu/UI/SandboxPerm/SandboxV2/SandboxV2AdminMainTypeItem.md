# SandboxV2AdminMainTypeItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _normalTitle`

- `Text _selTitle`

- `Image _icon`

- `Image _selectedImage`

- `GameObject _hotspot`

- `Int32 m_idx`


## Properties

- `GameObject tutorialOnly_hotspotGO`


## Methods

- `Void add_eClick(Action`1)`

- `Void remove_eClick(Action`1)`

- `Void SetConfig(Color, Color)`

- `Void Render(Int32, SandboxV2AdminMainTypeItemData, Int32)`

- `Void EventOnClick()`

- `GameObject get_tutorialOnly_hotspotGO()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainTypeItem : MonoBehaviour, IHotfixable
{
	private Text _normalTitle; // 0x18
	private Text _selTitle; // 0x20
	private Image _icon; // 0x28
	private Image _selectedImage; // 0x30
	private GameObject _hotspot; // 0x38
	private Int32 m_idx; // 0x40
	private Action`1 eClick; // 0x48
	private static DelegateBridge __Hotfix0_add_eClick; // 0x0
	private static DelegateBridge __Hotfix0_remove_eClick; // 0x8
	private static DelegateBridge __Hotfix0_SetConfig; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x20
	private static DelegateBridge __Hotfix0_get_tutorialOnly_hotspotGO; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public GameObject tutorialOnly_hotspotGO { get; }

	// RVA: 0x24b6c94 VA: 0x7594acec94
	public Void add_eClick(Action`1 value) { }
	// RVA: 0x24b6d88 VA: 0x7594aced88
	public Void remove_eClick(Action`1 value) { }
	// RVA: 0x24b6e7c VA: 0x7594acee7c
	public Void SetConfig(Color selBgClr, Color selTitleClr) { }
	// RVA: 0x24b6fa0 VA: 0x7594acefa0
	public Void Render(Int32 idx, SandboxV2AdminMainTypeItemData data, Int32 selected) { }
	// RVA: 0x24b70c0 VA: 0x7594acf0c0
	public Void EventOnClick() { }
	// RVA: 0x24b7148 VA: 0x7594acf148
	public GameObject get_tutorialOnly_hotspotGO() { }
	// RVA: 0x24b71b0 VA: 0x7594acf1b0
	public Void .ctor() { }
}
```