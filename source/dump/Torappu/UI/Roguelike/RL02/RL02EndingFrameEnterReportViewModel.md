# RL02EndingFrameEnterReportViewModel

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `String nickName`

- `String endingId`

- `String endingName`

- `Boolean isSuccess`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02EndingFrameEnterReportViewModel : RL02EndingFrameReportViewModel
{
	public String nickName; // 0x18
	public String endingId; // 0x20
	public String endingName; // 0x28
	public Boolean isSuccess; // 0x30
	private static DelegateBridge __Hotfix0_get_viewType; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override ReportViewType viewType { get; }

	// RVA: 0x2b67404 VA: 0x759517f404
	public override ReportViewType get_viewType() { }
	// RVA: 0x2b6746c VA: 0x759517f46c
	protected override Boolean LoadData(String topicId, RL02EndingFrameViewModel dataSource) { }
	// RVA: 0x2b676cc VA: 0x759517f6cc
	public Void .ctor() { }
}
```