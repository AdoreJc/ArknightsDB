# RL02ReportNewsView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `UIAtlasObject _atlasObject`

- `Boolean m_inited`

- `RL02EndingText m_cachedTextConfig`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ReportNewsView : RL02CommonReportView`1
{
	private const String ENTER_ANIM_NAME; // 0x0
	private NewsItemView[] _newsItemViews; // 0x58
	private UIAtlasObject _atlasObject; // 0x60
	private NewsAtlasConfig[] _atlasConfigs; // 0x68
	private Boolean m_inited; // 0x70
	private RL02EndingText m_cachedTextConfig; // 0x78
	private Dictionary`2 m_newsImageConfigs; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetViewType; // 0x8
	private static DelegateBridge __Hotfix0_GetShowAnimName; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b65f3c VA: 0x759517df3c
	private Void _InitIfNot() { }
	// RVA: 0x2b66170 VA: 0x759517e170
	public override ReportViewType GetViewType() { }
	// RVA: 0x2b661d8 VA: 0x759517e1d8
	protected override String GetShowAnimName() { }
	// RVA: 0x2b66254 VA: 0x759517e254
	protected override Void Render(RL02EndingFrameNewsReportViewModel viewModel) { }
	// RVA: 0x2b66498 VA: 0x759517e498
	public Void .ctor() { }
}
```