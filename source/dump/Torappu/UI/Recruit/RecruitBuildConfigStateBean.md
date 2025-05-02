# RecruitBuildConfigStateBean

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `BuildConfigTagGroupViewProperty _tagGroupProperty`

- `BuildConfigTimeViewProperty _timeProperty`

- `BuildConfigCostViewProperty _costProperty`

- `BuildConfigRarityProperty _rarityProperty`

- `Boolean isConfirmed`

- `Int32 <editingSlotIndex>k__BackingField`


## Properties

- `Int32 editingSlotIndex`


## Methods

- `Int32 get_editingSlotIndex()`

- `Void set_editingSlotIndex(Int32)`

- `Void SetData(Int32)`

- `Void ModifyTime(Int64)`

- `Void TryToggleTag(Int32)`

- `NormalGachaRequest ParseNormalGachaRequest()`

- `String CheckResourceToBuild()`

- `Boolean HasSpecialTag()`

- `Boolean CheckNeedSpecialTagWarning(out)`

- `Void _UpdateCost()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildConfigStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private const Int64 MAX_BUILD_TIME; // 0x0
	private const Int64 DEFAULT_BUILD_TIME; // 0x0
	public const Int64 MIN_BUILD_TIME; // 0x0
	private const Int32 MAX_TAG_SELECT_NUM; // 0x0
	private BuildConfigTagGroupViewProperty _tagGroupProperty; // 0x18
	private BuildConfigTimeViewProperty _timeProperty; // 0x20
	private BuildConfigCostViewProperty _costProperty; // 0x28
	private BuildConfigRarityProperty _rarityProperty; // 0x30
	public Boolean isConfirmed; // 0x38
	private Int32 <editingSlotIndex>k__BackingField; // 0x3c
	private static DelegateBridge __Hotfix0_get_editingSlotIndex; // 0x0
	private static DelegateBridge __Hotfix0_set_editingSlotIndex; // 0x8
	private static DelegateBridge __Hotfix0_SetData; // 0x10
	private static DelegateBridge __Hotfix0_ModifyTime; // 0x18
	private static DelegateBridge __Hotfix0_TryToggleTag; // 0x20
	private static DelegateBridge __Hotfix0_ParseNormalGachaRequest; // 0x28
	private static DelegateBridge __Hotfix0_CheckResourceToBuild; // 0x30
	private static DelegateBridge __Hotfix0_HasSpecialTag; // 0x38
	private static DelegateBridge __Hotfix0_CheckNeedSpecialTagWarning; // 0x40
	private static DelegateBridge __Hotfix0__UpdateCost; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 editingSlotIndex { get; set; }

	// RVA: 0x26f568c VA: 0x7594d0d68c
	public Int32 get_editingSlotIndex() { }
	// RVA: 0x26fdbf0 VA: 0x7594d15bf0
	private Void set_editingSlotIndex(Int32 value) { }
	// RVA: 0x26f57ec VA: 0x7594d0d7ec
	public Void SetData(Int32 slotIndex) { }
	// RVA: 0x26f3be4 VA: 0x7594d0bbe4
	public Void ModifyTime(Int64 deltaTime) { }
	// RVA: 0x26f4e48 VA: 0x7594d0ce48
	public Void TryToggleTag(Int32 tagIndex) { }
	// RVA: 0x26f5178 VA: 0x7594d0d178
	public NormalGachaRequest ParseNormalGachaRequest() { }
	// RVA: 0x26f4154 VA: 0x7594d0c154
	public String CheckResourceToBuild() { }
	// RVA: 0x26f4b3c VA: 0x7594d0cb3c
	public Boolean HasSpecialTag() { }
	// RVA: 0x26f4498 VA: 0x7594d0c498
	public Boolean CheckNeedSpecialTagWarning(out String warningText) { }
	// RVA: 0x26fdc6c VA: 0x7594d15c6c
	private Void _UpdateCost() { }
	// RVA: 0x26fdf58 VA: 0x7594d15f58
	public Void .ctor() { }
}
```