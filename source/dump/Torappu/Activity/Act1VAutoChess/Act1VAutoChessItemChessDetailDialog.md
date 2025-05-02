# Act1VAutoChessItemChessDetailDialog

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessItemChessDetailView _view`

- `UIRenderTextureImage _blurImg`

- `RectTransform _backPressRect`

- `Act1VAutoChessItemChessDetailViewModel m_viewModel`


## Methods

- `Void EventOnCloseBtnClick()`

- `Void EventOnRightBtnClick()`

- `Void EventOnLeftBtnClick()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessItemChessDetailDialog : UICompDialog`1
{
	private Act1VAutoChessItemChessDetailView _view; // 0x48
	private UIRenderTextureImage _blurImg; // 0x50
	private RectTransform _backPressRect; // 0x58
	private Act1VAutoChessItemChessDetailViewModel m_viewModel; // 0x60
	private static DelegateBridge __Hotfix0_EventOnCloseBtnClick; // 0x0
	private static DelegateBridge __Hotfix0_EventOnRightBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_EventOnLeftBtnClick; // 0x10
	private static DelegateBridge __Hotfix0_OnRender; // 0x18
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x33597a0 VA: 0x75959717a0
	public Void EventOnCloseBtnClick() { }
	// RVA: 0x3359874 VA: 0x7595971874
	public Void EventOnRightBtnClick() { }
	// RVA: 0x335997c VA: 0x759597197c
	public Void EventOnLeftBtnClick() { }
	// RVA: 0x3359a84 VA: 0x7595971a84
	protected override Void OnRender(Option input) { }
	// RVA: 0x335a000 VA: 0x7595972000
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x335a068 VA: 0x7595972068
	public Void .ctor() { }
	// RVA: 0x335a0f8 VA: 0x75959720f8
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```