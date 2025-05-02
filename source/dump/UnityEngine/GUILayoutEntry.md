# GUILayoutEntry

**Namespace:** `UnityEngine`


## Fields

- `Single minWidth`

- `Single maxWidth`

- `Single minHeight`

- `Single maxHeight`

- `Rect rect`

- `Int32 stretchWidth`

- `Int32 stretchHeight`

- `Boolean consideredForMargin`

- `GUIStyle m_Style`


## Properties

- `GUIStyle style`

- `Int32 marginHorizontal`

- `Int32 marginVertical`


## Methods

- `GUIStyle get_style()`

- `Void set_style(GUIStyle)`

- `Int32 get_marginHorizontal()`

- `Int32 get_marginVertical()`


## Dump
```C#
// Dll : UnityEngine.IMGUIModule.dll
// Namespace : UnityEngine
internal class GUILayoutEntry
{
	public Single minWidth; // 0x10
	public Single maxWidth; // 0x14
	public Single minHeight; // 0x18
	public Single maxHeight; // 0x1c
	public Rect rect; // 0x20
	public Int32 stretchWidth; // 0x30
	public Int32 stretchHeight; // 0x34
	public Boolean consideredForMargin; // 0x38
	private GUIStyle m_Style; // 0x40
	internal static Rect kDummyRect; // 0x0
	protected static Int32 indent; // 0x10

	public GUIStyle style { get; set; }
	public virtual Int32 marginLeft { get; }
	public virtual Int32 marginRight { get; }
	public virtual Int32 marginTop { get; }
	public virtual Int32 marginBottom { get; }
	public Int32 marginHorizontal { get; }
	public Int32 marginVertical { get; }

	// RVA: 0x68c44f4 VA: 0x7598edc4f4
	public GUIStyle get_style() { }
	// RVA: 0x68c44fc VA: 0x7598edc4fc
	public Void set_style(GUIStyle value) { }
	// RVA: 0x68c4530 VA: 0x7598edc530
	public virtual Int32 get_marginLeft() { }
	// RVA: 0x68c4558 VA: 0x7598edc558
	public virtual Int32 get_marginRight() { }
	// RVA: 0x68c4580 VA: 0x7598edc580
	public virtual Int32 get_marginTop() { }
	// RVA: 0x68c45a8 VA: 0x7598edc5a8
	public virtual Int32 get_marginBottom() { }
	// RVA: 0x68c45d0 VA: 0x7598edc5d0
	public Int32 get_marginHorizontal() { }
	// RVA: 0x68c460c VA: 0x7598edc60c
	public Int32 get_marginVertical() { }
	// RVA: 0x68c4648 VA: 0x7598edc648
	public Void .ctor(Single _minWidth, Single _maxWidth, Single _minHeight, Single _maxHeight, GUIStyle _style) { }
	// RVA: 0x68c4770 VA: 0x7598edc770
	public Void .ctor(Single _minWidth, Single _maxWidth, Single _minHeight, Single _maxHeight, GUIStyle _style, GUILayoutOption[] options) { }
	// RVA: 0x68c4894 VA: 0x7598edc894
	public virtual Void CalcWidth() { }
	// RVA: 0x68c4898 VA: 0x7598edc898
	public virtual Void CalcHeight() { }
	// RVA: 0x68c489c VA: 0x7598edc89c
	public virtual Void SetHorizontal(Single x, Single width) { }
	// RVA: 0x68c48d0 VA: 0x7598edc8d0
	public virtual Void SetVertical(Single y, Single height) { }
	// RVA: 0x68c4904 VA: 0x7598edc904
	protected virtual Void ApplyStyleSettings(GUIStyle style) { }
	// RVA: 0x68c4998 VA: 0x7598edc998
	public virtual Void ApplyOptions(GUILayoutOption[] options) { }
	// RVA: 0x68c4c6c VA: 0x7598edcc6c
	public override String ToString() { }
	// RVA: 0x68c5364 VA: 0x7598edd364
	private static Void .cctor() { }
}
```