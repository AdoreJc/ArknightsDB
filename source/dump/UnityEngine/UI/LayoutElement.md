# LayoutElement

**Namespace:** `UnityEngine.UI`


## Fields

- `Boolean m_IgnoreLayout`

- `Single m_MinWidth`

- `Single m_MinHeight`

- `Single m_PreferredWidth`

- `Single m_PreferredHeight`

- `Single m_FlexibleWidth`

- `Single m_FlexibleHeight`

- `Int32 m_LayoutPriority`


## Methods

- `Void SetDirty()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class LayoutElement : UIBehaviour, ILayoutElement, ILayoutIgnorer
{
	private Boolean m_IgnoreLayout; // 0x18
	private Single m_MinWidth; // 0x1c
	private Single m_MinHeight; // 0x20
	private Single m_PreferredWidth; // 0x24
	private Single m_PreferredHeight; // 0x28
	private Single m_FlexibleWidth; // 0x2c
	private Single m_FlexibleHeight; // 0x30
	private Int32 m_LayoutPriority; // 0x34

	public virtual Boolean ignoreLayout { get; set; }
	public virtual Single minWidth { get; set; }
	public virtual Single minHeight { get; set; }
	public virtual Single preferredWidth { get; set; }
	public virtual Single preferredHeight { get; set; }
	public virtual Single flexibleWidth { get; set; }
	public virtual Single flexibleHeight { get; set; }
	public virtual Int32 layoutPriority { get; set; }

	// RVA: 0x6a5584c VA: 0x759906d84c
	public virtual Boolean get_ignoreLayout() { }
	// RVA: 0x6a55854 VA: 0x759906d854
	public virtual Void set_ignoreLayout(Boolean value) { }
	// RVA: 0x6a55980 VA: 0x759906d980
	public virtual Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x6a55984 VA: 0x759906d984
	public virtual Void CalculateLayoutInputVertical() { }
	// RVA: 0x6a55988 VA: 0x759906d988
	public virtual Single get_minWidth() { }
	// RVA: 0x6a55990 VA: 0x759906d990
	public virtual Void set_minWidth(Single value) { }
	// RVA: 0x6a55a04 VA: 0x759906da04
	public virtual Single get_minHeight() { }
	// RVA: 0x6a55a0c VA: 0x759906da0c
	public virtual Void set_minHeight(Single value) { }
	// RVA: 0x6a55a80 VA: 0x759906da80
	public virtual Single get_preferredWidth() { }
	// RVA: 0x6a55a88 VA: 0x759906da88
	public virtual Void set_preferredWidth(Single value) { }
	// RVA: 0x6a55afc VA: 0x759906dafc
	public virtual Single get_preferredHeight() { }
	// RVA: 0x6a55b04 VA: 0x759906db04
	public virtual Void set_preferredHeight(Single value) { }
	// RVA: 0x6a55b78 VA: 0x759906db78
	public virtual Single get_flexibleWidth() { }
	// RVA: 0x6a55b80 VA: 0x759906db80
	public virtual Void set_flexibleWidth(Single value) { }
	// RVA: 0x6a55bf4 VA: 0x759906dbf4
	public virtual Single get_flexibleHeight() { }
	// RVA: 0x6a55bfc VA: 0x759906dbfc
	public virtual Void set_flexibleHeight(Single value) { }
	// RVA: 0x6a55c70 VA: 0x759906dc70
	public virtual Int32 get_layoutPriority() { }
	// RVA: 0x6a55c78 VA: 0x759906dc78
	public virtual Void set_layoutPriority(Int32 value) { }
	// RVA: 0x6a55cec VA: 0x759906dcec
	protected Void .ctor() { }
	// RVA: 0x6a55d10 VA: 0x759906dd10
	protected override Void OnEnable() { }
	// RVA: 0x6a55d2c VA: 0x759906dd2c
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x6a55d30 VA: 0x759906dd30
	protected override Void OnDisable() { }
	// RVA: 0x6a55d4c VA: 0x759906dd4c
	protected override Void OnDidApplyAnimationProperties() { }
	// RVA: 0x6a55d50 VA: 0x759906dd50
	protected override Void OnBeforeTransformParentChanged() { }
	// RVA: 0x6a558c8 VA: 0x759906d8c8
	protected Void SetDirty() { }
}
```