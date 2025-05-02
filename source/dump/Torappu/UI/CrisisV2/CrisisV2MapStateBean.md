# CrisisV2MapStateBean

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String targetMapId`

- `String previewNodeIdFromMissionState`

- `ViewType targetViewTypeFromMissionState`

- `CrisisV2MapPreviewParams previewParams`

- `CrisisV2MapProp m_mapProp`


## Properties

- `CrisisV2MapProp mapProp`


## Methods

- `CrisisV2MapProp get_mapProp()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapStateBean : IStateBean, IHotfixable
{
	public String targetMapId; // 0x10
	public String previewNodeIdFromMissionState; // 0x18
	public ViewType targetViewTypeFromMissionState; // 0x20
	public CrisisV2MapPreviewParams previewParams; // 0x28
	private CrisisV2MapProp m_mapProp; // 0x38
	private static DelegateBridge __Hotfix0_get_mapProp; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public CrisisV2MapProp mapProp { get; }

	// RVA: 0x2be8ec8 VA: 0x7595200ec8
	public CrisisV2MapProp get_mapProp() { }
	// RVA: 0x2be8f30 VA: 0x7595200f30
	public Void .ctor() { }
}
```