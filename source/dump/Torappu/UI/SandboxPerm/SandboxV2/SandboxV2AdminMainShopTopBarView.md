# SandboxV2AdminMainShopTopBarView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _panelGold`

- `Image _imgGold`

- `Text _textGold`

- `GameObject _panelDimensionCoin`

- `Image _imgDimensionCoin`

- `Text _textDimensionCoin`

- `Text _textRefreshRemain`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainShopTopBarView : DataBinder`1, IHotfixable
{
	private GameObject _panelGold; // 0x20
	private Image _imgGold; // 0x28
	private Text _textGold; // 0x30
	private GameObject _panelDimensionCoin; // 0x38
	private Image _imgDimensionCoin; // 0x40
	private Text _textDimensionCoin; // 0x48
	private Text _textRefreshRemain; // 0x50
	private UIPage <page>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private UIPage page { get; set; }

	// RVA: 0x24eb1c0 VA: 0x7594b031c0
	private UIPage get_page() { }
	// RVA: 0x24e9f6c VA: 0x7594b01f6c
	public Void set_page(UIPage value) { }
	// RVA: 0x24eb228 VA: 0x7594b03228
	public override Void OnValueChanged(SandboxV2AdminMainShopProperty property) { }
	// RVA: 0x24eb530 VA: 0x7594b03530
	public Void .ctor() { }
}
```