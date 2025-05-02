# CrisisV2MapNormalNodeModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2RuneData m_runeData`

- `Boolean m_isUnknown`

- `Boolean m_isLockableNode`

- `String m_runeDesc`

- `Boolean m_isCompleted`

- `Connectivity m_connectivity`


## Properties

- `Boolean isCompleted`

- `Boolean isUnknown`

- `String name`

- `Int32 score`

- `String runeIconId`

- `String runeDesc`

- `Int32 dimension`


## Methods

- `Boolean get_isCompleted()`

- `Boolean get_isUnknown()`

- `String get_name()`

- `Int32 get_score()`

- `String get_runeIconId()`

- `String get_runeDesc()`

- `Int32 get_dimension()`

- `Connectivity <>xLuaBaseProxy_get_connectivity()`

- `Boolean <>xLuaBaseProxy_get_canCoverRoad()`

- `Void <>xLuaBaseProxy_UpdatePlayerData(BasicMapInfo)`

- `Void <>xLuaBaseProxy_OnLoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapNormalNodeModel : CrisisV2MapNodeModel
{
	private CrisisV2RuneData m_runeData; // 0x30
	private Boolean m_isUnknown; // 0x38
	private Boolean m_isLockableNode; // 0x39
	private String m_runeDesc; // 0x40
	private Boolean m_isCompleted; // 0x48
	private Connectivity m_connectivity; // 0x4c
	private static DelegateBridge __Hotfix0_get_isCompleted; // 0x0
	private static DelegateBridge __Hotfix0_get_isUnknown; // 0x8
	private static DelegateBridge __Hotfix0_get_connectivity; // 0x10
	private static DelegateBridge __Hotfix0_get_canCoverRoad; // 0x18
	private static DelegateBridge __Hotfix0_get_name; // 0x20
	private static DelegateBridge __Hotfix0_get_score; // 0x28
	private static DelegateBridge __Hotfix0_get_runeIconId; // 0x30
	private static DelegateBridge __Hotfix0_get_runeDesc; // 0x38
	private static DelegateBridge __Hotfix0_get_dimension; // 0x40
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x48
	private static DelegateBridge __Hotfix0_OnLoadData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean isCompleted { get; }
	public Boolean isUnknown { get; }
	public override Connectivity connectivity { get; }
	public override Boolean canCoverRoad { get; }
	public String name { get; }
	public Int32 score { get; }
	public String runeIconId { get; }
	public String runeDesc { get; }
	public Int32 dimension { get; }

	// RVA: 0x2be854c VA: 0x759520054c
	public Boolean get_isCompleted() { }
	// RVA: 0x2be85b4 VA: 0x75952005b4
	public Boolean get_isUnknown() { }
	// RVA: 0x2be861c VA: 0x759520061c
	public override Connectivity get_connectivity() { }
	// RVA: 0x2be8684 VA: 0x7595200684
	public override Boolean get_canCoverRoad() { }
	// RVA: 0x2be86ec VA: 0x75952006ec
	public String get_name() { }
	// RVA: 0x2be8780 VA: 0x7595200780
	public Int32 get_score() { }
	// RVA: 0x2be87f8 VA: 0x75952007f8
	public String get_runeIconId() { }
	// RVA: 0x2be8870 VA: 0x7595200870
	public String get_runeDesc() { }
	// RVA: 0x2be890c VA: 0x759520090c
	public Int32 get_dimension() { }
	// RVA: 0x2be8984 VA: 0x7595200984
	public override Void UpdatePlayerData(BasicMapInfo playerMapInfo) { }
	// RVA: 0x2be8af4 VA: 0x7595200af4
	protected override Void OnLoadData() { }
	// RVA: 0x2be6f10 VA: 0x75951fef10
	public Void .ctor() { }
	// RVA: 0x2be8c40 VA: 0x7595200c40
	private Connectivity <>xLuaBaseProxy_get_connectivity() { }
	// RVA: 0x2be8c44 VA: 0x7595200c44
	private Boolean <>xLuaBaseProxy_get_canCoverRoad() { }
	// RVA: 0x2be8c48 VA: 0x7595200c48
	private Void <>xLuaBaseProxy_UpdatePlayerData(BasicMapInfo P0) { }
	// RVA: 0x2be8c4c VA: 0x7595200c4c
	private Void <>xLuaBaseProxy_OnLoadData() { }
}
```