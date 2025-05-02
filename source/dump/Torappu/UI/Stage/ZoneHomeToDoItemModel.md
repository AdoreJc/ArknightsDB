# ZoneHomeToDoItemModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `HomeToDoFuncType m_funcType`

- `String m_funcId`

- `HomeToDoSortIndex <sortIndex>k__BackingField`

- `Int32 viewIndex`

- `Int64 endTs`

- `String m_cachedId`


## Properties

- `HomeToDoFuncType funcType`

- `String funcId`

- `HomeToDoSortIndex sortIndex`


## Methods

- `HomeToDoFuncType get_funcType()`

- `Void set_funcType(HomeToDoFuncType)`

- `String get_funcId()`

- `Void set_funcId(String)`

- `HomeToDoSortIndex get_sortIndex()`

- `Void set_sortIndex(HomeToDoSortIndex)`

- `String GetId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneHomeToDoItemModel : IHotfixable
{
	private HomeToDoFuncType m_funcType; // 0x10
	private String m_funcId; // 0x18
	private HomeToDoSortIndex <sortIndex>k__BackingField; // 0x20
	public Int32 viewIndex; // 0x24
	public Int64 endTs; // 0x28
	private String m_cachedId; // 0x30
	private static DelegateBridge __Hotfix0_get_funcType; // 0x0
	private static DelegateBridge __Hotfix0_set_funcType; // 0x8
	private static DelegateBridge __Hotfix0_get_funcId; // 0x10
	private static DelegateBridge __Hotfix0_set_funcId; // 0x18
	private static DelegateBridge __Hotfix0_get_sortIndex; // 0x20
	private static DelegateBridge __Hotfix0_set_sortIndex; // 0x28
	private static DelegateBridge __Hotfix0_GetId; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public HomeToDoFuncType funcType { get; set; }
	public String funcId { get; set; }
	public HomeToDoSortIndex sortIndex { get; set; }

	// RVA: 0x2f0bda4 VA: 0x7595523da4
	public HomeToDoFuncType get_funcType() { }
	// RVA: 0x2f0bed0 VA: 0x7595523ed0
	public Void set_funcType(HomeToDoFuncType value) { }
	// RVA: 0x2f0bf74 VA: 0x7595523f74
	public String get_funcId() { }
	// RVA: 0x2f0bfdc VA: 0x7595523fdc
	public Void set_funcId(String value) { }
	// RVA: 0x2f0bd3c VA: 0x7595523d3c
	public HomeToDoSortIndex get_sortIndex() { }
	// RVA: 0x2f0c098 VA: 0x7595524098
	protected Void set_sortIndex(HomeToDoSortIndex value) { }
	// RVA: 0x2f0800c VA: 0x759552000c
	public String GetId() { }
	// RVA: 0x2f0c114 VA: 0x7595524114
	public Void .ctor() { }
}
```