# Mask

**Namespace:** `UnityEngine.UI`


## Fields

- `RectTransform m_RectTransform`

- `Boolean m_ShowMaskGraphic`

- `Graphic m_Graphic`

- `Material m_MaskMaterial`

- `Material m_UnmaskMaterial`


## Properties

- `RectTransform rectTransform`

- `Boolean showMaskGraphic`

- `Graphic graphic`


## Methods

- `RectTransform get_rectTransform()`

- `Boolean get_showMaskGraphic()`

- `Void set_showMaskGraphic(Boolean)`

- `Graphic get_graphic()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Mask : UIBehaviour, ICanvasRaycastFilter, IMaterialModifier
{
	private RectTransform m_RectTransform; // 0x18
	private Boolean m_ShowMaskGraphic; // 0x20
	private Graphic m_Graphic; // 0x28
	private Material m_MaskMaterial; // 0x30
	private Material m_UnmaskMaterial; // 0x38

	public RectTransform rectTransform { get; }
	public Boolean showMaskGraphic { get; set; }
	public Graphic graphic { get; }

	// RVA: 0x6a58b38 VA: 0x7599070b38
	public RectTransform get_rectTransform() { }
	// RVA: 0x6a58ba8 VA: 0x7599070ba8
	public Boolean get_showMaskGraphic() { }
	// RVA: 0x6a58bb0 VA: 0x7599070bb0
	public Void set_showMaskGraphic(Boolean value) { }
	// RVA: 0x6a58c60 VA: 0x7599070c60
	public Graphic get_graphic() { }
	// RVA: 0x6a58cd0 VA: 0x7599070cd0
	protected Void .ctor() { }
	// RVA: 0x6a58ce0 VA: 0x7599070ce0
	public virtual Boolean MaskEnabled() { }
	// RVA: 0x6a58d70 VA: 0x7599070d70
	public virtual Void OnSiblingGraphicEnabledDisabled() { }
	// RVA: 0x6a58d74 VA: 0x7599070d74
	protected override Void OnEnable() { }
	// RVA: 0x6a59144 VA: 0x7599071144
	protected override Void OnDisable() { }
	// RVA: 0x6a59328 VA: 0x7599071328
	public virtual Boolean IsRaycastLocationValid(Vector2 sp, Camera eventCamera) { }
	// RVA: 0x6a593d4 VA: 0x75990713d4
	public virtual Material GetModifiedMaterial(Material baseMaterial) { }
}
```