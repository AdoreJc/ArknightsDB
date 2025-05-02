# ClimbTowerTrapViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String m_trapId`

- `String m_trapName`

- `String m_trapDesc`

- `String m_iconId`

- `ClimbTowerTrapType m_trapType`


## Properties

- `String trapId`

- `String trapName`

- `String trapDesc`

- `String iconId`

- `ClimbTowerTrapType trapType`


## Methods

- `String get_trapId()`

- `String get_trapName()`

- `String get_trapDesc()`

- `String get_iconId()`

- `ClimbTowerTrapType get_trapType()`

- `Void InitData(String, ClimbTowerTrapType)`

- `Void _InitMainCardData(String)`

- `Void _InitSubCardData(String)`

- `Void _InitCurseCardData(String)`

- `Void _InitTrapData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrapViewModel : IHotfixable
{
	private String m_trapId; // 0x10
	private String m_trapName; // 0x18
	private String m_trapDesc; // 0x20
	private String m_iconId; // 0x28
	private ClimbTowerTrapType m_trapType; // 0x30
	private static DelegateBridge __Hotfix0_get_trapId; // 0x0
	private static DelegateBridge __Hotfix0_get_trapName; // 0x8
	private static DelegateBridge __Hotfix0_get_trapDesc; // 0x10
	private static DelegateBridge __Hotfix0_get_iconId; // 0x18
	private static DelegateBridge __Hotfix0_get_trapType; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x28
	private static DelegateBridge __Hotfix0__InitMainCardData; // 0x30
	private static DelegateBridge __Hotfix0__InitSubCardData; // 0x38
	private static DelegateBridge __Hotfix0__InitCurseCardData; // 0x40
	private static DelegateBridge __Hotfix0__InitTrapData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String trapId { get; }
	public String trapName { get; }
	public String trapDesc { get; }
	public String iconId { get; }
	public ClimbTowerTrapType trapType { get; }

	// RVA: 0x2c8ed58 VA: 0x75952a6d58
	public String get_trapId() { }
	// RVA: 0x2c8ec88 VA: 0x75952a6c88
	public String get_trapName() { }
	// RVA: 0x2c8ecf0 VA: 0x75952a6cf0
	public String get_trapDesc() { }
	// RVA: 0x2c8f0d0 VA: 0x75952a70d0
	public String get_iconId() { }
	// RVA: 0x2c8f138 VA: 0x75952a7138
	public ClimbTowerTrapType get_trapType() { }
	// RVA: 0x2c90da0 VA: 0x75952a8da0
	public Void InitData(String trapId, ClimbTowerTrapType trapType) { }
	// RVA: 0x2c90f18 VA: 0x75952a8f18
	private Void _InitMainCardData(String cardId) { }
	// RVA: 0x2c91030 VA: 0x75952a9030
	private Void _InitSubCardData(String cardId) { }
	// RVA: 0x2c91170 VA: 0x75952a9170
	private Void _InitCurseCardData(String cardId) { }
	// RVA: 0x2c91290 VA: 0x75952a9290
	private Void _InitTrapData(String trapId) { }
	// RVA: 0x2c90d30 VA: 0x75952a8d30
	public Void .ctor() { }
}
```