# UniEquipArchiveFilterEquipItem

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `UniEquipArchiveFilterEquipState _equipState`

- `Text _text`

- `Color _selectedColor`

- `Color _unselectedColor`


## Properties

- `UniEquipArchiveFilterEquipState equipState`


## Methods

- `UniEquipArchiveFilterEquipState get_equipState()`

- `Void Render(Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveFilterEquipItem : MonoBehaviour, IHotfixable
{
	private UniEquipArchiveFilterEquipState _equipState; // 0x18
	private Text _text; // 0x20
	private Color _selectedColor; // 0x28
	private Color _unselectedColor; // 0x38
	public Action`1 onUnlockTabClick; // 0x48
	private static DelegateBridge __Hotfix0_get_equipState; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public UniEquipArchiveFilterEquipState equipState { get; }

	// RVA: 0x22e43a4 VA: 0x75948fc3a4
	public UniEquipArchiveFilterEquipState get_equipState() { }
	// RVA: 0x22e440c VA: 0x75948fc40c
	public Void Render(Boolean isSelected) { }
	// RVA: 0x22e44c4 VA: 0x75948fc4c4
	public Void OnClick() { }
	// RVA: 0x22e454c VA: 0x75948fc54c
	public Void .ctor() { }
}
```