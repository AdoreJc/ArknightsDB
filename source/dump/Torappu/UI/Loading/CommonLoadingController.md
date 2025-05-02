# CommonLoadingController

**Namespace:** `Torappu.UI.Loading`


## Fields

- `Image _illust`

- `UITipsHolder _tipsHolder`

- `DirectAssetLoader m_assetLoader`

- `Boolean m_isShowing`


## Properties

- `Boolean isShowing`


## Methods

- `Boolean get_isShowing()`

- `String _GetLoadingIllustId(String)`

- `Category _GetTipCategoryMask()`

- `Void Show(String)`

- `Void Hide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Loading
public class CommonLoadingController : MonoBehaviour, IHotfixable
{
	private Image _illust; // 0x18
	private UITipsHolder _tipsHolder; // 0x20
	private DirectAssetLoader m_assetLoader; // 0x28
	private Boolean m_isShowing; // 0x30
	private static DelegateBridge __Hotfix0_get_isShowing; // 0x0
	private static DelegateBridge __Hotfix0__GetLoadingIllustId; // 0x8
	private static DelegateBridge __Hotfix0__GetTipCategoryMask; // 0x10
	private static DelegateBridge __Hotfix0_Show; // 0x18
	private static DelegateBridge __Hotfix0_Hide; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isShowing { get; }

	// RVA: 0x27b9184 VA: 0x7594dd1184
	public Boolean get_isShowing() { }
	// RVA: 0x27b91ec VA: 0x7594dd11ec
	private String _GetLoadingIllustId(String illustId) { }
	// RVA: 0x27b92d8 VA: 0x7594dd12d8
	private Category _GetTipCategoryMask() { }
	// RVA: 0x27b9384 VA: 0x7594dd1384
	public Void Show(String loadingIllust) { }
	// RVA: 0x27b9554 VA: 0x7594dd1554
	public Void Hide() { }
	// RVA: 0x27b9600 VA: 0x7594dd1600
	public Void .ctor() { }
}
```