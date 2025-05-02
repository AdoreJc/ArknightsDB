# Act1VAutoChessHUDBlurBackPanel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `CanvasGroup _rootCanvasGroup`

- `UIRenderTextureImage _rtImage`

- `Boolean m_isInited`

- `FadeSwitchTween m_fadeTween`

- `BlurHandler m_blurHandler`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void set_isShow(Boolean)`

- `Void _InitIfNot()`

- `Void Reset(Boolean)`

- `Void _HandleBlurTarget()`

- `Void SetBlurHanlder(BlurHandler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDBlurBackPanel : MonoBehaviour, IHotfixable
{
	private CanvasGroup _rootCanvasGroup; // 0x18
	private UIRenderTextureImage _rtImage; // 0x20
	private Boolean m_isInited; // 0x28
	private FadeSwitchTween m_fadeTween; // 0x30
	private BlurHandler m_blurHandler; // 0x38
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_set_isShow; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0__HandleBlurTarget; // 0x20
	private static DelegateBridge __Hotfix0_SetBlurHanlder; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isShow { get; set; }

	// RVA: 0x3371790 VA: 0x7595989790
	public Boolean get_isShow() { }
	// RVA: 0x33718f0 VA: 0x75959898f0
	public Void set_isShow(Boolean value) { }
	// RVA: 0x337180c VA: 0x759598980c
	private Void _InitIfNot() { }
	// RVA: 0x3371a8c VA: 0x7595989a8c
	public Void Reset(Boolean isShow) { }
	// RVA: 0x33719a4 VA: 0x75959899a4
	private Void _HandleBlurTarget() { }
	// RVA: 0x3371cd4 VA: 0x7595989cd4
	public Void SetBlurHanlder(BlurHandler blurHandler) { }
	// RVA: 0x3371d58 VA: 0x7595989d58
	public Void .ctor() { }
}
```