# SiracusaMapPointInfoHolder

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaMapPointInfoView _pointInfoViewPrefab`

- `RectTransform _pointInfoContainer`

- `CanvasGroup _canvasGroup`

- `Boolean m_isInited`

- `SiracusaMapPointInfoView m_pointInfoView`

- `UISwitchTween m_fadeTween`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapPointInfoHolder : DataBinder`1
{
	private SiracusaMapPointInfoView _pointInfoViewPrefab; // 0x20
	private RectTransform _pointInfoContainer; // 0x28
	private CanvasGroup _canvasGroup; // 0x30
	private Boolean m_isInited; // 0x38
	private SiracusaMapPointInfoView m_pointInfoView; // 0x40
	private UISwitchTween m_fadeTween; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x23e2030 VA: 0x75949fa030
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x23e2184 VA: 0x75949fa184
	private Void _InitIfNot() { }
	// RVA: 0x23e22fc VA: 0x75949fa2fc
	public Void .ctor() { }
}
```