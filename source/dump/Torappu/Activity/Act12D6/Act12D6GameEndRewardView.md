# Act12D6GameEndRewardView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Act12D6GameEndScoreObjView _passedZoneScoreView`

- `Act12D6GameEndScoreObjView _moveScoreView`

- `Act12D6GameEndScoreObjView _battleScoreView`

- `Act12D6GameEndScoreObjView _eliteScoreView`

- `Act12D6GameEndScoreObjView _bossScoreView`

- `Act12D6GameEndScoreObjView _relicScoreView`

- `Act12D6GameEndScoreObjView _charScoreView`

- `Image _imageModeBkg`

- `Text _textMode`

- `Text _textModeFactor`

- `Act12D6GameEndScoreObjView _totoalScoreView`

- `Text _textOutBuffTokenTotalScore`

- `Text _textOutBuffTokenFactor`

- `Act12D6GameEndScoreObjView _outBuffTokenCnt`

- `Text _textOutBuffTokenName`

- `Image _imageOutBuffTokenIcon`

- `Text _textMilestoneTokenTotalScore`

- `Text _textMilestoneTokenFactor`

- `Act12D6GameEndScoreObjView _milestoneTokenCnt`

- `Text _textMilestoneTokenName`

- `Image _imageMilestoneTokenIcon`

- `Boolean m_inited`

- `FadeSwitchTween <switchTween>k__BackingField`


## Properties

- `FadeSwitchTween switchTween`


## Methods

- `FadeSwitchTween get_switchTween()`

- `Void set_switchTween(FadeSwitchTween)`

- `Void Render(Act12D6GameEndViewModel)`

- `Void _InitIfNot()`

- `Color _GetModeBkgColor(String)`

- `Color _GetModeTextColor(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6GameEndRewardView : MonoBehaviour, IHotfixable
{
	private const String FACTOR_FORMAT; // 0x0
	private List`1 _modeColorData; // 0x18
	private Act12D6GameEndScoreObjView _passedZoneScoreView; // 0x20
	private Act12D6GameEndScoreObjView _moveScoreView; // 0x28
	private Act12D6GameEndScoreObjView _battleScoreView; // 0x30
	private Act12D6GameEndScoreObjView _eliteScoreView; // 0x38
	private Act12D6GameEndScoreObjView _bossScoreView; // 0x40
	private Act12D6GameEndScoreObjView _relicScoreView; // 0x48
	private Act12D6GameEndScoreObjView _charScoreView; // 0x50
	private Image _imageModeBkg; // 0x58
	private Text _textMode; // 0x60
	private Text _textModeFactor; // 0x68
	private Act12D6GameEndScoreObjView _totoalScoreView; // 0x70
	private Text _textOutBuffTokenTotalScore; // 0x78
	private Text _textOutBuffTokenFactor; // 0x80
	private Act12D6GameEndScoreObjView _outBuffTokenCnt; // 0x88
	private Text _textOutBuffTokenName; // 0x90
	private Image _imageOutBuffTokenIcon; // 0x98
	private Text _textMilestoneTokenTotalScore; // 0xa0
	private Text _textMilestoneTokenFactor; // 0xa8
	private Act12D6GameEndScoreObjView _milestoneTokenCnt; // 0xb0
	private Text _textMilestoneTokenName; // 0xb8
	private Image _imageMilestoneTokenIcon; // 0xc0
	private Boolean m_inited; // 0xc8
	private FadeSwitchTween <switchTween>k__BackingField; // 0xd0
	private static DelegateBridge __Hotfix0_get_switchTween; // 0x0
	private static DelegateBridge __Hotfix0_set_switchTween; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__GetModeBkgColor; // 0x20
	private static DelegateBridge __Hotfix0__GetModeTextColor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public FadeSwitchTween switchTween { get; set; }

	// RVA: 0x3473010 VA: 0x7595a8b010
	public FadeSwitchTween get_switchTween() { }
	// RVA: 0x3473078 VA: 0x7595a8b078
	private Void set_switchTween(FadeSwitchTween value) { }
	// RVA: 0x34730fc VA: 0x7595a8b0fc
	public Void Render(Act12D6GameEndViewModel viewModel) { }
	// RVA: 0x34738bc VA: 0x7595a8b8bc
	private Void _InitIfNot() { }
	// RVA: 0x3473654 VA: 0x7595a8b654
	private Color _GetModeBkgColor(String modeId) { }
	// RVA: 0x3473788 VA: 0x7595a8b788
	private Color _GetModeTextColor(String modeId) { }
	// RVA: 0x34739ac VA: 0x7595a8b9ac
	public Void .ctor() { }
}
```