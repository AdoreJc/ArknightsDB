# UIManager

**Namespace:** `YostarSDK.UI`


## Fields

- `Options m_options`

- `UIPage m_currentPage`

- `RaycastBlockerMgr m_raycastBlockerMgr`

- `YostarSDKAgreement m_agreement`

- `YostarSDK <sdk>k__BackingField`


## Properties

- `Boolean isShowPage`

- `Boolean isShowAgreement`

- `YostarSDK sdk`


## Methods

- `Boolean get_isShowPage()`

- `Boolean get_isShowAgreement()`

- `YostarSDK get_sdk()`

- `Void set_sdk(YostarSDK)`

- `Void OnStart()`

- `PageType OpenUIPage(PageType, Action`1)`

- `Boolean CloseUIPage(UIPage)`

- `Boolean CloseCurrentUIPage()`

- `Boolean BlockRaycast(Boolean, RaycastBlockerSource)`

- `YostarSDKAgreement OpenAgreement(YostarSDKAgreement, AgreementOptions)`

- `Void CloseAgreement()`

- `IEnumerator _DoOpenUICoroutine()`

- `IEnumerator _DoCloseUICoroutine()`

- `IEnumerator _CloseAgreementCoroutine()`

- `Void _UpdateViews()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class UIManager : IHotfixable
{
	private Options m_options; // 0x10
	private UIPage m_currentPage; // 0x40
	private RaycastBlockerMgr m_raycastBlockerMgr; // 0x48
	private YostarSDKAgreement m_agreement; // 0x50
	private YostarSDK <sdk>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_isShowPage; // 0x0
	private static DelegateBridge __Hotfix0_get_isShowAgreement; // 0x8
	private static DelegateBridge __Hotfix0_get_sdk; // 0x10
	private static DelegateBridge __Hotfix0_set_sdk; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge __Hotfix0_OnStart; // 0x28
	private static DelegateBridge __Hotfix0_OpenUIPage; // 0x30
	private static DelegateBridge __Hotfix0_CloseUIPage; // 0x38
	private static DelegateBridge __Hotfix0_CloseCurrentUIPage; // 0x40
	private static DelegateBridge __Hotfix0_BlockRaycast; // 0x48
	private static DelegateBridge __Hotfix0_OpenAgreement; // 0x50
	private static DelegateBridge __Hotfix0_CloseAgreement; // 0x58
	private static DelegateBridge __Hotfix0__DoOpenUICoroutine; // 0x60
	private static DelegateBridge __Hotfix0__DoCloseUICoroutine; // 0x68
	private static DelegateBridge __Hotfix0__CloseAgreementCoroutine; // 0x70
	private static DelegateBridge __Hotfix0__UpdateViews; // 0x78

	public Boolean isShowPage { get; }
	public Boolean isShowAgreement { get; }
	public YostarSDK sdk { get; set; }

	// RVA: 0x257f3a0 VA: 0x7594b973a0
	public Boolean get_isShowPage() { }
	// RVA: 0x257f438 VA: 0x7594b97438
	public Boolean get_isShowAgreement() { }
	// RVA: 0x257f4d0 VA: 0x7594b974d0
	public YostarSDK get_sdk() { }
	// RVA: 0x257f538 VA: 0x7594b97538
	private Void set_sdk(YostarSDK value) { }
	// RVA: 0x257f5bc VA: 0x7594b975bc
	public Void .ctor(YostarSDK sdk, Options options) { }
	// RVA: 0x257f78c VA: 0x7594b9778c
	public Void OnStart() { }
	// RVA: 0x VA: 0x0
	public PageType OpenUIPage(PageType uiPrefab, Action`1 onLoaded) { }
	// RVA: 0x257b3bc VA: 0x7594b933bc
	public Boolean CloseUIPage(UIPage ui) { }
	// RVA: 0x257f9bc VA: 0x7594b979bc
	public Boolean CloseCurrentUIPage() { }
	// RVA: 0x257fa94 VA: 0x7594b97a94
	public Boolean BlockRaycast(Boolean isBlock, RaycastBlockerSource source) { }
	// RVA: 0x257fbd4 VA: 0x7594b97bd4
	public YostarSDKAgreement OpenAgreement(YostarSDKAgreement prefab, AgreementOptions options) { }
	// RVA: 0x257fe78 VA: 0x7594b97e78
	public Void CloseAgreement() { }
	// RVA: 0x257fff8 VA: 0x7594b97ff8
	private IEnumerator _DoOpenUICoroutine() { }
	// RVA: 0x257f910 VA: 0x7594b97910
	private IEnumerator _DoCloseUICoroutine() { }
	// RVA: 0x257ff4c VA: 0x7594b97f4c
	private IEnumerator _CloseAgreementCoroutine() { }
	// RVA: 0x257f7f4 VA: 0x7594b977f4
	private Void _UpdateViews() { }
}
```