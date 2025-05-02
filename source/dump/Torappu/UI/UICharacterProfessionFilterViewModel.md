# UICharacterProfessionFilterViewModel

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_isAll`

- `ProfessionCategory m_selectedProf`

- `String m_selectedSubProf`

- `Boolean showProf`

- `Boolean showSubProf`

- `Int32 fastSeq`


## Properties

- `Boolean isAll`

- `ProfessionCategory selectedProf`

- `String selectedSubProf`


## Methods

- `Boolean get_isAll()`

- `ProfessionCategory get_selectedProf()`

- `String get_selectedSubProf()`

- `Void InitData()`

- `Void _LoadProfessionData()`

- `Void _LoadSubProfessionData()`

- `Void UpdateInvalidSubProf()`

- `Int32 LoadSelectedProfItem(out)`

- `ProfessionFilterSubProfItemViewModel GetSelectedSubProfItem()`

- `Boolean SetProfession(Boolean, ProfessionCategory, String)`

- `Int32 _LoadProfItemOrNull(ProfessionCategory, out)`

- `Boolean _IsValidProfParam(ProfessionCategory, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterProfessionFilterViewModel : IHotfixable
{
	private ListDict`2 m_profItems; // 0x10
	private Boolean m_isAll; // 0x18
	private ProfessionCategory m_selectedProf; // 0x1c
	private String m_selectedSubProf; // 0x20
	public Boolean showProf; // 0x28
	public Boolean showSubProf; // 0x29
	public Int32 fastSeq; // 0x2c
	public HashSet`1 invalidSubProfs; // 0x30
	private static readonly List`1 s_PROFESSION_ORDER_LIST; // 0x0
	private static DelegateBridge __Hotfix0_get_profItems; // 0x8
	private static DelegateBridge __Hotfix0_get_isAll; // 0x10
	private static DelegateBridge __Hotfix0_get_selectedProf; // 0x18
	private static DelegateBridge __Hotfix0_get_selectedSubProf; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x28
	private static DelegateBridge __Hotfix0__LoadProfessionData; // 0x30
	private static DelegateBridge __Hotfix0__LoadSubProfessionData; // 0x38
	private static DelegateBridge __Hotfix0_UpdateInvalidSubProf; // 0x40
	private static DelegateBridge __Hotfix0_IsProfessionValid; // 0x48
	private static DelegateBridge __Hotfix0_LoadSelectedProfItem; // 0x50
	private static DelegateBridge __Hotfix0_GetSelectedSubProfItem; // 0x58
	private static DelegateBridge __Hotfix0_SetProfession; // 0x60
	private static DelegateBridge __Hotfix0__LoadProfItemOrNull; // 0x68
	private static DelegateBridge __Hotfix0__IsValidProfParam; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public ListDict`2 profItems { get; }
	public Boolean isAll { get; }
	public ProfessionCategory selectedProf { get; }
	public String selectedSubProf { get; }

	// RVA: 0x2125ef4 VA: 0x759473def4
	public ListDict`2 get_profItems() { }
	// RVA: 0x2124590 VA: 0x759473c590
	public Boolean get_isAll() { }
	// RVA: 0x2124608 VA: 0x759473c608
	public ProfessionCategory get_selectedProf() { }
	// RVA: 0x2124680 VA: 0x759473c680
	public String get_selectedSubProf() { }
	// RVA: 0x2124350 VA: 0x759473c350
	public Void InitData() { }
	// RVA: 0x21279f8 VA: 0x759473f9f8
	private Void _LoadProfessionData() { }
	// RVA: 0x2127c30 VA: 0x759473fc30
	private Void _LoadSubProfessionData() { }
	// RVA: 0x2123ef4 VA: 0x759473bef4
	public Void UpdateInvalidSubProf() { }
	// RVA: 0x2124e48 VA: 0x759473ce48
	public static Boolean IsProfessionValid(ProfessionCategory prof) { }
	// RVA: 0x2125a38 VA: 0x759473da38
	public Int32 LoadSelectedProfItem(out ProfessionFilterProfItemViewModel itemModel) { }
	// RVA: 0x212761c VA: 0x759473f61c
	public ProfessionFilterSubProfItemViewModel GetSelectedSubProfItem() { }
	// RVA: 0x21249fc VA: 0x759473c9fc
	public Boolean SetProfession(Boolean isAll, ProfessionCategory prof, String subProfId) { }
	// RVA: 0x2128120 VA: 0x7594740120
	private Int32 _LoadProfItemOrNull(ProfessionCategory prof, out ProfessionFilterProfItemViewModel itemModel) { }
	// RVA: 0x2128268 VA: 0x7594740268
	private Boolean _IsValidProfParam(ProfessionCategory prof, String subProfId) { }
	// RVA: 0x21283b0 VA: 0x75947403b0
	public Void .ctor() { }
	// RVA: 0x21284d4 VA: 0x75947404d4
	private static Void .cctor() { }
}
```