# Act12D6RetireConfirmView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `UIFullScreenImage _fullScreenImage`

- `GameObject _container`

- `CanvasGroup _rootView`

- `RectTransform _backBtn`

- `UIBlocker m_blocker`

- `Boolean m_isInited`

- `Action m_onClick`


## Methods

- `Void Initialize(Action)`

- `Void _Init()`

- `Void OnClick()`

- `Void ClosePage()`

- `Void OnDisable()`

- `Void _RenderBackImage()`

- `IEnumerator ShowCoroutine()`

- `IEnumerator HideCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6RetireConfirmView : MonoBehaviour, IHotfixable
{
	private UIFullScreenImage _fullScreenImage; // 0x18
	private GameObject _container; // 0x20
	private CanvasGroup _rootView; // 0x28
	private RectTransform _backBtn; // 0x30
	private UIBlocker m_blocker; // 0x38
	private Boolean m_isInited; // 0x40
	private Action m_onClick; // 0x48
	protected const Single FADE_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_Initialize; // 0x0
	private static DelegateBridge __Hotfix0__Init; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_ClosePage; // 0x18
	private static DelegateBridge __Hotfix0_OnDisable; // 0x20
	private static DelegateBridge __Hotfix0__RenderBackImage; // 0x28
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3479084 VA: 0x7595a91084
	public Void Initialize(Action OnConfirm) { }
	// RVA: 0x34791b4 VA: 0x7595a911b4
	private Void _Init() { }
	// RVA: 0x3479348 VA: 0x7595a91348
	public Void OnClick() { }
	// RVA: 0x34793d4 VA: 0x7595a913d4
	public Void ClosePage() { }
	// RVA: 0x34794fc VA: 0x7595a914fc
	private Void OnDisable() { }
	// RVA: 0x347921c VA: 0x7595a9121c
	private Void _RenderBackImage() { }
	// RVA: 0x3479590 VA: 0x7595a91590
	private IEnumerator ShowCoroutine() { }
	// RVA: 0x3479450 VA: 0x7595a91450
	private IEnumerator HideCoroutine() { }
	// RVA: 0x347968c VA: 0x7595a9168c
	public Void .ctor() { }
}
```