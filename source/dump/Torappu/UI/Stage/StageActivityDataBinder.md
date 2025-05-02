# StageActivityDataBinder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `CanvasGroup _mapDecorCanvasGroup`

- `StageActivityLoader _activityLoader`

- `SafeParentComponent _zoneMapPluginContainer`

- `UIPageListener m_pageListener`

- `FadeSwitchTween m_mapDecorSwitch`

- `ZoneViewType m_prevType`

- `String m_prevSelectedZone`

- `Boolean m_isInited`


## Methods

- `Void _UpdateMapDecor(ZoneViewProperty)`

- `Void _UpdateActivityZoneMapPlugin(ZoneViewProperty)`

- `StageZoneMapStatePlugin _CreateActPlugin(String, StagePage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageActivityDataBinder : DataBinder`1
{
	private CanvasGroup _mapDecorCanvasGroup; // 0x20
	private StageActivityLoader _activityLoader; // 0x28
	private SafeParentComponent _zoneMapPluginContainer; // 0x30
	private UIPageListener m_pageListener; // 0x38
	private FadeSwitchTween m_mapDecorSwitch; // 0x40
	private ListDict`2 m_actZoneMapPlugins; // 0x48
	private ZoneViewType m_prevType; // 0x50
	private String m_prevSelectedZone; // 0x58
	private Boolean m_isInited; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__UpdateMapDecor; // 0x8
	private static DelegateBridge __Hotfix0__UpdateActivityZoneMapPlugin; // 0x10
	private static DelegateBridge __Hotfix0__CreateActPlugin; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f81890 VA: 0x7595599890
	public override Void OnValueChanged(ZoneViewProperty property) { }
	// RVA: 0x2f81a14 VA: 0x7595599a14
	private Void _UpdateMapDecor(ZoneViewProperty property) { }
	// RVA: 0x2f81b5c VA: 0x7595599b5c
	private Void _UpdateActivityZoneMapPlugin(ZoneViewProperty zoneProp) { }
	// RVA: 0x2f821dc VA: 0x759559a1dc
	private StageZoneMapStatePlugin _CreateActPlugin(String actId, StagePage page) { }
	// RVA: 0x2f82500 VA: 0x759559a500
	public Void .ctor() { }
}
```