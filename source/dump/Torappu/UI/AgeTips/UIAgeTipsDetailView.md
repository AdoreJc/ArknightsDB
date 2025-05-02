# UIAgeTipsDetailView

**Namespace:** `Torappu.UI.AgeTips`


## Fields

- `RectTransform _contentHolder`

- `Text _titlePrefab`

- `Text _contentPrefab`

- `CanvasGroup _alphaHandler`

- `Button _btnClose`

- `FadeSwitchTween m_fadeTween`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Start()`

- `Void Show(Config)`

- `Void _OnContentSuc(MIMEObject)`

- `Boolean _OnContentFail(ResponseError)`

- `Void _RenderCurrentContent()`

- `Void EventOnCloseClicked()`

- `Boolean _CheckIfViewOpen()`

- `Void _Dismiss()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.AgeTips
public class UIAgeTipsDetailView : MonoBehaviour, IHotfixable
{
	private const Int32 MAX_TEXT_STRLEN; // 0x0
	private const Int32 MIN_TEXT_STRLEN; // 0x0
	private RectTransform _contentHolder; // 0x18
	private Text _titlePrefab; // 0x20
	private Text _contentPrefab; // 0x28
	private CanvasGroup _alphaHandler; // 0x30
	private Button _btnClose; // 0x38
	private List`1 m_content; // 0x40
	private FadeSwitchTween m_fadeTween; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0__OnContentSuc; // 0x18
	private static DelegateBridge __Hotfix0__OnContentFail; // 0x20
	private static DelegateBridge __Hotfix0__RenderCurrentContent; // 0x28
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x30
	private static DelegateBridge __Hotfix0__CheckIfViewOpen; // 0x38
	private static DelegateBridge __Hotfix0__Dismiss; // 0x40
	private static DelegateBridge __Hotfix0_SplitLicenseToSegments; // 0x48
	private static DelegateBridge __Hotfix0__SplitLongString; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2e98298 VA: 0x75954b0298
	private Void _InitIfNot() { }
	// RVA: 0x2e98428 VA: 0x75954b0428
	private Void Start() { }
	// RVA: 0x2e98490 VA: 0x75954b0490
	public Void Show(Config config) { }
	// RVA: 0x2e98890 VA: 0x75954b0890
	private Void _OnContentSuc(MIMEObject response) { }
	// RVA: 0x2e98db4 VA: 0x75954b0db4
	private Boolean _OnContentFail(ResponseError error) { }
	// RVA: 0x2e98714 VA: 0x75954b0714
	private Void _RenderCurrentContent() { }
	// RVA: 0x2e98eb0 VA: 0x75954b0eb0
	public Void EventOnCloseClicked() { }
	// RVA: 0x2e98698 VA: 0x75954b0698
	private Boolean _CheckIfViewOpen() { }
	// RVA: 0x2e98f18 VA: 0x75954b0f18
	private Void _Dismiss() { }
	// RVA: 0x2e98954 VA: 0x75954b0954
	public static List`1 SplitLicenseToSegments(String content) { }
	// RVA: 0x2e98fa8 VA: 0x75954b0fa8
	private static Void _SplitLongString(String longStr, List`1 outputList) { }
	// RVA: 0x2e9912c VA: 0x75954b112c
	public Void .ctor() { }
}
```