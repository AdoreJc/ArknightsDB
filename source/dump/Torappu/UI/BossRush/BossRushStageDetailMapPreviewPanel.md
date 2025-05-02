# BossRushStageDetailMapPreviewPanel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `Image _imgPreview`

- `UIReentrantFloatPanel _panel`

- `Boolean m_hasInited`


## Methods

- `Void set_onMapPreviewPanelClick(Action`1)`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailMapPreviewPanel : DataBinder`1, IHotfixable
{
	private Image _imgPreview; // 0x20
	private UIReentrantFloatPanel _panel; // 0x28
	private Action`1 <onMapPreviewPanelClick>k__BackingField; // 0x30
	private Boolean m_hasInited; // 0x38
	private static DelegateBridge __Hotfix0_get_onMapPreviewPanelClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onMapPreviewPanelClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onMapPreviewPanelClick { get; set; }

	// RVA: 0x2e74848 VA: 0x759548c848
	private Action`1 get_onMapPreviewPanelClick() { }
	// RVA: 0x2e748b0 VA: 0x759548c8b0
	public Void set_onMapPreviewPanelClick(Action`1 value) { }
	// RVA: 0x2e74934 VA: 0x759548c934
	public override Void OnValueChanged(BossRushStageDetailProperty property) { }
	// RVA: 0x2e74ba8 VA: 0x759548cba8
	public Void OnClick() { }
	// RVA: 0x2e74a98 VA: 0x759548ca98
	private Void _InitIfNot() { }
	// RVA: 0x2e74c54 VA: 0x759548cc54
	public Void .ctor() { }
}
```