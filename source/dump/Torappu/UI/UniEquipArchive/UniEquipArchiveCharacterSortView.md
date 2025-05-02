# UniEquipArchiveCharacterSortView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `TwoStateToggle _starMark`

- `SortItem _levelSort`

- `SortItem _raritySort`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void Render(UniEquipArchiveCharacterSortViewModel)`

- `Void _OnStarMarkToggle(State)`

- `Void _OnSortTypeClick(CharacterSortType)`

- `Void OnLevelDownClick()`

- `Void OnLevelUpClick()`

- `Void OnRarityDownClick()`

- `Void OnRarityUpClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveCharacterSortView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _starMark; // 0x18
	private SortItem _levelSort; // 0x20
	private SortItem _raritySort; // 0x28
	private Boolean m_isInited; // 0x30
	private UIStateFinder m_stateFinder; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__OnStarMarkToggle; // 0x10
	private static DelegateBridge __Hotfix0__OnSortTypeClick; // 0x18
	private static DelegateBridge __Hotfix0_OnLevelDownClick; // 0x20
	private static DelegateBridge __Hotfix0_OnLevelUpClick; // 0x28
	private static DelegateBridge __Hotfix0_OnRarityDownClick; // 0x30
	private static DelegateBridge __Hotfix0_OnRarityUpClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x22ebfec VA: 0x7594903fec
	private Void _InitIfNot() { }
	// RVA: 0x22ec178 VA: 0x7594904178
	public Void Render(UniEquipArchiveCharacterSortViewModel viewModel) { }
	// RVA: 0x22ec314 VA: 0x7594904314
	private Void _OnStarMarkToggle(State state) { }
	// RVA: 0x22ec428 VA: 0x7594904428
	private Void _OnSortTypeClick(CharacterSortType sortType) { }
	// RVA: 0x22ec534 VA: 0x7594904534
	public Void OnLevelDownClick() { }
	// RVA: 0x22ec5a0 VA: 0x75949045a0
	public Void OnLevelUpClick() { }
	// RVA: 0x22ec60c VA: 0x759490460c
	public Void OnRarityDownClick() { }
	// RVA: 0x22ec678 VA: 0x7594904678
	public Void OnRarityUpClick() { }
	// RVA: 0x22ec6e4 VA: 0x75949046e4
	public Void .ctor() { }
}
```