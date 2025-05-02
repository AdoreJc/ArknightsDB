# SiracusaMapSmallMapView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `UIAnimationLocation _showAnim`

- `Boolean m_hasInited`

- `Boolean m_hasValueChangedInited`

- `Boolean m_cachedIsSmallMapMode`

- `AnimationSwitchTween m_showSwitchTween`

- `UIPageListener m_pageListener`


## Methods

- `Void DoInit()`

- `Void _InitIfNot()`

- `Void _InitOnValueChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapSmallMapView : SiracusaMapViewBase`1
{
	private Canvas[] _canvases; // 0x88
	private UIAnimationLocation _showAnim; // 0x90
	private Boolean m_hasInited; // 0xa0
	private Boolean m_hasValueChangedInited; // 0xa1
	private Boolean m_cachedIsSmallMapMode; // 0xa2
	private AnimationSwitchTween m_showSwitchTween; // 0xa8
	private UIPageListener m_pageListener; // 0xb0
	private static DelegateBridge __Hotfix0_DoInit; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__InitOnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x241387c VA: 0x7594a2b87c
	public Void DoInit() { }
	// RVA: 0x2413da4 VA: 0x7594a2bda4
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x24138e4 VA: 0x7594a2b8e4
	private Void _InitIfNot() { }
	// RVA: 0x241415c VA: 0x7594a2c15c
	private Void _InitOnValueChanged() { }
	// RVA: 0x24142c0 VA: 0x7594a2c2c0
	public Void .ctor() { }
}
```