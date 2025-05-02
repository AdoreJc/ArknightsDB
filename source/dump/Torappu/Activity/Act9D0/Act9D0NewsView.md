# Act9D0NewsView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Act9D0NewsGroupAdapter _newsAdapter`

- `ScrollRect _detailContent`

- `Act9D0NewsDetailObjView _titleObj`

- `Act9D0NewsDetailObjView _textObj`

- `Act9D0NewsDetailObjView _imgObj`

- `Image _detailMainLogo`

- `LoopScrollRect _scrollRect`

- `String cachedActId`

- `Act9D0NewsStateBean cachedBean`

- `Tween m_cacheTween`


## Methods

- `Void Render(Act9D0NewsStateBean, String)`

- `Void RenderDetail(Act9D0NewsViewModel)`

- `Void _ClearContent()`

- `Void ScrollToGroupPos(Int32)`

- `Void <RenderDetail>b__11_0()`

- `Single <ScrollToGroupPos>b__13_0()`

- `Void <ScrollToGroupPos>b__13_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0NewsView : MonoBehaviour, IHotfixable
{
	private Act9D0NewsGroupAdapter _newsAdapter; // 0x18
	private ScrollRect _detailContent; // 0x20
	private Act9D0NewsDetailObjView _titleObj; // 0x28
	private Act9D0NewsDetailObjView _textObj; // 0x30
	private Act9D0NewsDetailObjView _imgObj; // 0x38
	private Image _detailMainLogo; // 0x40
	private LoopScrollRect _scrollRect; // 0x48
	private String cachedActId; // 0x50
	private Act9D0NewsStateBean cachedBean; // 0x58
	private Tween m_cacheTween; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RenderDetail; // 0x8
	private static DelegateBridge __Hotfix0__ClearContent; // 0x10
	private static DelegateBridge __Hotfix0_ScrollToGroupPos; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31aa470 VA: 0x75957c2470
	public Void Render(Act9D0NewsStateBean stateBean, String chosenId) { }
	// RVA: 0x31aa570 VA: 0x75957c2570
	public Void RenderDetail(Act9D0NewsViewModel viewModel) { }
	// RVA: 0x31aa8f8 VA: 0x75957c28f8
	private Void _ClearContent() { }
	// RVA: 0x31aaa5c VA: 0x75957c2a5c
	public Void ScrollToGroupPos(Int32 index) { }
	// RVA: 0x31aac48 VA: 0x75957c2c48
	public Void .ctor() { }
	// RVA: 0x31aacb8 VA: 0x75957c2cb8
	private Void <RenderDetail>b__11_0() { }
	// RVA: 0x31aacd8 VA: 0x75957c2cd8
	private Single <ScrollToGroupPos>b__13_0() { }
	// RVA: 0x31aacf4 VA: 0x75957c2cf4
	private Void <ScrollToGroupPos>b__13_1(Single val) { }
}
```