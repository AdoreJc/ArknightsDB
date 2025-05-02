# RL02EndingFrameSanReportViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Int32 endSanValue`

- `String endSanDesc`


## Methods

- `Void _FillZoneSanInfos(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02EndingFrameSanReportViewModel : RL02EndingFrameReportViewModel
{
	private const Int32 MAX_ZONE_INFOS_SIZE; // 0x0
	public List`1 zoneSanInfos; // 0x18
	public Int32 endSanValue; // 0x20
	public String endSanDesc; // 0x28
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__FillZoneSanInfos; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override ReportViewType viewType { get; }

	// RVA: 0x2b67738 VA: 0x759517f738
	public override ReportViewType get_viewType() { }
	// RVA: 0x2b677a0 VA: 0x759517f7a0
	protected override Boolean LoadData(String topicId, RL02EndingFrameViewModel dataSource) { }
	// RVA: 0x2b67b94 VA: 0x759517fb94
	private Void _FillZoneSanInfos(List`1 zoneSanInfos) { }
	// RVA: 0x2b67fac VA: 0x759517ffac
	public Void .ctor() { }
}
```