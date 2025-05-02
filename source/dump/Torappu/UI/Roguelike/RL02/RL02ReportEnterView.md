# RL02ReportEnterView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `Text _txtName`

- `Text _txtEnding`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ReportEnterView : RL02CommonReportView`1
{
	private const String ENTER_ANIM_NAME; // 0x0
	private Text _txtName; // 0x58
	private Text _txtEnding; // 0x60
	private static DelegateBridge __Hotfix0_GetViewType; // 0x0
	private static DelegateBridge __Hotfix0_GetShowAnimName; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b63810 VA: 0x759517b810
	public override ReportViewType GetViewType() { }
	// RVA: 0x2b63878 VA: 0x759517b878
	protected override String GetShowAnimName() { }
	// RVA: 0x2b638f4 VA: 0x759517b8f4
	protected override Void Render(RL02EndingFrameEnterReportViewModel viewModel) { }
	// RVA: 0x2b639fc VA: 0x759517b9fc
	public Void .ctor() { }
}
```