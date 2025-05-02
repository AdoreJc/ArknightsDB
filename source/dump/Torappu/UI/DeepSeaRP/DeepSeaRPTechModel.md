# DeepSeaRPTechModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `Boolean <isTechTreeSystemUnlock>k__BackingField`

- `Boolean <isTechTreeNodesAllLock>k__BackingField`

- `Boolean <hasTechTreeCanActive>k__BackingField`

- `Boolean <techSysNeedPop>k__BackingField`

- `Boolean <techTreeNeedPop>k__BackingField`

- `Boolean <haveTechUnlocking>k__BackingField`

- `String m_techTreeUnlockEventId`

- `Boolean m_isRetro`

- `String m_groupId`

- `ReadStatus m_prevTechLockState`

- `Boolean m_techSysStateChange`

- `Boolean m_prevHaveTechUnlock`


## Properties

- `Boolean isTechTreeSystemUnlock`

- `Boolean isTechTreeNodesAllLock`

- `Boolean hasTechTreeCanActive`

- `Boolean techSysNeedPop`

- `Boolean techTreeNeedPop`

- `Boolean haveTechUnlocking`


## Methods

- `Boolean get_isTechTreeSystemUnlock()`

- `Void set_isTechTreeSystemUnlock(Boolean)`

- `Boolean get_isTechTreeNodesAllLock()`

- `Void set_isTechTreeNodesAllLock(Boolean)`

- `Boolean get_hasTechTreeCanActive()`

- `Void set_hasTechTreeCanActive(Boolean)`

- `Boolean get_techSysNeedPop()`

- `Void set_techSysNeedPop(Boolean)`

- `Boolean get_techTreeNeedPop()`

- `Void set_techTreeNeedPop(Boolean)`

- `Boolean get_haveTechUnlocking()`

- `Void set_haveTechUnlocking(Boolean)`

- `Void InitModel(Boolean, String, String)`

- `Void _InitTechUnlockStatus()`

- `Void _InitTechSysLockChangeState()`

- `Void _UpdateTechTreeList(PlayerDeepSea)`

- `Void UpdateTechSysStatus(PlayerDeepSea)`

- `Void ConsumeSysPop()`

- `Boolean _TechTreeSysPopCheck()`

- `Void _LogTechSysPop()`

