# MaxSizeLayoutElement

**Namespace:** `Torappu.Scripts.UI.Common.Widgets`


## Fields

- `Boolean useMaxHeight`

- `Single maxHeight`

- `Boolean useMaxWidth`

- `Single maxWidth`

- `Boolean m_ignoreOnGettingPreferedSize`

- `RectTransform m_rectTransform`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.UI.Common.Widgets
public class MaxSizeLayoutElement : LayoutElement
{
	public Boolean useMaxHeight; // 0x38
	public Single maxHeight; // 0x3c
	public Boolean useMaxWidth; // 0x40
	public Single maxWidth; // 0x44
	private Boolean m_ignoreOnGettingPreferedSize; // 0x48
	private RectTransform m_rectTransform; // 0x50

	public override Int32 layoutPriority { get; set; }
	public override Single preferredHeight { get; set; }
	public override Single preferredWidth { get; set; }

	// RVA: 0x3776550 VA: 0x7595d8e550
	public override Int32 get_layoutPriority() { }
	// RVA: 0x3776568 VA: 0x7595d8e568
	public override Void set_layoutPriority(Int32 value) { }
	// RVA: 0x3776570 VA: 0x7595d8e570
	protected override Void Awake() { }
	// RVA: 0x37765f0 VA: 0x7595d8e5f0
	public override Single get_preferredHeight() { }
	// RVA: 0x3776664 VA: 0x7595d8e664
	public override Void set_preferredHeight(Single value) { }
	// RVA: 0x377666c VA: 0x7595d8e66c
	public override Single get_preferredWidth() { }
	// RVA: 0x37766e0 VA: 0x7595d8e6e0
	public override Void set_preferredWidth(Single value) { }
	// RVA: 0x37766e8 VA: 0x7595d8e6e8
	public Void .ctor() { }
}
```