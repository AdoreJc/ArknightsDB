# Act1LockMapView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `RectTransform _normalFocusBound`

- `RectTransform _interlockFocusBound`

- `Image _imgBkg`

- `RectTransform _btnContainer`

- `Act1LockPointView _milestonePointView`

- `Image _bkgDayMask`

- `Image _bkgSunsetMask`

- `Act1LockStageBtn _normalStageObj`

- `Act1LockStageBtn _lockStageObj`

- `Act1LockStageBtn _ultimateStageObj`

- `Color _interLockedColor`

- `Color _interNormalColor`

- `Act1LockZoneMapViewModel m_cachedZoneViewModel`

- `Act1LockStageBtn m_cachedSelectedBtn`

- `Tween m_tweenBkg`

- `Tween m_tweenBtn`

- `Single m_positionValue`

- `Single m_initValue`

- `Act1LockStageBtn m_cachedGuideInterlockBtn`

- `Act1LockStageBtn m_cachedGuideFinalBtn`

- `Boolean m_inited`


## Methods

- `Void RenderMap(Act1LockZoneMapViewModel)`

- `Void _RenderStagesFirstTime(Act1LockZoneMapViewModel)`

- `Void _RefreshStages(Act1LockZoneMapViewModel)`

- `Void _TryFocusStage(Act1LockStageBtnHolder, InterlockStageType)`

- `Void _RenderBkg()`

- `Void _InitPos()`

- `Void _ApplyToPos(RectTransform, RectTransform)`

- `Void _FocusToValue(Single)`

- `Void _TryResetFocus()`

- `Void _TryTriggerUnlockToast(Boolean, Boolean)`

- `Void _TraceMapAVG()`

- `Void _InitIfNot()`

- `Single <_FocusToValue>b__32_0()`

- `Void <_FocusToValue>b__32_1(Single)`

- `Single <_FocusToValue>b__32_2()`

- `Void <_FocusToValue>b__32_3(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockMapView : MonoBehaviour, IHotfixable
{
	private RectTransform _normalFocusBound; // 0x18
	private RectTransform _interlockFocusBound; // 0x20
	private Image _imgBkg; // 0x28
	private RectTransform _btnContainer; // 0x30
	private Act1LockPointView _milestonePointView; // 0x38
	private Image _bkgDayMask; // 0x40
	private Image _bkgSunsetMask; // 0x48
	private Act1LockStageBtn _normalStageObj; // 0x50
	private Act1LockStageBtn _lockStageObj; // 0x58
	private Act1LockStageBtn _ultimateStageObj; // 0x60
	private Act1LockStageBtnHolder[] _stageBtnHolders; // 0x68
	private Act1LockStageLine[] _stageLines; // 0x70
	private Color _interLockedColor; // 0x78
	private Color _interNormalColor; // 0x88
	public Action`1 onStageClickEvent; // 0x98
	private const Int32 FIRST_INTERLOCK_STAGE_SORTID; // 0x0
	private Act1LockZoneMapViewModel m_cachedZoneViewModel; // 0xa0
	private Act1LockStageBtn m_cachedSelectedBtn; // 0xa8
	private Tween m_tweenBkg; // 0xb0
	private Tween m_tweenBtn; // 0xb8
	private Single m_positionValue; // 0xc0
	private Single m_initValue; // 0xc4
	private Act1LockStageBtn m_cachedGuideInterlockBtn; // 0xc8
	private Act1LockStageBtn m_cachedGuideFinalBtn; // 0xd0
	private Boolean m_inited; // 0xd8
	private static DelegateBridge __Hotfix0_RenderMap; // 0x0
	private static DelegateBridge __Hotfix0__RenderStagesFirstTime; // 0x8
	private static DelegateBridge __Hotfix0__RefreshStages; // 0x10
	private static DelegateBridge __Hotfix0__TryFocusStage; // 0x18
	private static DelegateBridge __Hotfix0__RenderBkg; // 0x20
	private static DelegateBridge __Hotfix0__InitPos; // 0x28
	private static DelegateBridge __Hotfix0__ApplyToPos; // 0x30
	private static DelegateBridge __Hotfix0__FocusToValue; // 0x38
	private static DelegateBridge __Hotfix0__TryResetFocus; // 0x40
	private static DelegateBridge __Hotfix0__TryTriggerUnlockToast; // 0x48
	private static DelegateBridge __Hotfix0__TraceMapAVG; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x33ce1e4 VA: 0x75959e61e4
	public Void RenderMap(Act1LockZoneMapViewModel mapViewModel) { }
	// RVA: 0x33ce314 VA: 0x75959e6314
	private Void _RenderStagesFirstTime(Act1LockZoneMapViewModel mapViewModel) { }
	// RVA: 0x33ce7dc VA: 0x75959e67dc
	private Void _RefreshStages(Act1LockZoneMapViewModel mapViewModel) { }
	// RVA: 0x33cf49c VA: 0x75959e749c
	private Void _TryFocusStage(Act1LockStageBtnHolder btnHolder, InterlockStageType stageType) { }
	// RVA: 0x33cecf8 VA: 0x75959e6cf8
	private Void _RenderBkg() { }
	// RVA: 0x33cfe54 VA: 0x75959e7e54
	private Void _InitPos() { }
	// RVA: 0x33cfa30 VA: 0x75959e7a30
	private Void _ApplyToPos(RectTransform buttonTrans, RectTransform _focusBound) { }
	// RVA: 0x33cfc1c VA: 0x75959e7c1c
	private Void _FocusToValue(Single targetPos) { }
	// RVA: 0x33cf9a0 VA: 0x75959e79a0
	private Void _TryResetFocus() { }
	// RVA: 0x33cedbc VA: 0x75959e6dbc
	private Void _TryTriggerUnlockToast(Boolean isFinalFirst, Boolean isInterlockFirst) { }
	// RVA: 0x33ceac0 VA: 0x75959e6ac0
	private Void _TraceMapAVG() { }
	// RVA: 0x33cec68 VA: 0x75959e6c68
	private Void _InitIfNot() { }
	// RVA: 0x33cfedc VA: 0x75959e7edc
	public Void .ctor() { }
	// RVA: 0x33cff64 VA: 0x75959e7f64
	private Single <_FocusToValue>b__32_0() { }
	// RVA: 0x33cff6c VA: 0x75959e7f6c
	private Void <_FocusToValue>b__32_1(Single val) { }
	// RVA: 0x33cffd0 VA: 0x75959e7fd0
	private Single <_FocusToValue>b__32_2() { }
	// RVA: 0x33cffd8 VA: 0x75959e7fd8
	private Void <_FocusToValue>b__32_3(Single val) { }
}
```