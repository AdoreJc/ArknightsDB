# RL02EndingFrameNewsReportViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Methods

- `Void _TryAddViewModel(NewsItemModel, Special)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02EndingFrameNewsReportViewModel : RL02EndingFrameReportViewModel
{
	public List`1 items; // 0x18
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__TryAddViewModel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override ReportViewType viewType { get; }

	// RVA: 0x2b69334 VA: 0x7595181334
	public override ReportViewType get_viewType() { }
	// RVA: 0x2b6939c VA: 0x759518139c
	protected override Boolean LoadData(String topicId, RL02EndingFrameViewModel dataSource) { }
	// RVA: 0x2b69604 VA: 0x7595181604
	private Void _TryAddViewModel(NewsItemModel itemModel, Special newsGroupModel) { }
	// RVA: 0x2b69758 VA: 0x7595181758
	public Void .ctor() { }
}
```