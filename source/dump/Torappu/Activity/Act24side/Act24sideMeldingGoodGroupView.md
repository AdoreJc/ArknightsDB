# Act24sideMeldingGoodGroupView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `SimpleLayoutContent _layoutContent`

- `VerticalLayoutGroup _layout`

- `RectTransform _rectLayout`

- `ScrollRect _scrollRect`

- `Boolean m_hasInited`

- `Act24sideMeldingGoodGroupViewModel m_model`

- `Adapter m_adapter`

- `TweenWrapper m_focusTween`

- `Int32 m_layoutTopSpace`

- `Int32 m_layoutDownSpace`

- `Single m_layoutSpace`

- `Boolean m_isDicDisplayLayoutInited`

- `UIPage m_page`

- `Coroutine m_corScrollToProperRare`

- `String <gachaBoxId>k__BackingField`


## Properties

- `String gachaBoxId`


## Methods

- `String get_gachaBoxId()`

- `Void set_gachaBoxId(String)`

- `Void Init(UIPage)`

- `Void Render(Act24sideMeldingGoodGroupViewModel)`

- `Void TryScrollToRemainCountRarePart()`

- `Void _InitIfNot()`

- `Void _InitDicDisplayLayoutStatus()`

- `Boolean _IsAllDisplayLayouted()`

- `IEnumerator _CoTryScrollToRemainCountRarePart()`

- `Void _OnDisplayGridPostLayout(MeldingGoodDisplayType)`

- `Single <_CoTryScrollToRemainCountRarePart>b__27_0()`

- `Void <_CoTryScrollToRemainCountRarePart>b__27_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingGoodGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _layoutContent; // 0x18
	private VerticalLayoutGroup _layout; // 0x20
	private RectTransform _rectLayout; // 0x28
	private ScrollRect _scrollRect; // 0x30
	private Boolean m_hasInited; // 0x38
	private Act24sideMeldingGoodGroupViewModel m_model; // 0x40
	private Adapter m_adapter; // 0x48
	private TweenWrapper m_focusTween; // 0x50
	private Int32 m_layoutTopSpace; // 0x58
	private Int32 m_layoutDownSpace; // 0x5c
	private Single m_layoutSpace; // 0x60
	private Boolean m_isDicDisplayLayoutInited; // 0x64
	private Dictionary`2 m_dicDisplayLayoutStatus; // 0x68
	private UIPage m_page; // 0x70
	private Coroutine m_corScrollToProperRare; // 0x78
	private static readonly Single SCROLL_SPEED; // 0x0
	private String <gachaBoxId>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_gachaBoxId; // 0x8
	private static DelegateBridge __Hotfix0_set_gachaBoxId; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_TryScrollToRemainCountRarePart; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__InitDicDisplayLayoutStatus; // 0x38
	private static DelegateBridge __Hotfix0__IsAllDisplayLayouted; // 0x40
	private static DelegateBridge __Hotfix0__CoTryScrollToRemainCountRarePart; // 0x48
	private static DelegateBridge __Hotfix0__OnDisplayGridPostLayout; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String gachaBoxId { get; set; }

	// RVA: 0x32a217c VA: 0x75958ba17c
	public String get_gachaBoxId() { }
	// RVA: 0x32a21f4 VA: 0x75958ba1f4
	private Void set_gachaBoxId(String value) { }
	// RVA: 0x32a2288 VA: 0x75958ba288
	public Void Init(UIPage page) { }
	// RVA: 0x32a231c VA: 0x75958ba31c
	public Void Render(Act24sideMeldingGoodGroupViewModel groupViewModel) { }
	// RVA: 0x32a2694 VA: 0x75958ba694
	public Void TryScrollToRemainCountRarePart() { }
	// RVA: 0x32a240c VA: 0x75958ba40c
	private Void _InitIfNot() { }
	// RVA: 0x32a252c VA: 0x75958ba52c
	private Void _InitDicDisplayLayoutStatus() { }
	// RVA: 0x32a2938 VA: 0x75958ba938
	private Boolean _IsAllDisplayLayouted() { }
	// RVA: 0x32a27e8 VA: 0x75958ba7e8
	private IEnumerator _CoTryScrollToRemainCountRarePart() { }
	// RVA: 0x32a2b24 VA: 0x75958bab24
	private Void _OnDisplayGridPostLayout(MeldingGoodDisplayType displayType) { }
	// RVA: 0x32a2c70 VA: 0x75958bac70
	public Void .ctor() { }
	// RVA: 0x32a2d44 VA: 0x75958bad44
	private static Void .cctor() { }
	// RVA: 0x32a2d94 VA: 0x75958bad94
	private Single <_CoTryScrollToRemainCountRarePart>b__27_0() { }
	// RVA: 0x32a2db0 VA: 0x75958badb0
	private Void <_CoTryScrollToRemainCountRarePart>b__27_1(Single val) { }
}
```