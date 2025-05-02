# ZoneRecordRewardBuffDialog

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _outTime`

- `Text _itemName`

- `Text _itemNameEng`

- `Text _itemDesc`

- `Text _itemHowUse`

- `Text _itemHowGain`

- `UIRenderTextureImage _blurBg`

- `RectTransform _backRt`

- `Image _itemIcon`

- `Text _itemCount`


## Methods

- `Void EventOnConfirm()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordRewardBuffDialog : UICustomDialog`1
{
	private Text _outTime; // 0x40
	private Text _itemName; // 0x48
	private Text _itemNameEng; // 0x50
	private Text _itemDesc; // 0x58
	private Text _itemHowUse; // 0x60
	private Text _itemHowGain; // 0x68
	private UIRenderTextureImage _blurBg; // 0x70
	private RectTransform _backRt; // 0x78
	private Image _itemIcon; // 0x80
	private Text _itemCount; // 0x88
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x10
	private static DelegateBridge __Hotfix0_BeforeDestroy; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2fc861c VA: 0x75955e061c
	protected override Void OnInit() { }
	// RVA: 0x2fc8738 VA: 0x75955e0738
	protected override Void OnRender(Options option) { }
	// RVA: 0x2fc8bf8 VA: 0x75955e0bf8
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2fc8c60 VA: 0x75955e0c60
	protected override Void BeforeDestroy() { }
	// RVA: 0x2fc8d1c VA: 0x75955e0d1c
	public Void EventOnConfirm() { }
	// RVA: 0x2fc8da0 VA: 0x75955e0da0
	public Void .ctor() { }
}
```