# FifthAnnivExploreMapViewModel

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreMapRouteViewModel currentRoute`

- `Int32 currentIndexInRoute`

- `String currentNodeKey`

- `RouteCornerPos m_cornerPos`

- `Single m_lineCornerCountFactor`

- `Single m_lineMaxAmplitudeFactor`

- `FifthAnnivExploreData m_exploreData`

- `Int64 m_cachedStartTs`

- `Boolean m_isCurrentInited`

- `String m_currentStageId`

- `Int32 m_currentIndexInStage`


## Methods

- `Void LoadData(MapParam)`

- `Void UpdateData(PlayerMainlineExplore)`

- `Void ClearMapData()`

- `Void _LoadHistoryRoutes(FifthAnnivExploreData, PlayerMainlineExplore)`

- `Void _LoadCurrentRoute(FifthAnnivExploreData, PlayerMainlineExplore)`

- `Void _GeneHistoryShowNodesAndLines()`

- `Void _GeneSingleShowLineByLines(Vector2, Vector2, List`1)`

- `Vector2 _PerpendicularClockwise(Vector2)`

- `Vector2 _ConvertPointLocalToWorld(Vector2, Vector2, Vector2)`

- `Vector2 _CovertPointWorldToLocal(Vector2, Vector2, Vector2)`

- `Vector2 _ConvertCoordinates(Vector2, Vector2, Vector2, Vector2, Vector2)`

- `Void _UpdateShowNodesAndLines()`

- `Void _UpdateShowNodesAndLinesWithCurrent()`

- `FifthAnnivExploreMapRouteViewModel _CreateRouteWithSeedAndCheckpoint(FifthAnnivExploreData, PlayerExploreGameContextMapDisplay, FifthAnnivRouteType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMapViewModel : IHotfixable
{
	private const Int32 MAP_LOGIC_SIDE_LENGTH; // 0x0
	public List`1 historyRouteList; // 0x10
	public FifthAnnivExploreMapRouteViewModel currentRoute; // 0x18
	public ListDict`2 totalShowNodes; // 0x20
	public ListDict`2 totalShowLines; // 0x28
	public Int32 currentIndexInRoute; // 0x30
	public String currentNodeKey; // 0x38
	private RouteCornerPos m_cornerPos; // 0x40
	private Single m_lineCornerCountFactor; // 0x60
	private Single m_lineMaxAmplitudeFactor; // 0x64
	private FifthAnnivExploreData m_exploreData; // 0x68
	private Int64 m_cachedStartTs; // 0x70
	private Boolean m_isCurrentInited; // 0x78
	private String m_currentStageId; // 0x80
	private Int32 m_currentIndexInStage; // 0x88
	private List`1 m_historyShowNodes; // 0x90
	private List`1 m_historyShowLines; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0_ClearMapData; // 0x10
	private static DelegateBridge __Hotfix0__LoadHistoryRoutes; // 0x18
	private static DelegateBridge __Hotfix0__LoadCurrentRoute; // 0x20
	private static DelegateBridge __Hotfix0__GeneHistoryShowNodesAndLines; // 0x28
	private static DelegateBridge __Hotfix0__GeneSingleShowLineByLines; // 0x30
	private static DelegateBridge __Hotfix0__PerpendicularClockwise; // 0x38
	private static DelegateBridge __Hotfix0__ConvertPointLocalToWorld; // 0x40
	private static DelegateBridge __Hotfix0__CovertPointWorldToLocal; // 0x48
	private static DelegateBridge __Hotfix0__ConvertCoordinates; // 0x50
	private static DelegateBridge __Hotfix0__UpdateShowNodesAndLines; // 0x58
	private static DelegateBridge __Hotfix0__UpdateShowNodesAndLinesWithCurrent; // 0x60
	private static DelegateBridge __Hotfix0__CreateRouteWithSeedAndCheckpoint; // 0x68
	private static DelegateBridge __Hotfix0__GenerateEventPoints; // 0x70
	private static DelegateBridge __Hotfix0__GeneLineCornerPosList; // 0x78
	private static DelegateBridge __Hotfix0__TransformLogicPosToMapPos; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x2926434 VA: 0x7594f3e434
	public Void LoadData(MapParam param) { }
	// RVA: 0x2926fd0 VA: 0x7594f3efd0
	public Void UpdateData(PlayerMainlineExplore playerExplore) { }
	// RVA: 0x29265a4 VA: 0x7594f3e5a4
	public Void ClearMapData() { }
	// RVA: 0x2926704 VA: 0x7594f3e704
	private Void _LoadHistoryRoutes(FifthAnnivExploreData exploreData, PlayerMainlineExplore playerExplore) { }
	// RVA: 0x2926ec0 VA: 0x7594f3eec0
	private Void _LoadCurrentRoute(FifthAnnivExploreData exploreData, PlayerMainlineExplore playerExplore) { }
	// RVA: 0x29269c0 VA: 0x7594f3e9c0
	private Void _GeneHistoryShowNodesAndLines() { }
	// RVA: 0x2927cec VA: 0x7594f3fcec
	private Void _GeneSingleShowLineByLines(Vector2 startPos, Vector2 endPos, List`1 lineViewModels) { }
	// RVA: 0x2928480 VA: 0x7594f40480
	private Vector2 _PerpendicularClockwise(Vector2 vector) { }
	// RVA: 0x2928504 VA: 0x7594f40504
	private Vector2 _ConvertPointLocalToWorld(Vector2 point, Vector2 startPoint, Vector2 vector) { }
	// RVA: 0x29285dc VA: 0x7594f405dc
	private Vector2 _CovertPointWorldToLocal(Vector2 pointWorld, Vector2 targetStartPoint, Vector2 vector) { }
	// RVA: 0x292824c VA: 0x7594f4024c
	private Vector2 _ConvertCoordinates(Vector2 point, Vector2 oriLineStartPoint, Vector2 oriLineVector, Vector2 targetLineStartPoint, Vector2 targetLineVector) { }
	// RVA: 0x29270a4 VA: 0x7594f3f0a4
	private Void _UpdateShowNodesAndLines() { }
	// RVA: 0x29286b4 VA: 0x7594f406b4
	private Void _UpdateShowNodesAndLinesWithCurrent() { }
	// RVA: 0x292747c VA: 0x7594f3f47c
	private FifthAnnivExploreMapRouteViewModel _CreateRouteWithSeedAndCheckpoint(FifthAnnivExploreData exploreData, PlayerExploreGameContextMapDisplay playerPath, FifthAnnivRouteType routeType) { }
	// RVA: 0x2928aa0 VA: 0x7594f40aa0
	private List`1 _GenerateEventPoints(Vector2 startPos, Vector2 endPos, Int32 count, Random nodeRandom) { }
	// RVA: 0x2928cf8 VA: 0x7594f40cf8
	private List`1 _GeneLineCornerPosList(Vector2 startPos, Vector2 endPos, Random lineRandom) { }
	// RVA: 0x29289b4 VA: 0x7594f409b4
	private static Vector2 _TransformLogicPosToMapPos(RouteCornerPos cornerPos, Vector2 logicPos) { }
	// RVA: 0x2929184 VA: 0x7594f41184
	public Void .ctor() { }
}
```