# GUILayoutGroup

**Namespace:** `UnityEngine`


## Fields

- `Boolean isVertical`

- `Boolean resetCoords`

- `Single spacing`

- `Boolean sameSize`

- `Boolean isWindow`

- `Int32 windowID`

- `Int32 m_Cursor`

- `Int32 m_StretchableCountX`

- `Int32 m_StretchableCountY`

- `Boolean m_UserSpecifiedWidth`

- `Boolean m_UserSpecifiedHeight`

- `Single m_ChildMinWidth`

- `Single m_ChildMaxWidth`

- `Single m_ChildMinHeight`

- `Single m_ChildMaxHeight`

- `Int32 m_MarginLeft`

- `Int32 m_MarginRight`

- `Int32 m_MarginTop`

- `Int32 m_MarginBottom`


## Methods

- `Void ResetCursor()`

- `GUILayoutEntry GetNext()`

- `Void Add(GUILayoutEntry)`


## Dump
```C#
// Dll : UnityEngine.IMGUIModule.dll
// Namespace : UnityEngine
internal class GUILayoutGroup : GUILayoutEntry
{
	public List`1 entries; // 0x48
	public Boolean isVertical; // 0x50
	public Boolean resetCoords; // 0x51
	public Single spacing; // 0x54
	public Boolean sameSize; // 0x58
	public Boolean isWindow; // 0x59
	public Int32 windowID; // 0x5c
	private Int32 m_Cursor; // 0x60
	protected Int32 m_StretchableCountX; // 0x64
	protected Int32 m_StretchableCountY; // 0x68
	protected Boolean m_UserSpecifiedWidth; // 0x6c
	protected Boolean m_UserSpecifiedHeight; // 0x6d
	protected Single m_ChildMinWidth; // 0x70
	protected Single m_ChildMaxWidth; // 0x74
	protected Single m_ChildMinHeight; // 0x78
	protected Single m_ChildMaxHeight; // 0x7c
	protected Int32 m_MarginLeft; // 0x80
	protected Int32 m_MarginRight; // 0x84
	protected Int32 m_MarginTop; // 0x88
	protected Int32 m_MarginBottom; // 0x8c
	private static readonly GUILayoutEntry none; // 0x0

	public override Int32 marginLeft { get; }
	public override Int32 marginRight { get; }
	public override Int32 marginTop { get; }
	public override Int32 marginBottom { get; }

	// RVA: 0x68c5fb8 VA: 0x7598eddfb8
	public override Int32 get_marginLeft() { }
	// RVA: 0x68c5fc0 VA: 0x7598eddfc0
	public override Int32 get_marginRight() { }
	// RVA: 0x68c5fc8 VA: 0x7598eddfc8
	public override Int32 get_marginTop() { }
	// RVA: 0x68c5fd0 VA: 0x7598eddfd0
	public override Int32 get_marginBottom() { }
	// RVA: 0x68c5fd8 VA: 0x7598eddfd8
	public Void .ctor() { }
	// RVA: 0x68c6100 VA: 0x7598ede100
	public override Void ApplyOptions(GUILayoutOption[] options) { }
	// RVA: 0x68c6220 VA: 0x7598ede220
	protected override Void ApplyStyleSettings(GUIStyle style) { }
	// RVA: 0x68c6298 VA: 0x7598ede298
	public Void ResetCursor() { }
	// RVA: 0x68c5a90 VA: 0x7598edda90
	public GUILayoutEntry GetNext() { }
	// RVA: 0x68c59e0 VA: 0x7598edd9e0
	public Void Add(GUILayoutEntry e) { }
	// RVA: 0x68c62a0 VA: 0x7598ede2a0
	public override Void CalcWidth() { }
	// RVA: 0x68c68d0 VA: 0x7598ede8d0
	public override Void SetHorizontal(Single x, Single width) { }
	// RVA: 0x68c70e4 VA: 0x7598edf0e4
	public override Void CalcHeight() { }
	// RVA: 0x68c7664 VA: 0x7598edf664
	public override Void SetVertical(Single y, Single height) { }
	// RVA: 0x68c7e84 VA: 0x7598edfe84
	public override String ToString() { }
	// RVA: 0x68c8300 VA: 0x7598ee0300
	private static Void .cctor() { }
}
```