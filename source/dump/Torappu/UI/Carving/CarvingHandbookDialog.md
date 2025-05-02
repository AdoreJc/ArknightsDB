# CarvingHandbookDialog

**Namespace:** `Torappu.UI.Carving`


## Fields

- `RectTransform _rectBack`

- `UIRenderTextureImage _blurBg`

- `GameObject _darkenImgObj`

- `UIAnimationLocation _enterAnim`

- `Boolean m_hasInited`

- `Boolean m_hasAnimFinished`


## Methods

- `Void _EventOnEnterAnimFinished()`

- `Void _InitIfNot()`

- `Void EventOnBackClicked()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingHandbookDialog : UICompDialog`1, IHotfixable
{
	private RectTransform _rectBack; // 0x48
	private UIRenderTextureImage _blurBg; // 0x50
	private GameObject _darkenImgObj; // 0x58
	private UIAnimationLocation _enterAnim; // 0x60
	private Boolean m_hasInited; // 0x70
	private Boolean m_hasAnimFinished; // 0x71
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x8
	private static DelegateBridge __Hotfix0__EventOnEnterAnimFinished; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d90e38 VA: 0x75953a8e38
	protected override Void OnRender(Options input) { }
	// RVA: 0x2d9106c VA: 0x75953a906c
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x2d910d4 VA: 0x75953a90d4
	private Void _EventOnEnterAnimFinished() { }
	// RVA: 0x2d90f5c VA: 0x75953a8f5c
	private Void _InitIfNot() { }
	// RVA: 0x2d91140 VA: 0x75953a9140
	public Void EventOnBackClicked() { }
	// RVA: 0x2d9121c VA: 0x75953a921c
	public Void .ctor() { }
	// RVA: 0x2d912ac VA: 0x75953a92ac
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```