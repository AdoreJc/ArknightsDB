# SideStoryMapDecroLoader

**Namespace:** `Torappu.UI.Stage`


## Fields

- `SideStoryMapDecroTrailInfo _trailInfo`

- `SideStoryMapDecroTrailInfo m_trailInfo`

- `Boolean m_isInited`

- `StageSideStoryMapDecroViewBase m_decroView`

- `MainMapDecroView m_mainDecroView`

- `String m_decroRetroId`

- `String m_mainZoneId`


## Methods

- `Void _InitIfNot()`

- `Void RenderSelectZone(ZoneViewModel)`

- `Void _RenderMain(ZoneViewModel)`

- `Void _RenderRetro(ZoneViewModel)`

- `StageSideStoryMapDecroViewBase _GetView(String)`

- `MainMapDecroView _GetMainView(String)`

- `Void _RenderRetroDecroView(String, ZoneViewModel, List`1)`

- `Void _RenderTrail(String)`

- `Void _GetZonesForRetro(String, List`1)`

- `Boolean _FocusToZone(String)`

- `String _GetCurrentSelectedZone()`

- `Void _ExitCurrentRetro()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SideStoryMapDecroLoader : PageSingleComponent, IHotfixable
{
	private SideStoryMapDecroTrailInfo _trailInfo; // 0x20
	private SideStoryMapDecroTrailInfo m_trailInfo; // 0x28
	private Boolean m_isInited; // 0x30
	private StageSideStoryMapDecroViewBase m_decroView; // 0x38
	private MainMapDecroView m_mainDecroView; // 0x40
	private String m_decroRetroId; // 0x48
	private String m_mainZoneId; // 0x50
	private List`1 m_sideStoryZones; // 0x58
	private List`1 m_curRetroZones; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderSelectZone; // 0x8
	private static DelegateBridge __Hotfix0__RenderMain; // 0x10
	private static DelegateBridge __Hotfix0__RenderRetro; // 0x18
	private static DelegateBridge __Hotfix0__GetView; // 0x20
	private static DelegateBridge __Hotfix0__GetMainView; // 0x28
	private static DelegateBridge __Hotfix0__RenderRetroDecroView; // 0x30
	private static DelegateBridge __Hotfix0__RenderTrail; // 0x38
	private static DelegateBridge __Hotfix0__CheckInst; // 0x40
	private static DelegateBridge __Hotfix0_RegisterSideStoryZones; // 0x48
	private static DelegateBridge __Hotfix0__CheckIfRetroZone; // 0x50
	private static DelegateBridge __Hotfix0__GetZonesForRetro; // 0x58
	private static DelegateBridge __Hotfix0__FocusToZone; // 0x60
	private static DelegateBridge __Hotfix0__GetCurrentSelectedZone; // 0x68
	private static DelegateBridge __Hotfix0__ExitCurrentRetro; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2f15aa8 VA: 0x759552daa8
	private Void _InitIfNot() { }
	// RVA: 0x2f15968 VA: 0x759552d968
	public Void RenderSelectZone(ZoneViewModel zoneViewModel) { }
	// RVA: 0x2f15b1c VA: 0x759552db1c
	private Void _RenderMain(ZoneViewModel zoneViewModel) { }
	// RVA: 0x2f15e10 VA: 0x759552de10
	private Void _RenderRetro(ZoneViewModel zoneViewModel) { }
	// RVA: 0x2f167b0 VA: 0x759552e7b0
	private StageSideStoryMapDecroViewBase _GetView(String id) { }
	// RVA: 0x2f15fb0 VA: 0x759552dfb0
	private MainMapDecroView _GetMainView(String id) { }
	// RVA: 0x2f164e0 VA: 0x759552e4e0
	private Void _RenderRetroDecroView(String retroId, ZoneViewModel curZone, List`1 curRetroZones) { }
	// RVA: 0x2f16300 VA: 0x759552e300
	private Void _RenderTrail(String retroId) { }
	// RVA: 0x2f16ad8 VA: 0x759552ead8
	private static SideStoryMapDecroLoader _CheckInst(Interface pageInterface) { }
	// RVA: 0x2f16bac VA: 0x759552ebac
	public static Void RegisterSideStoryZones(Interface page, ListDict`2 zones) { }
	// RVA: 0x2f1606c VA: 0x759552e06c
	private static Boolean _CheckIfRetroZone(ZoneViewModel zoneModel) { }
	// RVA: 0x2f1610c VA: 0x759552e10c
	private Void _GetZonesForRetro(String retroId, List`1 outputList) { }
	// RVA: 0x2f16e20 VA: 0x759552ee20
	private Boolean _FocusToZone(String zoneId) { }
	// RVA: 0x2f16f50 VA: 0x759552ef50
	private String _GetCurrentSelectedZone() { }
	// RVA: 0x2f170a0 VA: 0x759552f0a0
	private Void _ExitCurrentRetro() { }
	// RVA: 0x2f171c8 VA: 0x759552f1c8
	public Void .ctor() { }
}
```