# CarvingSettleDialog

**Namespace:** `Torappu.UI.Carving`


## Fields

- `UIAnimationLocation _enterAnim`

- `Text _textName`

- `Text _textScore`

- `Text _textRound`

- `GameObject _panelRoundNewRecord`

- `GameObject _panelRoundReward`

- `Text _textRoundReward`

- `GameObject _panelComplete`

- `GameObject _panelUncomplete`

- `GameObject _panelFirstPass`

- `Text _textFirstPassReward`

- `Text _textMileStoneLevel`

- `Text _textMileStoneReward`

- `GameObject _panelMileStoneReward`

- `GameObject _panelMileStoneMax`

- `Slider _sliderProgress`

- `RectTransform _backRt`

- `Tween m_enterAnim`

- `String m_actId`


## Methods

- `Void EventOnClick()`

- `Void _Render(CarvingSettleViewModel)`

- `Void _GenerateEnterAnim(CarvingSettleViewModel)`

- `Tween _RenderMileStoneAndGenerateMileStoneAnim(CarvingSettleViewModel)`

- `Void _RenderMileStonePointInfo(CarvingMileStoneInfo)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnDestroySubClass()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingSettleDialog : UICompDialog`1, IHotfixable
{
	private const String MILE_STONE_PROGRESS_FORMAT; // 0x0
	private const Single MILE_STONE_ANIM_DELAY; // 0x0
	private const Single MILE_STONE_PROGRESS_ANIM_FADETIME_PER_LEVEL; // 0x0
	private const Int32 TOTAL_SCORE_ANIM_START_VALUE; // 0x0
	private const Single TOTAL_SCORE_ANIM_DELAY; // 0x0
	private const Single TOTAL_SCORE_ANIM_FADETIME; // 0x0
	private UIAnimationLocation _enterAnim; // 0x48
	private Text _textName; // 0x58
	private Text _textScore; // 0x60
	private Text _textRound; // 0x68
	private GameObject _panelRoundNewRecord; // 0x70
	private GameObject _panelRoundReward; // 0x78
	private Text _textRoundReward; // 0x80
	private GameObject _panelComplete; // 0x88
	private GameObject _panelUncomplete; // 0x90
	private GameObject _panelFirstPass; // 0x98
	private Text _textFirstPassReward; // 0xa0
	private Text _textMileStoneLevel; // 0xa8
	private Text _textMileStoneReward; // 0xb0
	private GameObject _panelMileStoneReward; // 0xb8
	private GameObject _panelMileStoneMax; // 0xc0
	private Slider _sliderProgress; // 0xc8
	private RectTransform _backRt; // 0xd0
	private Tween m_enterAnim; // 0xd8
	private String m_actId; // 0xe0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroySubClass; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge __Hotfix0__GenerateEnterAnim; // 0x28
	private static DelegateBridge __Hotfix0__RenderMileStoneAndGenerateMileStoneAnim; // 0x30
	private static DelegateBridge __Hotfix0__RenderMileStonePointInfo; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2dc0f00 VA: 0x75953d8f00
	protected override Void OnInit() { }
	// RVA: 0x2dc1018 VA: 0x75953d9018
	protected override Void OnRender(Option input) { }
	// RVA: 0x2dc15d4 VA: 0x75953d95d4
	protected override Void OnDestroySubClass() { }
	// RVA: 0x2dc1670 VA: 0x75953d9670
	public Void EventOnClick() { }
	// RVA: 0x2dc13fc VA: 0x75953d93fc
	private Void _Render(CarvingSettleViewModel viewModel) { }
	// RVA: 0x2dc17fc VA: 0x75953d97fc
	private Void _GenerateEnterAnim(CarvingSettleViewModel viewModel) { }
	// RVA: 0x2dc1c90 VA: 0x75953d9c90
	private Tween _RenderMileStoneAndGenerateMileStoneAnim(CarvingSettleViewModel viewModel) { }
	// RVA: 0x2dc2134 VA: 0x75953da134
	private Void _RenderMileStonePointInfo(CarvingMileStoneInfo info) { }
	// RVA: 0x2dc24d8 VA: 0x75953da4d8
	public Void .ctor() { }
	// RVA: 0x2dc2568 VA: 0x75953da568
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x2dc2570 VA: 0x75953da570
	private Void <>xLuaBaseProxy_OnDestroySubClass() { }
}
```