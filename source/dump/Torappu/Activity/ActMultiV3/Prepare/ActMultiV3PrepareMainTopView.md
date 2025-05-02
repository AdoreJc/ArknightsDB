# ActMultiV3PrepareMainTopView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `GameObject _btnReturn`

- `GameObject _space`

- `GameObject _invertTipObj`

- `Text _pingLabel`

- `TwoStateFadeSwitcher _cdState`

- `Int32 _oneDigitFontSize`

- `Int32 _otherFontSize`

- `UIAnimationLocation _emergencyAnim`

- `Text _stageCode`

- `Text _stageName`

- `Transform _diffIconContainer`

- `ActMultiV3DifficultyIconView _diffIconPrefab`

- `Single _diffIconScale`

- `GameObjectClusterActive _hideInEntrance`

- `ActMultiV3DifficultyIconView m_diffIcon`

- `UIStateFinder m_finder`

- `ActMultiV3PrepareMainViewModelProperty m_cachedProp`

- `StepCDInfo m_cdParam`

- `Int32 m_curSecNum`


## Methods

- `Void _InitIfNot()`

- `Void UpdatePing(Int32)`

- `Void _UpdateCD()`

- `Void _SetCDNum(Int32)`

- `Void _SetCDPrg(Single)`

- `Void EventOnExit()`

- `Void EventOnReturn()`

- `Void EventOnStageDetail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainTopView : ActMultiV3PrepareMainAnimViewBase, IPingListener
{
	private GameObject _btnReturn; // 0x38
	private GameObject _space; // 0x40
	private GameObject _invertTipObj; // 0x48
	private Text _pingLabel; // 0x50
	private TwoStateFadeSwitcher _cdState; // 0x58
	private Image[] _cdPrgs; // 0x60
	private Text[] _cdNums; // 0x68
	private Int32 _oneDigitFontSize; // 0x70
	private Int32 _otherFontSize; // 0x74
	private UIAnimationLocation _emergencyAnim; // 0x78
	private Text _stageCode; // 0x88
	private Text _stageName; // 0x90
	private Transform _diffIconContainer; // 0x98
	private ActMultiV3DifficultyIconView _diffIconPrefab; // 0xa0
	private Single _diffIconScale; // 0xa8
	private GameObjectClusterActive _hideInEntrance; // 0xb0
	private ActMultiV3DifficultyIconView m_diffIcon; // 0xb8
	private UIStateFinder m_finder; // 0xc0
	private ActMultiV3PrepareMainViewModelProperty m_cachedProp; // 0xd0
	private StepCDInfo m_cdParam; // 0xd8
	private Int32 m_curSecNum; // 0xe8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_UpdatePing; // 0x10
	private static DelegateBridge __Hotfix0__UpdateCD; // 0x18
	private static DelegateBridge __Hotfix0__SetCDNum; // 0x20
	private static DelegateBridge __Hotfix0__SetCDPrg; // 0x28
	private static DelegateBridge __Hotfix0_EventOnExit; // 0x30
	private static DelegateBridge __Hotfix0_EventOnReturn; // 0x38
	private static DelegateBridge __Hotfix0_EventOnStageDetail; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3165a90 VA: 0x759577da90
	public override Void OnValueChanged(ActMultiV3PrepareMainViewModelProperty property) { }
	// RVA: 0x3165cc8 VA: 0x759577dcc8
	private Void _InitIfNot() { }
	// RVA: 0x3165de0 VA: 0x759577dde0
	public Void UpdatePing(Int32 ping) { }
	// RVA: 0x3165ee8 VA: 0x759577dee8
	private Void _UpdateCD() { }
	// RVA: 0x316632c VA: 0x759577e32c
	private Void _SetCDNum(Int32 num) { }
	// RVA: 0x3166200 VA: 0x759577e200
	private Void _SetCDPrg(Single prgValue) { }
	// RVA: 0x3166518 VA: 0x759577e518
	public Void EventOnExit() { }
	// RVA: 0x31665bc VA: 0x759577e5bc
	public Void EventOnReturn() { }
	// RVA: 0x3166660 VA: 0x759577e660
	public Void EventOnStageDetail() { }
	// RVA: 0x3166704 VA: 0x759577e704
	public Void .ctor() { }
}
```