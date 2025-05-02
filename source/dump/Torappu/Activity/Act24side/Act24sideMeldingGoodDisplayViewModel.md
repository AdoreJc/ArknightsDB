# Act24sideMeldingGoodDisplayViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String <themeColor>k__BackingField`

- `MeldingGoodDisplayType <goodDisplayType>k__BackingField`


## Properties

- `String themeColor`

- `MeldingGoodDisplayType goodDisplayType`


## Methods

- `String get_themeColor()`

- `Void set_themeColor(String)`

- `MeldingGoodDisplayType get_goodDisplayType()`

- `Void set_goodDisplayType(MeldingGoodDisplayType)`

- `Boolean IsGachaDisplayTypeGoodAllTakeOut()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingGoodDisplayViewModel : IHotfixable
{
	private String <themeColor>k__BackingField; // 0x10
	private MeldingGoodDisplayType <goodDisplayType>k__BackingField; // 0x18
	public List`1 goodItemViewModelList; // 0x20
	private static DelegateBridge __Hotfix0_get_themeColor; // 0x0
	private static DelegateBridge __Hotfix0_set_themeColor; // 0x8
	private static DelegateBridge __Hotfix0_get_goodDisplayType; // 0x10
	private static DelegateBridge __Hotfix0_set_goodDisplayType; // 0x18
	private static DelegateBridge __Hotfix0_CreateDisplayViewModel; // 0x20
	private static DelegateBridge __Hotfix0_IsGachaDisplayTypeGoodAllTakeOut; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String themeColor { get; set; }
	public MeldingGoodDisplayType goodDisplayType { get; set; }

	// RVA: 0x32b1438 VA: 0x75958c9438
	public String get_themeColor() { }
	// RVA: 0x32b14a0 VA: 0x75958c94a0
	private Void set_themeColor(String value) { }
	// RVA: 0x32b1524 VA: 0x75958c9524
	public MeldingGoodDisplayType get_goodDisplayType() { }
	// RVA: 0x32b158c VA: 0x75958c958c
	private Void set_goodDisplayType(MeldingGoodDisplayType value) { }
	// RVA: 0x32b1608 VA: 0x75958c9608
	public static Act24sideMeldingGoodDisplayViewModel CreateDisplayViewModel(String theme, MeldingGoodDisplayType displayType) { }
	// RVA: 0x32b1774 VA: 0x75958c9774
	public Boolean IsGachaDisplayTypeGoodAllTakeOut() { }
	// RVA: 0x32b1704 VA: 0x75958c9704
	public Void .ctor() { }
}
```