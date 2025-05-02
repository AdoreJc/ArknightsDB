# Act20sideCollectionViewModel

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String m_curSelectCompId`

- `Int32 collectProgressNum`

- `Int32 collectProgressTotalNum`

- `Int32 totalCollectedNum`


## Properties

- `String curSelectCompId`


## Methods

- `String get_curSelectCompId()`

- `Void set_curSelectCompId(String)`

- `Void LoadData(String)`

- `CartAccessoryPos _TypeToCollectionDisplayPos(CartAccessoryType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCollectionViewModel : IHotfixable
{
	private String m_curSelectCompId; // 0x10
	public List`1 collectItemList; // 0x18
	public Int32 collectProgressNum; // 0x20
	public Int32 collectProgressTotalNum; // 0x24
	public Int32 totalCollectedNum; // 0x28
	private static readonly Dictionary`2 DISPLAY_BG_RES_MAP; // 0x0
	private static DelegateBridge __Hotfix0_get_curSelectCompId; // 0x8
	private static DelegateBridge __Hotfix0_set_curSelectCompId; // 0x10
	private static DelegateBridge __Hotfix0__GetCarTable; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0__TypeToCollectionDisplayPos; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String curSelectCompId { get; set; }

	// RVA: 0x32ff048 VA: 0x7595917048
	public String get_curSelectCompId() { }
	// RVA: 0x32f6a30 VA: 0x759590ea30
	public Void set_curSelectCompId(String value) { }
	// RVA: 0x33032e0 VA: 0x759591b2e0
	private Dictionary`2 _GetCarTable() { }
	// RVA: 0x3302c30 VA: 0x759591ac30
	public Void LoadData(String activityId) { }
	// RVA: 0x33033fc VA: 0x759591b3fc
	private CartAccessoryPos _TypeToCollectionDisplayPos(CartAccessoryType type) { }
	// RVA: 0x33034a4 VA: 0x759591b4a4
	public Void .ctor() { }
	// RVA: 0x3303524 VA: 0x759591b524
	private static Void .cctor() { }
}
```