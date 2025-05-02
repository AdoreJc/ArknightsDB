# StageMainlineZoneGroupView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneLockedView _lockedViewPrefab`

- `ScrollRect _focusScroll`

- `StageZoneLockedView m_lockedZoneView`

- `String m_focusZoneCache`

- `Boolean m_zoneLock`


## Methods

- `Void _OnZoneClicked(String)`

- `Void _TriggerZoneClickedEvent(ZoneViewModel)`

- `Void _InitZones()`

- `IEnumerator _InitialFocusCoroutine(String)`

- `Single _FocusZone(String, Boolean)`

- `Tween _ScrollToFocusRect(RectTransform, Boolean, out)`

- `Void <_FocusZone>b__14_0()`

- `Single <_ScrollToFocusRect>b__15_0()`

- `Void <_ScrollToFocusRect>b__15_1(Single)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnUpdate(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMainlineZoneGroupView : StageZoneGroupView
{
	private const Single TWEEN_TIME_UNIT; // 0x0
	private StageZoneLockedView _lockedViewPrefab; // 0x70
	private ScrollRect _focusScroll; // 0x78
	private StageZoneLockedView m_lockedZoneView; // 0x80
	private String m_focusZoneCache; // 0x88
	private Boolean m_zoneLock; // 0x90
	private static DelegateBridge __Hotfix0_get_showLockedZones; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x10
	private static DelegateBridge __Hotfix0__OnZoneClicked; // 0x18
	private static DelegateBridge __Hotfix0__TriggerZoneClickedEvent; // 0x20
	private static DelegateBridge __Hotfix0__InitZones; // 0x28
	private static DelegateBridge __Hotfix0__InitialFocusCoroutine; // 0x30
	private static DelegateBridge __Hotfix0__FocusZone; // 0x38
	private static DelegateBridge __Hotfix0__ScrollToFocusRect; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected override Boolean showLockedZones { get; }

	// RVA: 0x2fa56e0 VA: 0x75955bd6e0
	protected override Boolean get_showLockedZones() { }
	// RVA: 0x2fa5744 VA: 0x75955bd744
	protected override Void OnInit() { }
	// RVA: 0x2fa5cb8 VA: 0x75955bdcb8
	protected override Void OnUpdate(Boolean isActive) { }
	// RVA: 0x2fa5fec VA: 0x75955bdfec
	private Void _OnZoneClicked(String zoneId) { }
	// RVA: 0x2fa6208 VA: 0x75955be208
	private Void _TriggerZoneClickedEvent(ZoneViewModel zoneModel) { }
	// RVA: 0x2fa59dc VA: 0x75955bd9dc
	private Void _InitZones() { }
	// RVA: 0x2fa6444 VA: 0x75955be444
	private IEnumerator _InitialFocusCoroutine(String zoneId) { }
	// RVA: 0x2fa5e1c VA: 0x75955bde1c
	private Single _FocusZone(String zoneId, Boolean tweenTo) { }
	// RVA: 0x2fa65a4 VA: 0x75955be5a4
	private Tween _ScrollToFocusRect(RectTransform zoneTrans, Boolean useTween, out Single time) { }
	// RVA: 0x2fa68ec VA: 0x75955be8ec
	public Void .ctor() { }
	// RVA: 0x2fa6a3c VA: 0x75955bea3c
	private Void <_FocusZone>b__14_0() { }
	// RVA: 0x2fa6a44 VA: 0x75955bea44
	private Single <_ScrollToFocusRect>b__15_0() { }
	// RVA: 0x2fa6a60 VA: 0x75955bea60
	private Void <_ScrollToFocusRect>b__15_1(Single val) { }
	// RVA: 0x2fa6a7c VA: 0x75955bea7c
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x2fa6a80 VA: 0x75955bea80
	private Void <>xLuaBaseProxy_OnUpdate(Boolean P0) { }
}
```