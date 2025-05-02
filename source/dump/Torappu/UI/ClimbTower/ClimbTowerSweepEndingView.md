# ClimbTowerSweepEndingView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textTowerName`

- `Text _textTowerSubName`

- `Text _textFinishTime`

- `Image _imgTowerIcon`

- `Text _textFloorCurr`

- `Text _textFloorTarget`

- `GameObject _imgHard`

- `Color _colorHard`

- `Color _colorNormal`

- `Color _colorTowerIconHard`

- `Color _colorTowerIconNormal`

- `Image _iconLowerItem`

- `Image _iconHigherItem`

- `Text _textLowerItemName`

- `Text _textHigherItemName`

- `UISingleValueChangeBar _barLowerItem`

- `UISingleValueChangeBar _barHigherItem`

- `GameObject _iconLowerItemMax`

- `GameObject _iconHigherItemMax`

- `Text _textLowerItemGain`

- `Text _textHigherItemGain`

- `CanvasGroup _canvasLowerItemGain`

- `CanvasGroup _canvasHigherItemGain`

- `Boolean m_isLowerItemMax`

- `Boolean m_isHigherItemMax`

- `UIStateFinder m_stateFinder`

- `Boolean m_animPlayed`

- `Sequence m_sequence`


## Methods

- `Void _PlayTween()`

- `Void OnCloseSweepEndingState()`

- `Void <_PlayTween>b__33_0()`

- `Void <_PlayTween>b__33_3()`

- `Void <_PlayTween>b__33_1()`

- `Void <_PlayTween>b__33_4()`

- `Void <_PlayTween>b__33_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSweepEndingView : DataBinder`1
{
	private const String FLOOR_TARGET_FORMAT; // 0x0
	private const String ITEM_GAIN_COUNT_FORMAT; // 0x0
	private static readonly Color ITEM_GAIN_TEXT_DEFAULT_COLOR; // 0x0
	private static readonly Color ITEM_GAIN_TEXT_ZERO_COLOR; // 0x10
	private Text _textTowerName; // 0x20
	private Text _textTowerSubName; // 0x28
	private Text _textFinishTime; // 0x30
	private Image _imgTowerIcon; // 0x38
	private Text _textFloorCurr; // 0x40
	private Text _textFloorTarget; // 0x48
	private GameObject _imgHard; // 0x50
	private Color _colorHard; // 0x58
	private Color _colorNormal; // 0x68
	private Color _colorTowerIconHard; // 0x78
	private Color _colorTowerIconNormal; // 0x88
	private Image _iconLowerItem; // 0x98
	private Image _iconHigherItem; // 0xa0
	private Text _textLowerItemName; // 0xa8
	private Text _textHigherItemName; // 0xb0
	private UISingleValueChangeBar _barLowerItem; // 0xb8
	private UISingleValueChangeBar _barHigherItem; // 0xc0
	private GameObject _iconLowerItemMax; // 0xc8
	private GameObject _iconHigherItemMax; // 0xd0
	private Text _textLowerItemGain; // 0xd8
	private Text _textHigherItemGain; // 0xe0
	private CanvasGroup _canvasLowerItemGain; // 0xe8
	private CanvasGroup _canvasHigherItemGain; // 0xf0
	private Boolean m_isLowerItemMax; // 0xf8
	private Boolean m_isHigherItemMax; // 0xf9
	private UIStateFinder m_stateFinder; // 0x100
	private Boolean m_animPlayed; // 0x110
	private Sequence m_sequence; // 0x118
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__PlayTween; // 0x28
	private static DelegateBridge __Hotfix0_OnCloseSweepEndingState; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2cd3ea0 VA: 0x75952ebea0
	public override Void OnValueChanged(ClimbTowerSweepEndingProperty property) { }
	// RVA: 0x2cd4484 VA: 0x75952ec484
	private Void _PlayTween() { }
	// RVA: 0x2cd46f8 VA: 0x75952ec6f8
	public Void OnCloseSweepEndingState() { }
	// RVA: 0x2cd47b4 VA: 0x75952ec7b4
	public Void .ctor() { }
	// RVA: 0x2cd4854 VA: 0x75952ec854
	private static Void .cctor() { }
	// RVA: 0x2cd48b8 VA: 0x75952ec8b8
	private Void <_PlayTween>b__33_0() { }
	// RVA: 0x2cd4944 VA: 0x75952ec944
	private Void <_PlayTween>b__33_3() { }
	// RVA: 0x2cd4958 VA: 0x75952ec958
	private Void <_PlayTween>b__33_1() { }
	// RVA: 0x2cd49e4 VA: 0x75952ec9e4
	private Void <_PlayTween>b__33_4() { }
	// RVA: 0x2cd49f8 VA: 0x75952ec9f8
	private Void <_PlayTween>b__33_2() { }
}
```