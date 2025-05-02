# StageZoneMap

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Image _imgBkg`

- `UIPage m_registeredPage`


## Methods

- `Boolean TryAchieveStageButtonTransform(String, out)`

- `Void set_onStageSelected(Action`1)`

- `Void RenderZone(ZoneViewModel)`

- `Void _OnStageSelected(String)`

- `Void _TraceForAVG(ZoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneMap : MonoBehaviour
{
	private StageButtonOnMapHolder[] _stageButtons; // 0x18
	private Image _imgBkg; // 0x20
	private Action`1 m_onStageSelected; // 0x28
	private UIPage m_registeredPage; // 0x30

	public Action`1 onStageSelected { set; }

	// RVA: 0x2faec64 VA: 0x75955c6c64
	public Boolean TryAchieveStageButtonTransform(String stageId, out RectTransform transform) { }
	// RVA: 0x2faed60 VA: 0x75955c6d60
	public Void set_onStageSelected(Action`1 value) { }
	// RVA: 0x2faed68 VA: 0x75955c6d68
	public Void RenderZone(ZoneViewModel viewModel) { }
	// RVA: 0x2faf0e8 VA: 0x75955c70e8
	protected virtual Void Start() { }
	// RVA: 0x2faf1e4 VA: 0x75955c71e4
	protected virtual Void OnDestroy() { }
	// RVA: 0x2faf2c8 VA: 0x75955c72c8
	private Void _OnStageSelected(String stageId) { }
	// RVA: 0x2faef94 VA: 0x75955c6f94
	private Void _TraceForAVG(ZoneViewModel zoneModel) { }
	// RVA: 0x2faf2e4 VA: 0x75955c72e4
	public Void .ctor() { }
}
```