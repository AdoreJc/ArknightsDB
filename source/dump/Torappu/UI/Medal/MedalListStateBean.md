# MedalListStateBean

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalListViewModel listViewModel`

- `Int32 maxSelectCount`

- `Int32 <lastSelectCount>k__BackingField`

- `Boolean <isSelectionConfirmed>k__BackingField`

- `Int32 m_cachedSelectCount`

- `Boolean m_isInited`


## Properties

- `Int32 lastSelectCount`

- `Boolean isSelectionConfirmed`


## Methods

- `Int32 get_lastSelectCount()`

- `Void set_lastSelectCount(Int32)`

- `Boolean get_isSelectionConfirmed()`

- `Void set_isSelectionConfirmed(Boolean)`

- `Void RefreshData()`

- `Int32 GetTotalMedal()`

- `Int32 GetAvailMedal()`

- `Void InitData(Boolean)`

- `Void ToggleSelection(MedalCommonViewModel)`

- `Void SetSelectMedalInput(ICollection`1, Int32)`

- `Void ClearAllSelection()`

- `Void ConfirmSelection()`

- `Void LoadSelectedMedals(ICollection`1)`

- `Int32 _CountSelectedMedalsInUsedAndRestrict()`

- `Void _CountAndRestrictSelectionHandler(MedalCommonViewModel)`

- `Void _SetSelectionHandler(MedalCommonViewModel)`

- `Void _LoadSelectionHanlder(MedalCommonViewModel)`

- `Void _ForeachMedalInUsed(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public MedalListViewModel listViewModel; // 0x18
	public Int32 maxSelectCount; // 0x20
	private Int32 <lastSelectCount>k__BackingField; // 0x24
	private Boolean <isSelectionConfirmed>k__BackingField; // 0x28
	private HashSet`1 m_sharedSet; // 0x30
	private Int32 m_cachedSelectCount; // 0x38
	private Boolean m_isInited; // 0x3c
	private static DelegateBridge __Hotfix0_get_lastSelectCount; // 0x0
	private static DelegateBridge __Hotfix0_set_lastSelectCount; // 0x8
	private static DelegateBridge __Hotfix0_get_isSelectionConfirmed; // 0x10
	private static DelegateBridge __Hotfix0_set_isSelectionConfirmed; // 0x18
	private static DelegateBridge __Hotfix0_get_typeViewModelInUsed; // 0x20
	private static DelegateBridge __Hotfix0_RefreshData; // 0x28
	private static DelegateBridge __Hotfix0_GetTotalMedal; // 0x30
	private static DelegateBridge __Hotfix0_GetAvailMedal; // 0x38
	private static DelegateBridge __Hotfix0_InitData; // 0x40
	private static DelegateBridge __Hotfix0_ToggleSelection; // 0x48
	private static DelegateBridge __Hotfix0_SetSelectMedalInput; // 0x50
	private static DelegateBridge __Hotfix0_ClearAllSelection; // 0x58
	private static DelegateBridge __Hotfix0_ConfirmSelection; // 0x60
	private static DelegateBridge __Hotfix0_LoadSelectedMedals; // 0x68
	private static DelegateBridge __Hotfix0__CountSelectedMedalsInUsedAndRestrict; // 0x70
	private static DelegateBridge __Hotfix0__CountAndRestrictSelectionHandler; // 0x78
	private static DelegateBridge __Hotfix0__SetSelectionHandler; // 0x80
	private static DelegateBridge __Hotfix0__LoadSelectionHanlder; // 0x88
	private static DelegateBridge __Hotfix0__ForeachMedalInUsed; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public Int32 lastSelectCount { get; set; }
	public Boolean isSelectionConfirmed { get; set; }
	public List`1 typeViewModelInUsed { get; }

	// RVA: 0x27ae2d4 VA: 0x7594dc62d4
	public Int32 get_lastSelectCount() { }
	// RVA: 0x27ae33c VA: 0x7594dc633c
	private Void set_lastSelectCount(Int32 value) { }
	// RVA: 0x27ae3b8 VA: 0x7594dc63b8
	public Boolean get_isSelectionConfirmed() { }
	// RVA: 0x27ae420 VA: 0x7594dc6420
	private Void set_isSelectionConfirmed(Boolean value) { }
	// RVA: 0x27ae4a0 VA: 0x7594dc64a0
	public List`1 get_typeViewModelInUsed() { }
	// RVA: 0x27ae504 VA: 0x7594dc6504
	public Void RefreshData() { }
	// RVA: 0x27ae574 VA: 0x7594dc6574
	public Int32 GetTotalMedal() { }
	// RVA: 0x27ae5e4 VA: 0x7594dc65e4
	public Int32 GetAvailMedal() { }
	// RVA: 0x27ae654 VA: 0x7594dc6654
	public Void InitData(Boolean abortNotGetMedals) { }
	// RVA: 0x27ae700 VA: 0x7594dc6700
	public Void ToggleSelection(MedalCommonViewModel viewModel) { }
	// RVA: 0x27ae8b0 VA: 0x7594dc68b0
	public Void SetSelectMedalInput(ICollection`1 selectedIds, Int32 maxSelectCount) { }
	// RVA: 0x27aed30 VA: 0x7594dc6d30
	public Void ClearAllSelection() { }
	// RVA: 0x27aee64 VA: 0x7594dc6e64
	public Void ConfirmSelection() { }
	// RVA: 0x27aeed0 VA: 0x7594dc6ed0
	public Void LoadSelectedMedals(ICollection`1 selectResult) { }
	// RVA: 0x27ae7ec VA: 0x7594dc67ec
	private Int32 _CountSelectedMedalsInUsedAndRestrict() { }
	// RVA: 0x27af11c VA: 0x7594dc711c
	private Void _CountAndRestrictSelectionHandler(MedalCommonViewModel medalModel) { }
	// RVA: 0x27af1c4 VA: 0x7594dc71c4
	private Void _SetSelectionHandler(MedalCommonViewModel medalModel) { }
	// RVA: 0x27af2c4 VA: 0x7594dc72c4
	private Void _LoadSelectionHanlder(MedalCommonViewModel medalModel) { }
	// RVA: 0x27aeba4 VA: 0x7594dc6ba4
	private Void _ForeachMedalInUsed(Action`1 handler) { }
	// RVA: 0x27af3d0 VA: 0x7594dc73d0
	public Void .ctor() { }
}
```