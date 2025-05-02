# BuildConfigCostViewModel

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Single m_goldReductRate`

- `UIItemViewModel <goldModel>k__BackingField`

- `UIItemViewModel <recruitLicenseModel>k__BackingField`

- `String <specialTagName>k__BackingField`

- `Boolean <isSpecialViewModel>k__BackingField`


## Properties

- `UIItemViewModel goldModel`

- `UIItemViewModel recruitLicenseModel`

- `String specialTagName`

- `Boolean isSpecialViewModel`


## Methods

- `UIItemViewModel get_goldModel()`

- `Void set_goldModel(UIItemViewModel)`

- `UIItemViewModel get_recruitLicenseModel()`

- `Void set_recruitLicenseModel(UIItemViewModel)`

- `Void set_specialItemViewlModel(List`1)`

- `String get_specialTagName()`

- `Void set_specialTagName(String)`

- `Boolean get_isSpecialViewModel()`

- `Void set_isSpecialViewModel(Boolean)`

- `Void _InitIfNot()`

- `Void UpdateData(Int64, Int32, Boolean, SpecialRecruitPool)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class BuildConfigCostViewModel
{
	private Single m_goldReductRate; // 0x10
	private UIItemViewModel <goldModel>k__BackingField; // 0x18
	private UIItemViewModel <recruitLicenseModel>k__BackingField; // 0x20
	private List`1 <specialItemViewlModel>k__BackingField; // 0x28
	private String <specialTagName>k__BackingField; // 0x30
	private Boolean <isSpecialViewModel>k__BackingField; // 0x38

	public UIItemViewModel goldModel { get; set; }
	public UIItemViewModel recruitLicenseModel { get; set; }
	public List`1 specialItemViewlModel { get; set; }
	public String specialTagName { get; set; }
	public Boolean isSpecialViewModel { get; set; }

	// RVA: 0x26fce98 VA: 0x7594d14e98
	public UIItemViewModel get_goldModel() { }
	// RVA: 0x26fcea0 VA: 0x7594d14ea0
	protected Void set_goldModel(UIItemViewModel value) { }
	// RVA: 0x26fcea8 VA: 0x7594d14ea8
	public UIItemViewModel get_recruitLicenseModel() { }
	// RVA: 0x26fceb0 VA: 0x7594d14eb0
	protected Void set_recruitLicenseModel(UIItemViewModel value) { }
	// RVA: 0x26fceb8 VA: 0x7594d14eb8
	public List`1 get_specialItemViewlModel() { }
	// RVA: 0x26fcec0 VA: 0x7594d14ec0
	protected Void set_specialItemViewlModel(List`1 value) { }
	// RVA: 0x26fcec8 VA: 0x7594d14ec8
	public String get_specialTagName() { }
	// RVA: 0x26fced0 VA: 0x7594d14ed0
	protected Void set_specialTagName(String value) { }
	// RVA: 0x26fced8 VA: 0x7594d14ed8
	public Boolean get_isSpecialViewModel() { }
	// RVA: 0x26fcee0 VA: 0x7594d14ee0
	protected Void set_isSpecialViewModel(Boolean value) { }
	// RVA: 0x26fceec VA: 0x7594d14eec
	private Void _InitIfNot() { }
	// RVA: 0x26fc87c VA: 0x7594d1487c
	public Void UpdateData(Int64 costMillsec, Int32 tagNum, Boolean specialTagState, SpecialRecruitPool specialTagData) { }
	// RVA: 0x26fcdc0 VA: 0x7594d14dc0
	public Void .ctor() { }
}
```