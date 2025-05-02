# CrisisV2MapRoadPointView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `PointStyle _startPointStyle`

- `PointStyle _endPointStyle`

- `Material _matDisableRoad`


## Methods

- `Void Init(CrisisV2RoadPosData)`

- `Void Render(CrisisV2MapRoadModel, CrisisV2MapRoadStatus, CrisisV2RoadPointStyle, CrisisV2RoadPointStyle)`

- `Void _UpdatePointStyle(PointStyle, CrisisV2RoadPointStyle, CrisisV2MapRoadStatus)`

- `Void _SetImgStatus(Image, Boolean, Boolean)`

- `Void _SetPosAndSize(CrisisV2RoadPosData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapRoadPointView : MonoBehaviour, IHotfixable
{
	private PointStyle _startPointStyle; // 0x18
	private PointStyle _endPointStyle; // 0x20
	private Material _matDisableRoad; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__UpdatePointStyle; // 0x10
	private static DelegateBridge __Hotfix0__SetImgStatus; // 0x18
	private static DelegateBridge __Hotfix0__SetPosAndSize; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2c0b000 VA: 0x7595223000
	public Void Init(CrisisV2RoadPosData roadPosData) { }
	// RVA: 0x2c0b724 VA: 0x7595223724
	public Void Render(CrisisV2MapRoadModel roadModel, CrisisV2MapRoadStatus roadStatus, CrisisV2RoadPointStyle startPointStyle, CrisisV2RoadPointStyle endPointStyle) { }
	// RVA: 0x2c0bc1c VA: 0x7595223c1c
	private Void _UpdatePointStyle(PointStyle pointStyle, CrisisV2RoadPointStyle style, CrisisV2MapRoadStatus roadStatus) { }
	// RVA: 0x2c0bd9c VA: 0x7595223d9c
	private Void _SetImgStatus(Image imgPoint, Boolean isSelect, Boolean isDisable) { }
	// RVA: 0x2c0bb34 VA: 0x7595223b34
	private Void _SetPosAndSize(CrisisV2RoadPosData roadPosData) { }
	// RVA: 0x2c0be64 VA: 0x7595223e64
	public Void .ctor() { }
}
```