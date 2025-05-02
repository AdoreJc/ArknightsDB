# StageZoneSelectBackground

**Namespace:** `Torappu.UI.Stage`


## Fields

- `CanvasGroup _alphaHandler`

- `FadeSwitchTween m_zoneGroupSwitch`

- `ZoneViewType m_curViewType`


## Methods

- `Void _UpdateBkgStatus(ZoneViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneSelectBackground : DataBinder`1
{
	public const Single TWEEN_DURATION; // 0x0
	private CanvasGroup _alphaHandler; // 0x20
	private FadeSwitchTween m_zoneGroupSwitch; // 0x28
	private ZoneViewType m_curViewType; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__UpdateBkgStatus; // 0x8
	private static DelegateBridge __Hotfix0_CheckIfUseCommonBackground; // 0x10
	private static DelegateBridge __Hotfix0__CheckIfInstantShow; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2fbc414 VA: 0x75955d4414
	public override Void OnValueChanged(ZoneViewProperty property) { }
	// RVA: 0x2fbc494 VA: 0x75955d4494
	private Void _UpdateBkgStatus(ZoneViewProperty property) { }
	// RVA: 0x2fbc638 VA: 0x75955d4638
	public static Boolean CheckIfUseCommonBackground(ZoneViewProperty property) { }
	// RVA: 0x2fbc6c8 VA: 0x75955d46c8
	private static Boolean _CheckIfInstantShow(ZoneViewType prevType, ZoneViewType curType) { }
	// RVA: 0x2fbc748 VA: 0x75955d4748
	public Void .ctor() { }
}
```