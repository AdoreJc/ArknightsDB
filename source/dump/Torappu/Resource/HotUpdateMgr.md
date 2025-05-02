# HotUpdateMgr

**Namespace:** `Torappu.Resource`


## Methods

- `Void _Init(Boolean)`

- `Boolean _CheckUpdate(String)`

- `Void _SetUpdate(String, Boolean)`

- `Void _SetUpdateList(IList`1, Boolean)`

- `String _CheckType(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource
public class HotUpdateMgr : Singleton`1
{
	private Dictionary`2 m_typeInfos; // 0x10
	private Dictionary`2 m_status; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_CheckUpdate; // 0x8
	private static DelegateBridge __Hotfix0_CheckUpdateByABName; // 0x10
	private static DelegateBridge __Hotfix0_SetUpdate; // 0x18
	private static DelegateBridge __Hotfix0_SetUpdateList; // 0x20
	private static DelegateBridge __Hotfix0_CheckType; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30
	private static DelegateBridge __Hotfix0__Init; // 0x38
	private static DelegateBridge __Hotfix0__CheckUpdate; // 0x40
	private static DelegateBridge __Hotfix0__SetUpdate; // 0x48
	private static DelegateBridge __Hotfix0__SetUpdateList; // 0x50
	private static DelegateBridge __Hotfix0__CheckType; // 0x58


	// RVA: 0x373d43c VA: 0x7595d5543c
	public static Void Init(Boolean force) { }
	// RVA: 0x373d7d0 VA: 0x7595d557d0
	public static Boolean CheckUpdate(String resType) { }
	// RVA: 0x373d968 VA: 0x7595d55968
	public static Boolean CheckUpdateByABName(String abname) { }
	// RVA: 0x373dac0 VA: 0x7595d55ac0
	public static Void SetUpdate(String resType, Boolean update) { }
	// RVA: 0x373dc94 VA: 0x7595d55c94
	public static Void SetUpdateList(IList`1 resTypeList, Boolean update) { }
	// RVA: 0x373dfac VA: 0x7595d55fac
	public static String CheckType(String abname) { }
	// RVA: 0x373e038 VA: 0x7595d56038
	private Void .ctor() { }
	// RVA: 0x373d4c8 VA: 0x7595d554c8
	private Void _Init(Boolean force) { }
	// RVA: 0x373d85c VA: 0x7595d5585c
	private Boolean _CheckUpdate(String type) { }
	// RVA: 0x373db64 VA: 0x7595d55b64
	private Void _SetUpdate(String type, Boolean update) { }
	// RVA: 0x373dd38 VA: 0x7595d55d38
	private Void _SetUpdateList(IList`1 typeList, Boolean update) { }
	// RVA: 0x373da10 VA: 0x7595d55a10
	private String _CheckType(String abname) { }
}
```