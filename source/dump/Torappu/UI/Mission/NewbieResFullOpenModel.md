# NewbieResFullOpenModel

**Namespace:** `Torappu.UI.Mission`


## Fields

- `Boolean m_isAvail`

- `Boolean m_isUnlock`

- `Boolean m_isPause`

- `String <title>k__BackingField`

- `String <desc>k__BackingField`

- `String <lockHintStr>k__BackingField`

- `Int32 <remainDay>k__BackingField`


## Properties

- `String title`

- `String desc`

- `String lockHintStr`

- `Int32 remainDay`

- `Boolean showRemainDay`

- `Boolean isLock`

- `Boolean isExpire`

- `Boolean isPause`


## Methods

- `String get_title()`

- `Void set_title(String)`

- `String get_desc()`

- `Void set_desc(String)`

- `String get_lockHintStr()`

- `Void set_lockHintStr(String)`

- `Int32 get_remainDay()`

- `Void set_remainDay(Int32)`

- `Boolean get_showRemainDay()`

- `Boolean get_isLock()`

- `Boolean get_isExpire()`

- `Boolean get_isPause()`

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class NewbieResFullOpenModel : IHotfixable
{
	private Boolean m_isAvail; // 0x10
	private Boolean m_isUnlock; // 0x11
	private Boolean m_isPause; // 0x12
	private String <title>k__BackingField; // 0x18
	private String <desc>k__BackingField; // 0x20
	private String <lockHintStr>k__BackingField; // 0x28
	private Int32 <remainDay>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_title; // 0x0
	private static DelegateBridge __Hotfix0_set_title; // 0x8
	private static DelegateBridge __Hotfix0_get_desc; // 0x10
	private static DelegateBridge __Hotfix0_set_desc; // 0x18
	private static DelegateBridge __Hotfix0_get_lockHintStr; // 0x20
	private static DelegateBridge __Hotfix0_set_lockHintStr; // 0x28
	private static DelegateBridge __Hotfix0_get_remainDay; // 0x30
	private static DelegateBridge __Hotfix0_set_remainDay; // 0x38
	private static DelegateBridge __Hotfix0_get_showRemainDay; // 0x40
	private static DelegateBridge __Hotfix0_get_isLock; // 0x48
	private static DelegateBridge __Hotfix0_get_isExpire; // 0x50
	private static DelegateBridge __Hotfix0_get_isPause; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public String title { get; set; }
	public String desc { get; set; }
	public String lockHintStr { get; set; }
	public Int32 remainDay { get; set; }
	public Boolean showRemainDay { get; }
	public Boolean isLock { get; }
	public Boolean isExpire { get; }
	public Boolean isPause { get; }

	// RVA: 0x2734dd0 VA: 0x7594d4cdd0
	public String get_title() { }
	// RVA: 0x2734e38 VA: 0x7594d4ce38
	private Void set_title(String value) { }
	// RVA: 0x2734ebc VA: 0x7594d4cebc
	public String get_desc() { }
	// RVA: 0x2734f24 VA: 0x7594d4cf24
	private Void set_desc(String value) { }
	// RVA: 0x2734fa8 VA: 0x7594d4cfa8
	public String get_lockHintStr() { }
	// RVA: 0x2735010 VA: 0x7594d4d010
	private Void set_lockHintStr(String value) { }
	// RVA: 0x2735094 VA: 0x7594d4d094
	public Int32 get_remainDay() { }
	// RVA: 0x27350fc VA: 0x7594d4d0fc
	private Void set_remainDay(Int32 value) { }
	// RVA: 0x2735178 VA: 0x7594d4d178
	public Boolean get_showRemainDay() { }
	// RVA: 0x27351fc VA: 0x7594d4d1fc
	public Boolean get_isLock() { }
	// RVA: 0x273526c VA: 0x7594d4d26c
	public Boolean get_isExpire() { }
	// RVA: 0x27352ec VA: 0x7594d4d2ec
	public Boolean get_isPause() { }
	// RVA: 0x27349c4 VA: 0x7594d4c9c4
	public Void LoadData() { }
	// RVA: 0x273536c VA: 0x7594d4d36c
	public Void .ctor() { }
}
```