# CrisisV2RuneSingleItemViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String m_mapId`

- `String m_bagId`

- `String m_nodeId`

- `String m_description`

- `Int32 m_point`

- `Int32 m_uniqueSortId`

- `String m_tutorialHighLightKey`


## Methods

- `String GetDesc()`

- `Int32 GetPoint()`

- `String GetTutorialHighLightKey()`

- `Void LoadData(String, String, CrisisV2RuneData, String, CrisisV2MapDetailData, Boolean)`

- `String <>xLuaBaseProxy_GetGlobalId()`

- `SingleViewInfoType <>xLuaBaseProxy_GetViewType()`

- `Int32 <>xLuaBaseProxy_GetUniqueSortId()`

- `String <>xLuaBaseProxy_GetItemId()`

- `String <>xLuaBaseProxy_GetBagId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RuneSingleItemViewModel : CrisisV2RuneSingleViewModel, ICrisisV2RuneSingleItemInfo, IHotfixable
{
	private String m_mapId; // 0x18
	private String m_bagId; // 0x20
	private String m_nodeId; // 0x28
	private String m_description; // 0x30
	private Int32 m_point; // 0x38
	private Int32 m_uniqueSortId; // 0x3c
	private String m_tutorialHighLightKey; // 0x40
	private static DelegateBridge __Hotfix0_GetGlobalId; // 0x0
	private static DelegateBridge __Hotfix0_GetViewType; // 0x8
	private static DelegateBridge __Hotfix0_GetUniqueSortId; // 0x10
	private static DelegateBridge __Hotfix0_GetItemId; // 0x18
	private static DelegateBridge __Hotfix0_GetBagId; // 0x20
	private static DelegateBridge __Hotfix0_GetDesc; // 0x28
	private static DelegateBridge __Hotfix0_GetPoint; // 0x30
	private static DelegateBridge __Hotfix0_GetTutorialHighLightKey; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2bf5438 VA: 0x759520d438
	public override String GetGlobalId() { }
	// RVA: 0x2bf54c0 VA: 0x759520d4c0
	public override SingleViewInfoType GetViewType() { }
	// RVA: 0x2bf5528 VA: 0x759520d528
	public override Int32 GetUniqueSortId() { }
	// RVA: 0x2bf5590 VA: 0x759520d590
	public override String GetItemId() { }
	// RVA: 0x2bf55f8 VA: 0x759520d5f8
	public override String GetBagId() { }
	// RVA: 0x2bf5660 VA: 0x759520d660
	public String GetDesc() { }
	// RVA: 0x2bf56c8 VA: 0x759520d6c8
	public Int32 GetPoint() { }
	// RVA: 0x2bf5730 VA: 0x759520d730
	public String GetTutorialHighLightKey() { }
	// RVA: 0x2bf5798 VA: 0x759520d798
	public Void LoadData(String mapId, String nodeId, CrisisV2RuneData runeData, String slotPackId, CrisisV2MapDetailData mapDetailData, Boolean isHighLightRune) { }
	// RVA: 0x2bf597c VA: 0x759520d97c
	public Void .ctor() { }
	// RVA: 0x2bf59e8 VA: 0x759520d9e8
	private String <>xLuaBaseProxy_GetGlobalId() { }
	// RVA: 0x2bf59ec VA: 0x759520d9ec
	private SingleViewInfoType <>xLuaBaseProxy_GetViewType() { }
	// RVA: 0x2bf59f0 VA: 0x759520d9f0
	private Int32 <>xLuaBaseProxy_GetUniqueSortId() { }
	// RVA: 0x2bf59f4 VA: 0x759520d9f4
	private String <>xLuaBaseProxy_GetItemId() { }
	// RVA: 0x2bf59f8 VA: 0x759520d9f8
	private String <>xLuaBaseProxy_GetBagId() { }
}
```