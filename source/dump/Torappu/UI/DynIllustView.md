# DynIllustView

**Namespace:** `Torappu.UI`


## Fields

- `DynIllust _illust`

- `DynIllust m_inst`

- `RectTransform <rectTransform>k__BackingField`

- `RawImage <rawImage>k__BackingField`


## Properties

- `RectTransform rectTransform`

- `RawImage rawImage`

- `DynIllust res`

- `DynIllust inst`


## Methods

- `Void Awake()`

- `RectTransform get_rectTransform()`

- `Void set_rectTransform(RectTransform)`

- `RawImage get_rawImage()`

- `Void set_rawImage(RawImage)`

- `DynIllust get_res()`

- `DynIllust get_inst()`

- `Void Init(DynIllust)`

- `Void Active()`

- `Void ClearAdjust()`

- `Void ApplyAdjust(DynIllustAdjustType)`

- `Void InitComponent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DynIllustView : MonoBehaviour
{
	private DynIllust _illust; // 0x18
	private DynIllust m_inst; // 0x20
	private RectTransform <rectTransform>k__BackingField; // 0x28
	private RawImage <rawImage>k__BackingField; // 0x30

	public RectTransform rectTransform { get; set; }
	public RawImage rawImage { get; set; }
	public DynIllust res { get; }
	public DynIllust inst { get; }

	// RVA: 0x2117870 VA: 0x759472f870
	private Void Awake() { }
	// RVA: 0x2117978 VA: 0x759472f978
	public RectTransform get_rectTransform() { }
	// RVA: 0x2117980 VA: 0x759472f980
	private Void set_rectTransform(RectTransform value) { }
	// RVA: 0x2117988 VA: 0x759472f988
	public RawImage get_rawImage() { }
	// RVA: 0x2117990 VA: 0x759472f990
	private Void set_rawImage(RawImage value) { }
	// RVA: 0x2117998 VA: 0x759472f998
	public DynIllust get_res() { }
	// RVA: 0x21179a0 VA: 0x759472f9a0
	public DynIllust get_inst() { }
	// RVA: 0x21179a8 VA: 0x759472f9a8
	public Void Init(DynIllust illustRes) { }
	// RVA: 0x2117a84 VA: 0x759472fa84
	public Void Active() { }
	// RVA: 0x2117aec VA: 0x759472faec
	public Void ClearAdjust() { }
	// RVA: 0x2117b68 VA: 0x759472fb68
	public Void ApplyAdjust(DynIllustAdjustType type) { }
	// RVA: 0x21178e8 VA: 0x759472f8e8
	public Void InitComponent() { }
	// RVA: 0x2117be8 VA: 0x759472fbe8
	public Void .ctor() { }
}
```