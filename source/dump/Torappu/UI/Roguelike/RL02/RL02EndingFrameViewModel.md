# RL02EndingFrameViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Brief brief`

- `San san`

- `Mutation mutation`

- `Special special`


## Methods

- `Void ProcessViewModel()`

- `Void _TryAddViewModel(RL02EndingFrameReportViewModel)`

- `Int32 _GetViewTypeIndex(ReportViewType)`

- `ReportViewType GetPrevViewType(ReportViewType)`

- `ReportViewType GetNextViewType(ReportViewType)`

- `ReportViewType GetLastViewType()`

- `RL02EndingFrameReportViewModel GetCurrReportViewModel(ReportViewType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02EndingFrameViewModel : RoguelikeEndingFrameViewModel
{
	public Brief brief; // 0x28
	public List`1 troopChars; // 0x30
	public San san; // 0x38
	public List`1 virtue; // 0x40
	public Mutation mutation; // 0x48
	public List`1 dice; // 0x50
	public Special special; // 0x58
	private List`1 m_viewModelList; // 0x60
	private static DelegateBridge __Hotfix0_get_displayViewTypes; // 0x0
	private static DelegateBridge __Hotfix0_ProcessViewModel; // 0x8
	private static DelegateBridge __Hotfix0__TryAddViewModel; // 0x10
	private static DelegateBridge __Hotfix0__GetViewTypeIndex; // 0x18
	private static DelegateBridge __Hotfix0_GetPrevViewType; // 0x20
	private static DelegateBridge __Hotfix0_GetNextViewType; // 0x28
	private static DelegateBridge __Hotfix0_GetLastViewType; // 0x30
	private static DelegateBridge __Hotfix0_GetCurrReportViewModel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public List`1 displayViewTypes { get; }

	// RVA: 0x2b69b20 VA: 0x7595181b20
	public List`1 get_displayViewTypes() { }
	// RVA: 0x2b69ccc VA: 0x7595181ccc
	public Void ProcessViewModel() { }
	// RVA: 0x2b69e68 VA: 0x7595181e68
	private Void _TryAddViewModel(RL02EndingFrameReportViewModel viewModel) { }
	// RVA: 0x2b69f90 VA: 0x7595181f90
	private Int32 _GetViewTypeIndex(ReportViewType viewType) { }
	// RVA: 0x2b6a098 VA: 0x7595182098
	public ReportViewType GetPrevViewType(ReportViewType viewType) { }
	// RVA: 0x2b6a16c VA: 0x759518216c
	public ReportViewType GetNextViewType(ReportViewType viewType) { }
	// RVA: 0x2b6a270 VA: 0x7595182270
	public ReportViewType GetLastViewType() { }
	// RVA: 0x2b6a33c VA: 0x759518233c
	public RL02EndingFrameReportViewModel GetCurrReportViewModel(ReportViewType viewType) { }
	// RVA: 0x2b6a404 VA: 0x7595182404
	public Void .ctor() { }
}
```