- `Void ConsumeTechTreePop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPTechModel : IHotfixable
{
	private Boolean <isTechTreeSystemUnlock>k__BackingField; // 0x10
	private Boolean <isTechTreeNodesAllLock>k__BackingField; // 0x11
	private Boolean <hasTechTreeCanActive>k__BackingField; // 0x12
	private Boolean <techSysNeedPop>k__BackingField; // 0x13
	private Boolean <techTreeNeedPop>k__BackingField; // 0x14
	private Boolean <haveTechUnlocking>k__BackingField; // 0x15
	public List`1 techTreeList; // 0x18
	private String m_techTreeUnlockEventId; // 0x20
	private Boolean m_isRetro; // 0x28
	private String m_groupId; // 0x30
	private ReadStatus m_prevTechLockState; // 0x38
	private Boolean m_techSysStateChange; // 0x3c
	private Boolean m_prevHaveTechUnlock; // 0x3d
	private const String SYS_KEY; // 0x0
	private const String TAG_TREE_KEY; // 0x0
	private static DelegateBridge __Hotfix0_get_isTechTreeSystemUnlock; // 0x0
	private static DelegateBridge __Hotfix0_set_isTechTreeSystemUnlock; // 0x8
	private static DelegateBridge __Hotfix0_get_isTechTreeNodesAllLock; // 0x10
	private static DelegateBridge __Hotfix0_set_isTechTreeNodesAllLock; // 0x18
	private static DelegateBridge __Hotfix0_get_hasTechTreeCanActive; // 0x20
	private static DelegateBridge __Hotfix0_set_hasTechTreeCanActive; // 0x28
	private static DelegateBridge __Hotfix0_get_techSysNeedPop; // 0x30
	private static DelegateBridge __Hotfix0_set_techSysNeedPop; // 0x38
	private static DelegateBridge __Hotfix0_get_techTreeNeedPop; // 0x40
	private static DelegateBridge __Hotfix0_set_techTreeNeedPop; // 0x48
	private static DelegateBridge __Hotfix0_get_haveTechUnlocking; // 0x50
	private static DelegateBridge __Hotfix0_set_haveTechUnlocking; // 0x58
	private static DelegateBridge __Hotfix0_InitModel; // 0x60
	private static DelegateBridge __Hotfix0__InitTechUnlockStatus; // 0x68
	private static DelegateBridge __Hotfix0__InitTechSysLockChangeState; // 0x70
	private static DelegateBridge __Hotfix0__UpdateTechTreeList; // 0x78
	private static DelegateBridge __Hotfix0_UpdateTechSysStatus; // 0x80
	private static DelegateBridge __Hotfix0_ConsumeSysPop; // 0x88
	private static DelegateBridge __Hotfix0__TechTreeSysPopCheck; // 0x90
	private static DelegateBridge __Hotfix0__LogTechSysPop; // 0x98
	private static DelegateBridge __Hotfix0_ConsumeTechTreePop; // 0xa0
	private static DelegateBridge __Hotfix0_LogTechTreeAchieved; // 0xa8
	private static DelegateBridge __Hotfix0__TechTreePopCheck; // 0xb0
	private static DelegateBridge __Hotfix0__ConsumeTrack; // 0xb8
	private static DelegateBridge __Hotfix1__ConsumeTrack; // 0xc0
	private static DelegateBridge __Hotfix0_CheckTrack; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public Boolean isTechTreeSystemUnlock { get; set; }
	public Boolean isTechTreeNodesAllLock { get; set; }
	public Boolean hasTechTreeCanActive { get; set; }
	public Boolean techSysNeedPop { get; set; }
	public Boolean techTreeNeedPop { get; set; }
	public Boolean haveTechUnlocking { get; set; }

	// RVA: 0x29ca988 VA: 0x7594fe2988
	public Boolean get_isTechTreeSystemUnlock() { }
	// RVA: 0x29ca9f0 VA: 0x7594fe29f0
	private Void set_isTechTreeSystemUnlock(Boolean value) { }
	// RVA: 0x29caa70 VA: 0x7594fe2a70
	public Boolean get_isTechTreeNodesAllLock() { }
	// RVA: 0x29caad8 VA: 0x7594fe2ad8
	private Void set_isTechTreeNodesAllLock(Boolean value) { }
	// RVA: 0x29cab58 VA: 0x7594fe2b58
	public Boolean get_hasTechTreeCanActive() { }
	// RVA: 0x29cabc0 VA: 0x7594fe2bc0
	private Void set_hasTechTreeCanActive(Boolean value) { }
	// RVA: 0x29cac40 VA: 0x7594fe2c40
	public Boolean get_techSysNeedPop() { }
	// RVA: 0x29caca8 VA: 0x7594fe2ca8
	private Void set_techSysNeedPop(Boolean value) { }
	// RVA: 0x29cad28 VA: 0x7594fe2d28
	public Boolean get_techTreeNeedPop() { }
	// RVA: 0x29cad90 VA: 0x7594fe2d90
	private Void set_techTreeNeedPop(Boolean value) { }
	// RVA: 0x29cae10 VA: 0x7594fe2e10
	public Boolean get_haveTechUnlocking() { }
	// RVA: 0x29cae78 VA: 0x7594fe2e78
	private Void set_haveTechUnlocking(Boolean value) { }
	// RVA: 0x29caef8 VA: 0x7594fe2ef8
	public Void InitModel(Boolean isRetro, String groupId, String sysUnlockEventId) { }
	// RVA: 0x29cb0c8 VA: 0x7594fe30c8
	private Void _InitTechUnlockStatus() { }
	// RVA: 0x29cafe4 VA: 0x7594fe2fe4
	private Void _InitTechSysLockChangeState() { }
	// RVA: 0x29cb29c VA: 0x7594fe329c
	private Void _UpdateTechTreeList(PlayerDeepSea deepSeaData) { }
	// RVA: 0x29cb424 VA: 0x7594fe3424
	public Void UpdateTechSysStatus(PlayerDeepSea deepSeaData) { }
	// RVA: 0x29cb9b4 VA: 0x7594fe39b4
	public Void ConsumeSysPop() { }
	// RVA: 0x29cb7e4 VA: 0x7594fe37e4
	private Boolean _TechTreeSysPopCheck() { }
	// RVA: 0x29cb768 VA: 0x7594fe3768
	private Void _LogTechSysPop() { }
	// RVA: 0x29cbca8 VA: 0x7594fe3ca8
	public Void ConsumeTechTreePop() { }
	// RVA: 0x29cbbb8 VA: 0x7594fe3bb8
	public static Void LogTechTreeAchieved(String techId) { }
	// RVA: 0x29cb880 VA: 0x7594fe3880
	private static Boolean _TechTreePopCheck(PlayerDeepSea deepSea) { }
	// RVA: 0x29cbeb0 VA: 0x7594fe3eb0
	private static Void _ConsumeTrack(List`1 techIds) { }
	// RVA: 0x29cba3c VA: 0x7594fe3a3c
	private static Void _ConsumeTrack(String techId) { }
	// RVA: 0x29cbb10 VA: 0x7594fe3b10
	public static Boolean CheckTrack(String key) { }
	// RVA: 0x29cc160 VA: 0x7594fe4160
	public Void .ctor() { }
}
```