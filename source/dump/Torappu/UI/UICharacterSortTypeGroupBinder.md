# UICharacterSortTypeGroupBinder

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _groupHolder`

- `UICharacterSortTypeGroup _sortGroupPrefab`

- `UnityEvent _eventBtnFilterClick`

- `CharacterSortTypeMessage _eventSortTypeChange`

- `Boolean m_isInited`

- `UICharacterSortTypeGroup m_sortTypeGroup`


## Methods

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__7_0()`

- `Void <_InitIfNot>b__7_1(CharacterSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortTypeGroupBinder : DataBinder`1, IHotfixable
{
	private RectTransform _groupHolder; // 0x20
	private UICharacterSortTypeGroup _sortGroupPrefab; // 0x28
	private UnityEvent _eventBtnFilterClick; // 0x30
	private CharacterSortTypeMessage _eventSortTypeChange; // 0x38
	private Nullable`1 m_dataCache; // 0x40
	private Boolean m_isInited; // 0x48
	private UICharacterSortTypeGroup m_sortTypeGroup; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2135310 VA: 0x759474d310
	private Void _InitIfNot() { }
	// RVA: 0x2135514 VA: 0x759474d514
	public override Void OnValueChanged(CharacterCardSortTypeViewProperty property) { }
	// RVA: 0x2135648 VA: 0x759474d648
	public Void .ctor() { }
	// RVA: 0x21356d8 VA: 0x759474d6d8
	private Void <_InitIfNot>b__7_0() { }
	// RVA: 0x21356ec VA: 0x759474d6ec
	private Void <_InitIfNot>b__7_1(CharacterSortType sortType) { }
}
```