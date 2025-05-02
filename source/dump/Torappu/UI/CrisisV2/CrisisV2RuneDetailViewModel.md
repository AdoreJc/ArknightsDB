# CrisisV2RuneDetailViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `ViewType m_viewType`

- `TargetType m_targetType`

- `String m_focusTargetId`

- `Int32 m_focusSeq`


## Properties

- `Int32 focusSeq`


## Methods

- `Int32 get_focusSeq()`

- `Void RefreshFocus(ViewType, TargetType, String)`

- `Boolean IsSlotNodeFocus(String)`

- `Boolean IsSlotBagFocus(String)`

- `Boolean IsPackBagFocus(String)`

- `Void RefreshSlotRuneSingleViewList(HashSet`1, ViewType, String, CrisisV2MapDetailData, Boolean, String)`

- `Void _RefreshSingleItemBgType()`

- `Void RefreshSlotRunePackViewList(HashSet`1, ViewType, String, CrisisV2MapDetailData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2RuneDetailViewModel : IHotfixable
{
	private List`1 m_singleViewModels; // 0x10
	private List`1 m_packViewModels; // 0x18
	private ViewType m_viewType; // 0x20
	private TargetType m_targetType; // 0x24
	private String m_focusTargetId; // 0x28
	private Int32 m_focusSeq; // 0x30
	private static DelegateBridge __Hotfix0_get_singleViewModels; // 0x0
	private static DelegateBridge __Hotfix0_get_packViewModels; // 0x8
	private static DelegateBridge __Hotfix0_get_focusSeq; // 0x10
	private static DelegateBridge __Hotfix0_RefreshFocus; // 0x18
	private static DelegateBridge __Hotfix0_IsSlotNodeFocus; // 0x20
	private static DelegateBridge __Hotfix0_IsSlotBagFocus; // 0x28
	private static DelegateBridge __Hotfix0_IsPackBagFocus; // 0x30
	private static DelegateBridge __Hotfix0_RefreshSlotRuneSingleViewList; // 0x38
	private static DelegateBridge __Hotfix0__RefreshSingleItemBgType; // 0x40
	private static DelegateBridge __Hotfix0_RefreshSlotRunePackViewList; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public List`1 singleViewModels { get; }
	public List`1 packViewModels { get; }
	public Int32 focusSeq { get; }

	// RVA: 0x2bf71f4 VA: 0x759520f1f4
	public List`1 get_singleViewModels() { }
	// RVA: 0x2bf725c VA: 0x759520f25c
	public List`1 get_packViewModels() { }
	// RVA: 0x2bf72c4 VA: 0x759520f2c4
	public Int32 get_focusSeq() { }
	// RVA: 0x2bf732c VA: 0x759520f32c
	public Void RefreshFocus(ViewType viewType, TargetType targetType, String targetId) { }
	// RVA: 0x2bf73f8 VA: 0x759520f3f8
	public Boolean IsSlotNodeFocus(String nodeId) { }
	// RVA: 0x2bf74b8 VA: 0x759520f4b8
	public Boolean IsSlotBagFocus(String bagId) { }
	// RVA: 0x2bf7578 VA: 0x759520f578
	public Boolean IsPackBagFocus(String bagId) { }
	// RVA: 0x2bf7638 VA: 0x759520f638
	public Void RefreshSlotRuneSingleViewList(HashSet`1 selectNodeSet, ViewType viewType, String mapId, CrisisV2MapDetailData mapDetailData, Boolean curMapHasRunePack, String highlightRuneId) { }
	// RVA: 0x2bf7c80 VA: 0x759520fc80
	private Void _RefreshSingleItemBgType() { }
	// RVA: 0x2bf7e24 VA: 0x759520fe24
	public Void RefreshSlotRunePackViewList(HashSet`1 selectNodeSet, ViewType viewType, String mapId, CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bf88d8 VA: 0x75952108d8
	public Void .ctor() { }
}
```