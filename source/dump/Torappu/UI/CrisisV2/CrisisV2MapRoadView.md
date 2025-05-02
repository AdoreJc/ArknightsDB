# CrisisV2MapRoadView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2MapRoad _road`

- `Color _colorNormal`

- `Color _colorSelect`

- `Single _colorTweenDuration`

- `Material _matDisableRoad`

- `Boolean m_firstRender`

- `Sequence m_sequence`


## Methods

- `Void Init(CrisisV2RoadPosData)`

- `Void Render(CrisisV2MapRoadModel, CrisisV2MapRoadStatus)`

- `Void _SetPosAndSize(CrisisV2RoadPosData)`

- `Void _PlayColorTweenIfNeed(CrisisV2MapRoadStatus, Boolean)`

- `Tween _GetColorTween(MaskableGraphic, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapRoadView : MonoBehaviour, IHotfixable
{
	private CrisisV2MapRoad _road; // 0x18
	private Color _colorNormal; // 0x20
	private Color _colorSelect; // 0x30
	private Single _colorTweenDuration; // 0x40
	private Material _matDisableRoad; // 0x48
	private const Int32 MAP_LINE_WIDTH; // 0x0
	private Boolean m_firstRender; // 0x50
	private Sequence m_sequence; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__SetPosAndSize; // 0x10
	private static DelegateBridge __Hotfix0__PlayColorTweenIfNeed; // 0x18
	private static DelegateBridge __Hotfix0__GetColorTween; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2c0bedc VA: 0x7595223edc
	public Void Init(CrisisV2RoadPosData roadPosData) { }
	// RVA: 0x2c0c03c VA: 0x759522403c
	public Void Render(CrisisV2MapRoadModel roadModel, CrisisV2MapRoadStatus roadStatus) { }
	// RVA: 0x2c0bf6c VA: 0x7595223f6c
	private Void _SetPosAndSize(CrisisV2RoadPosData roadPosData) { }
	// RVA: 0x2c0c168 VA: 0x7595224168
	private Void _PlayColorTweenIfNeed(CrisisV2MapRoadStatus roadStatus, Boolean skipTween) { }
	// RVA: 0x2c0c374 VA: 0x7595224374
	private Tween _GetColorTween(MaskableGraphic targetImg, Color targetColor) { }
	// RVA: 0x2c0c550 VA: 0x7595224550
	public Void .ctor() { }
}
```