# TuningProductView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductFragSelectView _fragSelectView`

- `TuningProductOrcheSelectView _orcheSelectView`

- `TuningProductCircleView _circleView`

- `UIAnimationLocation _switchAnimLocation`

- `TuningProductSlotGroupItemView _tuningProductClosedEyeView`

- `GameObject _playBtnObj`

- `GameObject _playLock`

- `Button _playBtn`

- `GameObject _haveNewForm`

- `Color _circleColor`

- `Boolean m_isInited`

- `UIStateFinder m_stateFinder`

- `AnimationSwitchTween m_switchTween`

- `Int32 m_cachedEnterSequenceNum`

- `String m_cachedSelectFormSegmentId`

- `Int32 m_cachedSegmentNum`

- `Single m_cachedSegmentRotateSecond`


## Methods

- `Void _InitIfNot()`

- `Void _PlaySwitchTween(ProductStatus)`

- `Void _RenderSelectedFrag(TuningProductViewModel)`

- `Void _UpdateProductEyeStatus(Act29SideProductType)`

- `Void _ResetEyeStatus()`

- `Void TransToPlayState()`

- `Void TransToBagState()`

- `Void <_InitIfNot>b__22_0()`

- `Void <_InitIfNot>b__22_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductView : DataBinder`1
{
	private TuningProductFragSelectView _fragSelectView; // 0x20
	private TuningProductOrcheSelectView _orcheSelectView; // 0x28
	private TuningProductCircleView _circleView; // 0x30
	private List`1 _fragSelectedSlotItemViewList; // 0x38
	private UIAnimationLocation _switchAnimLocation; // 0x40
	private List`1 _tuningProductEyeViewList; // 0x50
	private TuningProductSlotGroupItemView _tuningProductClosedEyeView; // 0x58
	private GameObject _playBtnObj; // 0x60
	private GameObject _playLock; // 0x68
	private Button _playBtn; // 0x70
	private GameObject _haveNewForm; // 0x78
	private Color _circleColor; // 0x80
	public Action`1 onSelectOrche; // 0x90
	private Boolean m_isInited; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private AnimationSwitchTween m_switchTween; // 0xb0
	private Int32 m_cachedEnterSequenceNum; // 0xb8
	private String m_cachedSelectFormSegmentId; // 0xc0
	private Int32 m_cachedSegmentNum; // 0xc8
	private Single m_cachedSegmentRotateSecond; // 0xcc
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__PlaySwitchTween; // 0x10
	private static DelegateBridge __Hotfix0__RenderSelectedFrag; // 0x18
	private static DelegateBridge __Hotfix0__UpdateProductEyeStatus; // 0x20
	private static DelegateBridge __Hotfix0__ResetEyeStatus; // 0x28
	private static DelegateBridge __Hotfix0_TransToPlayState; // 0x30
	private static DelegateBridge __Hotfix0_TransToBagState; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x233a560 VA: 0x7594952560
	public override Void OnValueChanged(TuningProductProperty property) { }
	// RVA: 0x233a8bc VA: 0x75949528bc
	private Void _InitIfNot() { }
	// RVA: 0x233ad40 VA: 0x7594952d40
	private Void _PlaySwitchTween(ProductStatus transInStatus) { }
	// RVA: 0x233abe4 VA: 0x7594952be4
	private Void _RenderSelectedFrag(TuningProductViewModel model) { }
	// RVA: 0x233aea0 VA: 0x7594952ea0
	private Void _UpdateProductEyeStatus(Act29SideProductType transToProductType) { }
	// RVA: 0x233aab4 VA: 0x7594952ab4
	private Void _ResetEyeStatus() { }
	// RVA: 0x233b2cc VA: 0x75949532cc
	public Void TransToPlayState() { }
	// RVA: 0x233b370 VA: 0x7594953370
	public Void TransToBagState() { }
	// RVA: 0x233b414 VA: 0x7594953414
	public Void .ctor() { }
	// RVA: 0x233b4a4 VA: 0x75949534a4
	private Void <_InitIfNot>b__22_0() { }
	// RVA: 0x233b4cc VA: 0x75949534cc
	private Void <_InitIfNot>b__22_1() { }
}
```