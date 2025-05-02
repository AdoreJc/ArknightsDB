# CharacterLvlupHomeStateBean

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterIllustViewProperty illustProperty`

- `CharacterLvlupViewProperty lvlupViewProperty`

- `Int32 charInstId`

- `CharQuery m_charQuery`

- `Int32 m_cachedOriginLevel`


## Properties

- `String charId`

- `Int32 originLevel`


## Methods

- `String get_charId()`

- `Int32 get_originLevel()`

- `CharQuery GetCharQuery()`

- `Void LoadData(Param)`

- `Void TryModifyItemCount(Int32, Int32)`

- `Void _TryAddItem(CharacterLvlupViewModel, Int32, Int32)`

- `Void _TryReduceItem(CharacterLvlupViewModel, Int32, Int32)`

- `Void SwitchToScrollMode(Boolean)`

- `Int32 GetSelectedLevelPageIndex()`

- `Boolean CheckIfScrollMode()`

- `Void TryConfirmIndexOnScrollEnd(Int32)`

- `Void TryEnterScrollModeAndSelectIndex(Int32)`

- `Void SwitchToCardMode(Boolean)`

- `Void MoveToMaxValidLevel()`

- `Void ClearSelectedItems()`

- `Boolean IsRequiredGoldValid()`

- `Boolean IsSelectedExpValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupHomeStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public CharacterIllustViewProperty illustProperty; // 0x18
	public CharacterLvlupViewProperty lvlupViewProperty; // 0x20
	public Int32 charInstId; // 0x28
	private CharQuery m_charQuery; // 0x30
	private List`1 m_equipPairs; // 0x48
	private Int32 m_cachedOriginLevel; // 0x50
	private static DelegateBridge __Hotfix0_get_charId; // 0x0
	private static DelegateBridge __Hotfix0_get_originLevel; // 0x8
	private static DelegateBridge __Hotfix0_GetCharQuery; // 0x10
	private static DelegateBridge __Hotfix0_GetEquipQueries; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_TryModifyItemCount; // 0x28
	private static DelegateBridge __Hotfix0__TryAddItem; // 0x30
	private static DelegateBridge __Hotfix0__TryReduceItem; // 0x38
	private static DelegateBridge __Hotfix0_SwitchToScrollMode; // 0x40
	private static DelegateBridge __Hotfix0_GetSelectedLevelPageIndex; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfScrollMode; // 0x50
	private static DelegateBridge __Hotfix0_TryConfirmIndexOnScrollEnd; // 0x58
	private static DelegateBridge __Hotfix0_TryEnterScrollModeAndSelectIndex; // 0x60
	private static DelegateBridge __Hotfix0_SwitchToCardMode; // 0x68
	private static DelegateBridge __Hotfix0_MoveToMaxValidLevel; // 0x70
	private static DelegateBridge __Hotfix0_ClearSelectedItems; // 0x78
	private static DelegateBridge __Hotfix0_AchieveAllSelectedItems; // 0x80
	private static DelegateBridge __Hotfix0_IsRequiredGoldValid; // 0x88
	private static DelegateBridge __Hotfix0_IsSelectedExpValid; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public String charId { get; }
	public Int32 originLevel { get; }

	// RVA: 0x2d5ca38 VA: 0x7595374a38
	public String get_charId() { }
	// RVA: 0x2d5caa0 VA: 0x7595374aa0
	public Int32 get_originLevel() { }
	// RVA: 0x2d5cb08 VA: 0x7595374b08
	public CharQuery GetCharQuery() { }
	// RVA: 0x2d5cb98 VA: 0x7595374b98
	public List`1 GetEquipQueries() { }
	// RVA: 0x2d5cc00 VA: 0x7595374c00
	public Void LoadData(Param param) { }
	// RVA: 0x2d5d434 VA: 0x7595375434
	public Void TryModifyItemCount(Int32 itemIndex, Int32 deltaCount) { }
	// RVA: 0x2d5d5f4 VA: 0x75953755f4
	private Void _TryAddItem(CharacterLvlupViewModel viewModel, Int32 itemIndex, Int32 addCount) { }
	// RVA: 0x2d5d70c VA: 0x759537570c
	private Void _TryReduceItem(CharacterLvlupViewModel viewModel, Int32 itemIndex, Int32 reduceCount) { }
	// RVA: 0x2d5d984 VA: 0x7595375984
	public Void SwitchToScrollMode(Boolean isCounting) { }
	// RVA: 0x2d5dc88 VA: 0x7595375c88
	public Int32 GetSelectedLevelPageIndex() { }
	// RVA: 0x2d5dd8c VA: 0x7595375d8c
	public Boolean CheckIfScrollMode() { }
	// RVA: 0x2d5de1c VA: 0x7595375e1c
	public Void TryConfirmIndexOnScrollEnd(Int32 index) { }
	// RVA: 0x2d5e054 VA: 0x7595376054
	public Void TryEnterScrollModeAndSelectIndex(Int32 scrollIndex) { }
	// RVA: 0x2d5e13c VA: 0x759537613c
	public Void SwitchToCardMode(Boolean hasConfirmChange) { }
	// RVA: 0x2d5e348 VA: 0x7595376348
	public Void MoveToMaxValidLevel() { }
	// RVA: 0x2d5e5b8 VA: 0x75953765b8
	public Void ClearSelectedItems() { }
	// RVA: 0x2d5e6c0 VA: 0x75953766c0
	public List`1 AchieveAllSelectedItems() { }
	// RVA: 0x2d5e878 VA: 0x7595376878
	public Boolean IsRequiredGoldValid() { }
	// RVA: 0x2d5e9c8 VA: 0x75953769c8
	public Boolean IsSelectedExpValid() { }
	// RVA: 0x2d5eb7c VA: 0x7595376b7c
	public Void .ctor() { }
}
```