# UICharacterTabGroup

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Transform _root`

- `RectTransform _rectRoot`

- `Transform _infoTabRoot`

- `Transform _infoTabDetailPanelRoot`


## Properties

- `Transform infoTabRoot`

- `Transform infoTabDetailPanelRoot`


## Methods

- `Transform get_infoTabRoot()`

- `Transform get_infoTabDetailPanelRoot()`

- `Void Reset()`

- `Void EnableTabInfomation(Int32)`

- `Void ShowTabInfomation(Int32)`

- `Void _OnTabClickedToShow(UICharacterTabSwitchButton)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterTabGroup : MonoBehaviour, IHotfixable
{
	private Transform _root; // 0x18
	private RectTransform _rectRoot; // 0x20
	private Transform _infoTabRoot; // 0x28
	private Transform _infoTabDetailPanelRoot; // 0x30
	private List`1 _widthWhenShow; // 0x38
	private List`1 m_tabButtons; // 0x40
	private static DelegateBridge __Hotfix0_get_infoTabRoot; // 0x0
	private static DelegateBridge __Hotfix0_get_infoTabDetailPanelRoot; // 0x8
	private static DelegateBridge __Hotfix0_get_tabButtons; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0_EnableTabInfomation; // 0x20
	private static DelegateBridge __Hotfix0_ShowTabInfomation; // 0x28
	private static DelegateBridge __Hotfix0__OnTabClickedToShow; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Transform infoTabRoot { get; }
	public Transform infoTabDetailPanelRoot { get; }
	private List`1 tabButtons { get; }

	// RVA: 0x203a924 VA: 0x7594652924
	public Transform get_infoTabRoot() { }
	// RVA: 0x203a98c VA: 0x759465298c
	public Transform get_infoTabDetailPanelRoot() { }
	// RVA: 0x203a9f4 VA: 0x75946529f4
	private List`1 get_tabButtons() { }
	// RVA: 0x20388a8 VA: 0x75946508a8
	public Void Reset() { }
	// RVA: 0x2039830 VA: 0x7594651830
	public Void EnableTabInfomation(Int32 mask) { }
	// RVA: 0x203ad58 VA: 0x7594652d58
	public Void ShowTabInfomation(Int32 mask) { }
	// RVA: 0x203ae88 VA: 0x7594652e88
	private Void _OnTabClickedToShow(UICharacterTabSwitchButton button) { }
	// RVA: 0x203af64 VA: 0x7594652f64
	public Void .ctor() { }
}
```