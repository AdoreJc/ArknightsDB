# YostarSDKAgreementItem

**Namespace:** `YostarSDK.UI.Agreement`


## Fields

- `TwoStateToggle _toggleConfirm`

- `SimpleLayoutContent _textContainer`

- `Text _textConfirm`

- `AgreementItemModel m_viewModel`

- `ContentAdapter m_adapter`

- `Boolean m_isContentInited`


## Methods

- `Void _InitContentIfNot(String)`

- `Void UpdateStatus(AgreementItemModel)`

- `Void EventOnConfirmClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI.Agreement
public class YostarSDKAgreementItem : MonoBehaviour, IHotfixable
{
	private const Int32 MAX_TEXT_STRLEN; // 0x0
	private const Int32 MIN_TEXT_STRLEN; // 0x0
	private TwoStateToggle _toggleConfirm; // 0x18
	private SimpleLayoutContent _textContainer; // 0x20
	private Text _textConfirm; // 0x28
	private AgreementItemModel m_viewModel; // 0x30
	public Action`1 onConfirmToggleClicked; // 0x38
	private List`1 m_content; // 0x40
	private ContentAdapter m_adapter; // 0x48
	private Boolean m_isContentInited; // 0x50
	private static DelegateBridge __Hotfix0__InitContentIfNot; // 0x0
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x8
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x10
	private static DelegateBridge __Hotfix0_SplitLicenseToSegments; // 0x18
	private static DelegateBridge __Hotfix0__SplitLongString; // 0x20
	private static DelegateBridge __Hotfix0__DealWithTitleStyle; // 0x28
	private static DelegateBridge __Hotfix0__DealWithContentStyle; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2581ba0 VA: 0x7594b99ba0
	private Void _InitContentIfNot(String content) { }
	// RVA: 0x2581704 VA: 0x7594b99704
	public Void UpdateStatus(AgreementItemModel viewModel) { }
	// RVA: 0x2581e9c VA: 0x7594b99e9c
	public Void EventOnConfirmClicked() { }
	// RVA: 0x2579324 VA: 0x7594b91324
	public static List`1 SplitLicenseToSegments(String content) { }
	// RVA: 0x2581f2c VA: 0x7594b99f2c
	private static Void _SplitLongString(String longStr, List`1 outputList) { }
	// RVA: 0x25820b0 VA: 0x7594b9a0b0
	private static Void _DealWithTitleStyle(Text text) { }
	// RVA: 0x2582138 VA: 0x7594b9a138
	private static Void _DealWithContentStyle(Text text) { }
	// RVA: 0x25821c0 VA: 0x7594b9a1c0
	public Void .ctor() { }
}
```