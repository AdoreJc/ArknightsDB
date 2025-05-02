# CrisisV2MapNormalNodeView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `GameObject _normalViewGo`

- `GameObject _unknowViewGo`

- `GameObject _bgDisable`

- `GameObject _bgUnselect`

- `GameObject _bgSelect`

- `GameObject _bgExclusion`

- `GameObject _iconCompletedGo`

- `Text _textScore`

- `Image _imgRune`

- `TwoStateToggle _toggleExclusion`

- `TwoStateToggle _toggleScoreBg`

- `Color _colorRuneUnselect`

- `Color _colorRuneSelect`

- `Color _colorRuneUnreach`

- `Color _colorScoreReachable`

- `Color _colorScoreUnreach`

- `GameObject _highlightAnimGo`


## Methods

- `Void _UpdateRuneIcon(CrisisV2MapNormalNodeModel)`

- `Void <>xLuaBaseProxy_PlayHighlightAnimIfNeed(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapNormalNodeView : CrisisV2MapNodeViewBase
{
	private GameObject _normalViewGo; // 0x50
	private GameObject _unknowViewGo; // 0x58
	private GameObject _bgDisable; // 0x60
	private GameObject _bgUnselect; // 0x68
	private GameObject _bgSelect; // 0x70
	private GameObject _bgExclusion; // 0x78
	private GameObject _iconCompletedGo; // 0x80
	private Text _textScore; // 0x88
	private Image _imgRune; // 0x90
	private TwoStateToggle _toggleExclusion; // 0x98
	private TwoStateToggle _toggleScoreBg; // 0xa0
	private Color _colorRuneUnselect; // 0xa8
	private Color _colorRuneSelect; // 0xb8
	private Color _colorRuneUnreach; // 0xc8
	private Color _colorScoreReachable; // 0xd8
	private Color _colorScoreUnreach; // 0xe8
	private GameObject _highlightAnimGo; // 0xf8
	private static DelegateBridge __Hotfix0_GetSlotType; // 0x0
	private static DelegateBridge __Hotfix0_PlayHighlightAnimIfNeed; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__UpdateRuneIcon; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2c07798 VA: 0x759521f798
	public override CrisisV2NodeSlotType GetSlotType() { }
	// RVA: 0x2c07800 VA: 0x759521f800
	protected override Void PlayHighlightAnimIfNeed(Boolean isNodeHighlight) { }
	// RVA: 0x2c07884 VA: 0x759521f884
	protected override Void Render() { }
	// RVA: 0x2c07b2c VA: 0x759521fb2c
	private Void _UpdateRuneIcon(CrisisV2MapNormalNodeModel normalNodeModel) { }
	// RVA: 0x2c07c8c VA: 0x759521fc8c
	public Void .ctor() { }
	// RVA: 0x2c07cf8 VA: 0x759521fcf8
	private Void <>xLuaBaseProxy_PlayHighlightAnimIfNeed(Boolean P0) { }
}
```