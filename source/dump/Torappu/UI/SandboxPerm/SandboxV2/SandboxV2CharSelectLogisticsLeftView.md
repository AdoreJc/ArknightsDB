# SandboxV2CharSelectLogisticsLeftView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _layoutContent`

- `ScrollRect _scrollRect`

- `RectTransform _realViewportRectTransform`

- `Boolean m_isInited`

- `BuffListAdapter m_buffListAdapter`

- `SandboxV2CharListViewModel m_charListViewModel`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void _OnScrollRectTween(Single)`

- `Void EventOnTipsBtnClick()`

- `Single <_OnScrollRectTween>b__10_0()`

- `Void <_OnScrollRectTween>b__10_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharSelectLogisticsLeftView : SandboxV2AdminCharSelectAbstractLeftView
{
	private SimpleLayoutContent _layoutContent; // 0x18
	private ScrollRect _scrollRect; // 0x20
	private RectTransform _realViewportRectTransform; // 0x28
	private Boolean m_isInited; // 0x30
	private BuffListAdapter m_buffListAdapter; // 0x38
	private SandboxV2CharListViewModel m_charListViewModel; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnScrollRectTween; // 0x10
	private static DelegateBridge __Hotfix0_EventOnTipsBtnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2483294 VA: 0x7594a9b294
	public override Void RenderView(SandboxV2CharListViewModel charListViewModel, SandboxV2CharSelectTabEnum tabEnum) { }
	// RVA: 0x24834c8 VA: 0x7594a9b4c8
	private Void _InitIfNot() { }
	// RVA: 0x2483698 VA: 0x7594a9b698
	private Void _OnScrollRectTween(Single pos) { }
	// RVA: 0x24838a0 VA: 0x7594a9b8a0
	public Void EventOnTipsBtnClick() { }
	// RVA: 0x2483954 VA: 0x7594a9b954
	public Void .ctor() { }
	// RVA: 0x24839c4 VA: 0x7594a9b9c4
	private Single <_OnScrollRectTween>b__10_0() { }
	// RVA: 0x24839e0 VA: 0x7594a9b9e0
	private Void <_OnScrollRectTween>b__10_1(Single val) { }
}
```