# ZoneRecordMissionDialog

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIRenderTextureImage _blurBg`

- `Text _missionDesc`

- `RectTransform _backRt`


## Methods

- `Void EventOnConfirm()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordMissionDialog : UICustomDialog`1
{
	private UIRenderTextureImage _blurBg; // 0x40
	private Text _missionDesc; // 0x48
	private RectTransform _backRt; // 0x50
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x10
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2fc7d24 VA: 0x75955dfd24
	protected override Void OnInit() { }
	// RVA: 0x2fc7e40 VA: 0x75955dfe40
	protected override Void OnRender(Options options) { }
	// RVA: 0x2fc7ed4 VA: 0x75955dfed4
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2fc7f3c VA: 0x75955dff3c
	public Void EventOnConfirm() { }
	// RVA: 0x2fc7fc0 VA: 0x75955dffc0
	public Void .ctor() { }
}
```