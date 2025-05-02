# TuningPlayView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductPagerView _orchePagerView`

- `CanvasGroup _orcheListGroup`

- `Single _canSelectAlpha`

- `Single _cannotSelectAlpha`

- `Single _hiddenAlpha`

- `Single _orcheListFadeDuration`

- `TuningProductCircleView _circleView`

- `Color _circleColor`

- `Image _tintImg`

- `UIStateFinder m_stateFinder`

- `Boolean m_isInited`

- `Int32 m_cachedEyeShowSequenceNum`

- `Int32 m_cachedEnterSequenceNum`

- `String m_cachedSelectFormSegmentId`

- `Int32 m_cachedSegmentNum`

- `Single m_cachedSegmentRotateSecond`

- `SelectOrcheStatus m_cachedStatus`

- `Tween m_orcheListFadeTween`


## Methods

- `Void _RenderCircle(TuningPlayViewModel)`

- `Void _RenderEye(TuningPlayViewModel)`

- `Void _ResetEye()`

- `Void _SetOrcheListDisplayType(SelectOrcheStatus)`

- `Void _InitIfNot()`

- `Void OnClickBackToProductState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningPlayView : DataBinder`1
{
	private TuningProductPagerView _orchePagerView; // 0x20
	private CanvasGroup _orcheListGroup; // 0x28
	private Single _canSelectAlpha; // 0x30
	private Single _cannotSelectAlpha; // 0x34
	private Single _hiddenAlpha; // 0x38
	private Single _orcheListFadeDuration; // 0x3c
	private List`1 _orcheIdToFormEffectViewList; // 0x40
	private TuningProductCircleView _circleView; // 0x48
	private Color _circleColor; // 0x50
	private List`1 _tuningProductEyeViewList; // 0x60
	private Image _tintImg; // 0x68
	public Action`1 onSelectOrche; // 0x70
	private UIStateFinder m_stateFinder; // 0x78
	private Boolean m_isInited; // 0x88
	private Int32 m_cachedEyeShowSequenceNum; // 0x8c
	private Int32 m_cachedEnterSequenceNum; // 0x90
	private String m_cachedSelectFormSegmentId; // 0x98
	private Int32 m_cachedSegmentNum; // 0xa0
	private Single m_cachedSegmentRotateSecond; // 0xa4
	private SelectOrcheStatus m_cachedStatus; // 0xa8
	private Tween m_orcheListFadeTween; // 0xb0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderCircle; // 0x8
	private static DelegateBridge __Hotfix0__RenderEye; // 0x10
	private static DelegateBridge __Hotfix0__ResetEye; // 0x18
	private static DelegateBridge __Hotfix0__SetOrcheListDisplayType; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_OnClickBackToProductState; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2331448 VA: 0x7594949448
	public override Void OnValueChanged(TuningPlayProperty property) { }
	// RVA: 0x2331a84 VA: 0x7594949a84
	private Void _RenderCircle(TuningPlayViewModel model) { }
	// RVA: 0x2331d34 VA: 0x7594949d34
	private Void _RenderEye(TuningPlayViewModel model) { }
	// RVA: 0x233170c VA: 0x759494970c
	private Void _ResetEye() { }
	// RVA: 0x2331e94 VA: 0x7594949e94
	private Void _SetOrcheListDisplayType(SelectOrcheStatus status) { }
	// RVA: 0x23315e8 VA: 0x75949495e8
	private Void _InitIfNot() { }
	// RVA: 0x233274c VA: 0x759494a74c
	public Void OnClickBackToProductState() { }
	// RVA: 0x23327f0 VA: 0x759494a7f0
	public Void .ctor() { }
}
```