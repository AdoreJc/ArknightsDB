# SiracusaOperaCommentColumnView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SimpleLayoutContent _content`

- `VerticalLayoutGroup _layoutGroup`

- `RectTransform _bottom`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `Single m_columnHeight`


## Properties

- `Single columnHeight`


## Methods

- `Single get_columnHeight()`

- `Void Render(List`1, String, Boolean)`

- `Void SetBottomHeight(Single)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaCommentColumnView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private VerticalLayoutGroup _layoutGroup; // 0x20
	private RectTransform _bottom; // 0x28
	public Action`1 onCommentClicked; // 0x30
	private Boolean m_isInited; // 0x38
	private Adapter m_adapter; // 0x40
	private Single m_columnHeight; // 0x48
	private const Single BOTTOM_FILL_THRESHOLD_HEIGHT; // 0x0
	private static DelegateBridge __Hotfix0_get_columnHeight; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_SetBottomHeight; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Single columnHeight { get; }

	// RVA: 0x23f5ae4 VA: 0x7594a0dae4
	public Single get_columnHeight() { }
	// RVA: 0x23f5b4c VA: 0x7594a0db4c
	public Void Render(List`1 items, String selectedCommentId, Boolean isInit) { }
	// RVA: 0x23f5e70 VA: 0x7594a0de70
	public Void SetBottomHeight(Single bottomHeight) { }
	// RVA: 0x23f5c3c VA: 0x7594a0dc3c
	private Void _InitIfNot() { }
	// RVA: 0x23f6010 VA: 0x7594a0e010
	public Void .ctor() { }
}
```