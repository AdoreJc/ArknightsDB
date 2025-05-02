# ZoneHomeEntryGroupModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneHomeEntryItemModel themeEntry`

- `ActivityThemeData themeData`


## Methods

- `Void LoadData(StageStateBean)`

- `Void _UpdateViewIndex()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneHomeEntryGroupModel : IHotfixable
{
	public ZoneHomeEntryItemModel themeEntry; // 0x10
	public ActivityThemeData themeData; // 0x18
	public List`1 entryList; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__ExtractHomeThemeEntry; // 0x8
	private static DelegateBridge __Hotfix0__ExtractActivityThemeEntryImpl; // 0x10
	private static DelegateBridge __Hotfix0__ExtractMainlineEntryAsThemeImpl; // 0x18
	private static DelegateBridge __Hotfix0__UpdateViewIndex; // 0x20
	private static DelegateBridge __Hotfix0__CompareEntryItem; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2f08830 VA: 0x7595520830
	public Void LoadData(StageStateBean stateBean) { }
	// RVA: 0x2f08e9c VA: 0x7595520e9c
	private static Void _ExtractHomeThemeEntry(List`1 entryList, StageStateBean stateBean, out ZoneHomeEntryItemModel themeEntry, out ActivityThemeData themeData) { }
	// RVA: 0x2f09040 VA: 0x7595521040
	private static Boolean _ExtractActivityThemeEntryImpl(List`1 entryList, StageStateBean stateBean, out ZoneHomeEntryItemModel themeEntry, out ActivityThemeData themeData) { }
	// RVA: 0x2f092b4 VA: 0x75955212b4
	private static Boolean _ExtractMainlineEntryAsThemeImpl(List`1 entryList, StageStateBean stateBean, out ZoneHomeEntryItemModel themeEntry, out ActivityThemeData themeData) { }
	// RVA: 0x2f08f6c VA: 0x7595520f6c
	private Void _UpdateViewIndex() { }
	// RVA: 0x2f09568 VA: 0x7595521568
	private static Int32 _CompareEntryItem(ZoneHomeEntryItemModel lhs, ZoneHomeEntryItemModel rhs) { }
	// RVA: 0x2f0978c VA: 0x759552178c
	public Void .ctor() { }
}
```