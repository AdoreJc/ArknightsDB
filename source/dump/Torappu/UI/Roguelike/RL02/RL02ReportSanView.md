# RL02ReportSanView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `UIAtlasObject _atlasObject`

- `Text _sanResultDesc`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ReportSanView : RL02CommonReportView`1
{
	private const String ENTER_ANIM_NAME; // 0x0
	private UIAtlasObject _atlasObject; // 0x58
	private ZoneSanView[] _zoneSanViews; // 0x60
	private ZoneAtlasConfig[] _zoneAtlasConfigs; // 0x68
	private Text _sanResultDesc; // 0x70
	private Boolean m_inited; // 0x78
	private Dictionary`2 m_zoneAtlasConfigs; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetViewType; // 0x8
	private static DelegateBridge __Hotfix0_GetShowAnimName; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b668c8 VA: 0x759517e8c8
	private Void _InitIfNot() { }
	// RVA: 0x2b66b0c VA: 0x759517eb0c
	public override ReportViewType GetViewType() { }
	// RVA: 0x2b66b74 VA: 0x759517eb74
	protected override String GetShowAnimName() { }
	// RVA: 0x2b66bf0 VA: 0x759517ebf0
	protected override Void Render(RL02EndingFrameSanReportViewModel viewModel) { }
	// RVA: 0x2b670cc VA: 0x759517f0cc
	public Void .ctor() { }
}
```