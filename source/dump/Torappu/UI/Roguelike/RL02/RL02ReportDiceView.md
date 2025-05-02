# RL02ReportDiceView

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `UIAtlasObject _atlasObject`

- `Text _textDiceDesc`

- `Text _textGoodResult`

- `Text _textBadResult`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `String _FormatTextFromDiceResultInfo(RL02EndingFrameDiceReportViewModel, DiceResultInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ReportDiceView : RL02CommonReportView`1
{
	private const String ENTER_ANIM_NAME; // 0x0
	private UIAtlasObject _atlasObject; // 0x58
	private DiceResultItemView[] _resultViews; // 0x60
	private DiceAtlasConfig[] _atlasConfigs; // 0x68
	private Text _textDiceDesc; // 0x70
	private Text _textGoodResult; // 0x78
	private Text _textBadResult; // 0x80
	private Boolean m_inited; // 0x88
	private Dictionary`2 m_diceAtlasConfigs; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetViewType; // 0x8
	private static DelegateBridge __Hotfix0_GetShowAnimName; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__FormatTextFromDiceResultInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2b62e04 VA: 0x759517ae04
	private Void _InitIfNot() { }
	// RVA: 0x2b6300c VA: 0x759517b00c
	public override ReportViewType GetViewType() { }
	// RVA: 0x2b63074 VA: 0x759517b074
	protected override String GetShowAnimName() { }
	// RVA: 0x2b630f0 VA: 0x759517b0f0
	protected override Void Render(RL02EndingFrameDiceReportViewModel viewModel) { }
	// RVA: 0x2b63590 VA: 0x759517b590
	private String _FormatTextFromDiceResultInfo(RL02EndingFrameDiceReportViewModel viewModel, DiceResultInfo resultInfo) { }
	// RVA: 0x2b636bc VA: 0x759517b6bc
	public Void .ctor() { }
}
```