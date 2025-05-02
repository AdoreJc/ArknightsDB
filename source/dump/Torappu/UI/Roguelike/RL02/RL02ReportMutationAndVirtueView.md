# RL02ReportMutationAndVirtueView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `GameObject _pnlMutation`

- `GameObject _pnlVirtue`

- `RL02ClassicEndingStatsMutationAndVirtueItemView _itemMutation`

- `Text _textMutationDesc`

- `SimpleLayoutContent _virtueGroup`

- `Boolean m_inited`

- `Adapter m_adapter`

- `RL02EndingFrameMutationAndVirtueReportViewModel m_cachedModel`


## Methods

- `Void _InitIfNot()`

- `String _BuildMutationString(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ReportMutationAndVirtueView : RL02CommonReportView`1
{
	private const String ENTER_ANIM_NAME; // 0x0
	private GameObject _pnlMutation; // 0x58
	private GameObject _pnlVirtue; // 0x60
	private RL02ClassicEndingStatsMutationAndVirtueItemView _itemMutation; // 0x68
	private Text _textMutationDesc; // 0x70
	private SimpleLayoutContent _virtueGroup; // 0x78
	private Boolean m_inited; // 0x80
	private Adapter m_adapter; // 0x88
	private RL02EndingFrameMutationAndVirtueReportViewModel m_cachedModel; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetViewType; // 0x8
	private static DelegateBridge __Hotfix0_GetShowAnimName; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__BuildMutationString; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b63c78 VA: 0x759517bc78
	private Void _InitIfNot() { }
	// RVA: 0x2b63d4c VA: 0x759517bd4c
	public override ReportViewType GetViewType() { }
	// RVA: 0x2b63db4 VA: 0x759517bdb4
	protected override String GetShowAnimName() { }
	// RVA: 0x2b63e30 VA: 0x759517be30
	protected override Void Render(RL02EndingFrameMutationAndVirtueReportViewModel viewModel) { }
	// RVA: 0x2b64044 VA: 0x759517c044
	private String _BuildMutationString(List`1 mutationCharList) { }
	// RVA: 0x2b64218 VA: 0x759517c218
	public Void .ctor() { }
}
```