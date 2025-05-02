# BuildingToDoNotifyItemModel

**Namespace:** `Torappu`


## Fields

- `String desc`

- `Int32 count`

- `String clickDesc`

- `Boolean canPlayClickAnim`

- `Boolean isHide`

- `Boolean needPlayClickAnim`

- `Boolean forceHideCount`

- `Int32 <sortPriority>k__BackingField`

- `BuildingToDoType m_type`


## Properties

- `BuildingToDoType type`

- `Int32 sortPriority`

- `Boolean available`


## Methods

- `BuildingToDoType get_type()`

- `Void set_type(BuildingToDoType)`

- `Int32 get_sortPriority()`

- `Void set_sortPriority(Int32)`

- `Boolean get_available()`

- `Int32 GetCount4Display()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuildingToDoNotifyItemModel : IHotfixable
{
	public String desc; // 0x10
	public Int32 count; // 0x18
	public String clickDesc; // 0x20
	public List`1 slots; // 0x28
	public Boolean canPlayClickAnim; // 0x30
	public Boolean isHide; // 0x31
	public Boolean needPlayClickAnim; // 0x32
	public Boolean forceHideCount; // 0x33
	private Int32 <sortPriority>k__BackingField; // 0x34
	private BuildingToDoType m_type; // 0x38
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_set_type; // 0x8
	private static DelegateBridge __Hotfix0_get_sortPriority; // 0x10
	private static DelegateBridge __Hotfix0_set_sortPriority; // 0x18
	private static DelegateBridge __Hotfix0_get_available; // 0x20
	private static DelegateBridge __Hotfix0_GetCount4Display; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public BuildingToDoType type { get; set; }
	public Int32 sortPriority { get; set; }
	public Boolean available { get; }

	// RVA: 0x2d0d52c VA: 0x759532552c
	public BuildingToDoType get_type() { }
	// RVA: 0x2d0f580 VA: 0x7595327580
	public Void set_type(BuildingToDoType value) { }
	// RVA: 0x2d12110 VA: 0x759532a110
	public Int32 get_sortPriority() { }
	// RVA: 0x2d12094 VA: 0x759532a094
	private Void set_sortPriority(Int32 value) { }
	// RVA: 0x2d12178 VA: 0x759532a178
	public Boolean get_available() { }
	// RVA: 0x2d121f8 VA: 0x759532a1f8
	public Int32 GetCount4Display() { }
	// RVA: 0x2d0f510 VA: 0x7595327510
	public Void .ctor() { }
}
```