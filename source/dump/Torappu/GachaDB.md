# GachaDB

**Namespace:** `Torappu`


## Methods

- `Void _InitFreeLimitGachaMap()`

- `Void _InitPoolSearchTable()`

- `GachaPoolClientData GetGachaPool(String)`

- `String GetGuaranteeName(String)`

- `String GetRecruit6StarHint(String)`

- `SpecialRecruitPool GetSpecialRecruitPool(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GachaDB : ConstTable`2
{
	private Dictionary`2 m_recruitBuildTimeMap; // 0x60
	private Dictionary`2 m_freeLimitGachaMap; // 0x68
	private Dictionary`2 m_poolMap; // 0x70
	private TimeList`1 m_poolTimeList; // 0x78
	private TimeList`1 m_limitTktTimeList; // 0x80
	private TimeList`1 m_linkageTktTimeList; // 0x88
	private TimeList`1 m_normalTktTimeList; // 0x90
	private static DelegateBridge __Hotfix0_get_recruitBuildTimeMap; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0__InitFreeLimitGachaMap; // 0x10
	private static DelegateBridge __Hotfix0__InitPoolSearchTable; // 0x18
	private static DelegateBridge __Hotfix0_GetGachaPool; // 0x20
	private static DelegateBridge __Hotfix0_GetGuaranteeName; // 0x28
	private static DelegateBridge __Hotfix0_GetRecruit6StarHint; // 0x30
	private static DelegateBridge __Hotfix0_GetSpecialRecruitPool; // 0x38
	private static DelegateBridge __Hotfix0_CheckFreeGachaLastRefresh; // 0x40
	private static DelegateBridge __Hotfix0_GetValidPoolsEnumerator; // 0x48
	private static DelegateBridge __Hotfix0_GetValidLimitTenGachaTktEnumerator; // 0x50
	private static DelegateBridge __Hotfix0_GetValidLinkageTenGachaTktEnumerator; // 0x58
	private static DelegateBridge __Hotfix0_GetValiNormalGachaTktEnumerator; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Dictionary`2 recruitBuildTimeMap { get; }

	// RVA: 0x31f10a8 VA: 0x75958090a8
	public Dictionary`2 get_recruitBuildTimeMap() { }
	// RVA: 0x31f1110 VA: 0x7595809110
	protected override Void OnInit() { }
	// RVA: 0x31f12b0 VA: 0x75958092b0
	private Void _InitFreeLimitGachaMap() { }
	// RVA: 0x31f140c VA: 0x759580940c
	private Void _InitPoolSearchTable() { }
	// RVA: 0x31f166c VA: 0x759580966c
	public GachaPoolClientData GetGachaPool(String poolId) { }
	// RVA: 0x31f1708 VA: 0x7595809708
	public String GetGuaranteeName(String poolId) { }
	// RVA: 0x31f17b8 VA: 0x75958097b8
	public String GetRecruit6StarHint(String poolId) { }
	// RVA: 0x31f1900 VA: 0x7595809900
	public SpecialRecruitPool GetSpecialRecruitPool(Int32 tagId) { }
	// RVA: 0x31f1a2c VA: 0x7595809a2c
	public static Boolean CheckFreeGachaLastRefresh(String inputPoolId) { }
	// RVA: 0x31f1bc8 VA: 0x7595809bc8
	public IEnumerator`1 GetValidPoolsEnumerator() { }
	// RVA: 0x31f1c84 VA: 0x7595809c84
	public IEnumerator`1 GetValidLimitTenGachaTktEnumerator() { }
	// RVA: 0x31f1d40 VA: 0x7595809d40
	public IEnumerator`1 GetValidLinkageTenGachaTktEnumerator() { }
	// RVA: 0x31f1dfc VA: 0x7595809dfc
	public IEnumerator`1 GetValiNormalGachaTktEnumerator() { }
	// RVA: 0x31f1eb8 VA: 0x7595809eb8
	public Void .ctor() { }
}
```