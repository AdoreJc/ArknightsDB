# CrisisV2SlotDetailMapView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2MapRoadView _roadPrefab`

- `CrisisV2MapRoadPointView _roadPointPrefab`

- `RectTransform _unselectRoadContainer`

- `RectTransform _selectRoadContainer`

- `RectTransform _unselectPointContainer`

- `RectTransform _selectPointContainer`

- `CrisisV2MapNodeViewHolder _nodeHolderPrefab`

- `RectTransform _nodeUpperContainer`

- `RectTransform _nodeLowerContainer`

- `CrisisV2MapBagTitleView _bagTitlePrefab`

- `RectTransform _bagTitleContainer`

- `CrisisV2MapBagBgView _bagBgPrefab`

- `RectTransform _bagBgContainer`

- `CrisisV2MapExclusionGroupView _exclusionGroupPrefab`

- `RectTransform _exclusionGroupContainer`

- `CrisisV2MapBagTitleDictPool m_bagTitlePool`

- `CrisisV2MapBagBgDictPool m_bagBgPool`

- `CrisisV2MapExclusionDictPool m_exclusionPool`

- `CrisisV2MapRoadDictPool m_roadDictPool`

- `CrisisV2MapRoadPointDictPool m_roadPointDictPool`

- `CrisisV2MapNodeDictPool m_lowerNodeDictPool`

- `CrisisV2MapNodeDictPool m_upperNodeDictPool`


## Methods

- `Void ClosePreviewViewIfOpen()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SlotDetailMapView : CrisisV2DetailMapViewBase
{
	private CrisisV2MapRoadView _roadPrefab; // 0x88
	private CrisisV2MapRoadPointView _roadPointPrefab; // 0x90
	private RectTransform _unselectRoadContainer; // 0x98
	private RectTransform _selectRoadContainer; // 0xa0
	private RectTransform _unselectPointContainer; // 0xa8
	private RectTransform _selectPointContainer; // 0xb0
	private CrisisV2MapNodeViewHolder _nodeHolderPrefab; // 0xb8
	private RectTransform _nodeUpperContainer; // 0xc0
	private RectTransform _nodeLowerContainer; // 0xc8
	private CrisisV2MapBagTitleView _bagTitlePrefab; // 0xd0
	private RectTransform _bagTitleContainer; // 0xd8
	private CrisisV2MapBagBgView _bagBgPrefab; // 0xe0
	private RectTransform _bagBgContainer; // 0xe8
	private CrisisV2MapExclusionGroupView _exclusionGroupPrefab; // 0xf0
	private RectTransform _exclusionGroupContainer; // 0xf8
	private CrisisV2MapBagTitleDictPool m_bagTitlePool; // 0x100
	private CrisisV2MapBagBgDictPool m_bagBgPool; // 0x108
	private CrisisV2MapExclusionDictPool m_exclusionPool; // 0x110
	private CrisisV2MapRoadDictPool m_roadDictPool; // 0x118
	private CrisisV2MapRoadPointDictPool m_roadPointDictPool; // 0x120
	private CrisisV2MapNodeDictPool m_lowerNodeDictPool; // 0x128
	private CrisisV2MapNodeDictPool m_upperNodeDictPool; // 0x130
	private static DelegateBridge __Hotfix0_UpdateDictPool; // 0x0
	private static DelegateBridge __Hotfix0_ForceRecycleDictPool; // 0x8
	private static DelegateBridge __Hotfix0_InitDictPool; // 0x10
	private static DelegateBridge __Hotfix0_GetViewType; // 0x18
	private static DelegateBridge __Hotfix0_GetMapSize; // 0x20
	private static DelegateBridge __Hotfix0_ClosePreviewViewIfOpen; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2c17704 VA: 0x759522f704
	protected override Void UpdateDictPool(CrisisV2MapModel mapModel) { }
	// RVA: 0x2c17888 VA: 0x759522f888
	protected override Void ForceRecycleDictPool() { }
	// RVA: 0x2c179c0 VA: 0x759522f9c0
	protected override Void InitDictPool() { }
	// RVA: 0x2c17f78 VA: 0x759522ff78
	protected override ViewType GetViewType() { }
	// RVA: 0x2c17fe0 VA: 0x759522ffe0
	protected override Vector2 GetMapSize(CrisisV2MapModel mapModel) { }
	// RVA: 0x2c180b8 VA: 0x75952300b8
	public Void ClosePreviewViewIfOpen() { }
	// RVA: 0x2c1815c VA: 0x759523015c
	public Void .ctor() { }
}
```