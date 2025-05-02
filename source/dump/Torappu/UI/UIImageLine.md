# UIImageLine

**Namespace:** `Torappu.UI`


## Fields

- `Single _lineWidth`

- `Single _lineAlign`

- `Image m_image`

- `RectTransform m_rectTrans`


## Properties

- `Image image`

- `Single lineWidth`

- `Single lineAlign`

- `RectTransform rectTrans`


## Methods

- `Image get_image()`

- `Single get_lineWidth()`

- `Void set_lineWidth(Single)`

- `Single get_lineAlign()`

- `Void set_lineAlign(Single)`

- `RectTransform get_rectTrans()`

- `Void LineTo(Vector2, Vector2, RectTransform)`

- `Void _UpdateConfig(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIImageLine : MonoBehaviour, IHotfixable
{
	private Single _lineWidth; // 0x18
	private Single _lineAlign; // 0x1c
	private Image m_image; // 0x20
	private RectTransform m_rectTrans; // 0x28
	private static DelegateBridge __Hotfix0_get_image; // 0x0
	private static DelegateBridge __Hotfix0_get_lineWidth; // 0x8
	private static DelegateBridge __Hotfix0_set_lineWidth; // 0x10
	private static DelegateBridge __Hotfix0_get_lineAlign; // 0x18
	private static DelegateBridge __Hotfix0_set_lineAlign; // 0x20
	private static DelegateBridge __Hotfix0_get_rectTrans; // 0x28
	private static DelegateBridge __Hotfix0_LineTo; // 0x30
	private static DelegateBridge __Hotfix0__UpdateConfig; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Image image { get; }
	public Single lineWidth { get; set; }
	public Single lineAlign { get; set; }
	public RectTransform rectTrans { get; }

	// RVA: 0x21d7dec VA: 0x75947efdec
	public Image get_image() { }
	// RVA: 0x21d7ec4 VA: 0x75947efec4
	public Single get_lineWidth() { }
	// RVA: 0x21d7f2c VA: 0x75947eff2c
	public Void set_lineWidth(Single value) { }
	// RVA: 0x21d7fa8 VA: 0x75947effa8
	public Single get_lineAlign() { }
	// RVA: 0x21d8010 VA: 0x75947f0010
	public Void set_lineAlign(Single value) { }
	// RVA: 0x21d808c VA: 0x75947f008c
	public RectTransform get_rectTrans() { }
	// RVA: 0x21d8164 VA: 0x75947f0164
	public Void LineTo(Vector2 start, Vector2 end, RectTransform local) { }
	// RVA: 0x21d8334 VA: 0x75947f0334
	private Void _UpdateConfig(Single length) { }
	// RVA: 0x21d8424 VA: 0x75947f0424
	public Void .ctor() { }
}
```