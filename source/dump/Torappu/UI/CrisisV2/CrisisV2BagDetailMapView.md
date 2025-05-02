# CrisisV2BagDetailMapView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2MapRoadView _roadPrefab`

- `RectTransform _unselectRoadContainer`

- `RectTransform _selectRoadContainer`

- `CrisisV2MapRoadPointView _roadPointPrefab`

- `RectTransform _unselectRoadPointContainer`

- `RectTransform _selectRoadPointContainer`

- `CrisisV2MapBagView _bagPrefab`

- `RectTransform _bagContainer`

- `CrisisV2MapNodeViewHolder _nodeHolderPrefab`

- `RectTransform _nodeContainer`

- `CrisisV2MapRoadDictPool m_roadDictPool`

- `CrisisV2MapRoadPointDictPool m_roadPointDictPool`

- `CrisisV2MapBagDictPool m_bagDictPool`

- `CrisisV2MapTreasureDictPool m_treasureDictPool`


## Methods

- `Void ClosePreviewViewIfOpen()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2BagDetailMapView : CrisisV2DetailMapViewBase
{
	private CrisisV2MapRoadView _roadPrefab; // 0x88
	private RectTransform _unselectRoadContainer; // 0x90
	private RectTransform _selectRoadContainer; // 0x98
	private CrisisV2MapRoadPointView _roadPointPrefab; // 0xa0
	private RectTransform _unselectRoadPointContainer; // 0xa8
	private RectTransform _selectRoadPointContainer; // 0xb0
	private CrisisV2MapBagView _bagPrefab; // 0xb8
	private RectTransform _bagContainer; // 0xc0
	private CrisisV2MapNodeViewHolder _nodeHolderPrefab; // 0xc8
	private RectTransform _nodeContainer; // 0xd0
	private CrisisV2MapRoadDictPool m_roadDictPool; // 0xd8
	private CrisisV2MapRoadPointDictPool m_roadPointDictPool; // 0xe0
	private CrisisV2MapBagDictPool m_bagDictPool; // 0xe8
	private CrisisV2MapTreasureDictPool m_treasureDictPool; // 0xf0
	private static DelegateBridge __Hotfix0_UpdateDictPool; // 0x0
	private static DelegateBridge __Hotfix0_ForceRecycleDictPool; // 0x8
	private static DelegateBridge __Hotfix0_InitDictPool; // 0x10
	private static DelegateBridge __Hotfix0_GetViewType; // 0x18
	private static DelegateBridge __Hotfix0_GetMapSize; // 0x20
	private static DelegateBridge __Hotfix0_ClosePreviewViewIfOpen; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2bfd27c VA: 0x759521527c
	protected override Void UpdateDictPool(CrisisV2MapModel mapModel) { }
	// RVA: 0x2bfd42c VA: 0x759521542c
	protected override Void ForceRecycleDictPool() { }
	// RVA: 0x2bfd520 VA: 0x7595215520
	protected override Void InitDictPool() { }
	// RVA: 0x2bfd9e4 VA: 0x75952159e4
	protected override ViewType GetViewType() { }
	// RVA: 0x2bfda4c VA: 0x7595215a4c
	protected override Vector2 GetMapSize(CrisisV2MapModel mapModel) { }
	// RVA: 0x2bfdb24 VA: 0x7595215b24
	public Void ClosePreviewViewIfOpen() { }
	// RVA: 0x2bfdbc8 VA: 0x7595215bc8
	public Void .ctor() { }
}
```