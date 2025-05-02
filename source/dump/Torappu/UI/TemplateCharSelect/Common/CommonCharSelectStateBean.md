# CommonCharSelectStateBean

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `InputParam m_param`

- `TemplateCharSelectMainProperty m_property`

- `CommonCharSelectCustomization m_custom`


## Properties

- `TemplateCharSelectMainProperty property`

- `InputParam inputParam`

- `CommonCharSelectCustomization customization`


## Methods

- `TemplateCharSelectMainProperty get_property()`

- `Void SetInputData(InputParam)`

- `Void SetCustom(CommonCharSelectCustomization)`

- `InputParam get_inputParam()`

- `CommonCharSelectCustomization get_customization()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectStateBean : IStateBean, IHotfixable
{
	private InputParam m_param; // 0x10
	private TemplateCharSelectMainProperty m_property; // 0x18
	public CommonCharSelectCustomization m_custom; // 0x20
	private static DelegateBridge __Hotfix0_get_property; // 0x0
	private static DelegateBridge __Hotfix0_SetInputData; // 0x8
	private static DelegateBridge __Hotfix0_SetCustom; // 0x10
	private static DelegateBridge __Hotfix0_get_inputParam; // 0x18
	private static DelegateBridge __Hotfix0_get_customization; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public TemplateCharSelectMainProperty property { get; }
	public InputParam inputParam { get; }
	public CommonCharSelectCustomization customization { get; }

	// RVA: 0x2c4f8f8 VA: 0x75952678f8
	public TemplateCharSelectMainProperty get_property() { }
	// RVA: 0x2c51370 VA: 0x7595269370
	public Void SetInputData(InputParam inputParam) { }
	// RVA: 0x2c513f4 VA: 0x75952693f4
	public Void SetCustom(CommonCharSelectCustomization custom) { }
	// RVA: 0x2c503a0 VA: 0x75952683a0
	public InputParam get_inputParam() { }
	// RVA: 0x2c4ff64 VA: 0x7595267f64
	public CommonCharSelectCustomization get_customization() { }
	// RVA: 0x2c51010 VA: 0x7595269010
	public Void .ctor() { }
}
```