# SkinSelectButtonPreview

**Namespace:** `Torappu.UI.Skin`


## Fields

- `GameObject _btnPreview`

- `UISwitchTween m_btnPreviewShowTween`

- `SkinSelectViewModel m_cachedModel`

- `CharUISkinStruct m_cachedSkin`

- `UIPage m_page`


## Methods

- `Void InitData(UIPage)`

- `Void ApplyState(SkinSelectViewModel)`

- `Void OnBtnPreviewClicked()`

- `IEnumerator _PlayDynEntranceCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinSelectButtonPreview : MonoBehaviour, IHotfixable
{
	private GameObject _btnPreview; // 0x18
	private UISwitchTween m_btnPreviewShowTween; // 0x20
	private SkinSelectViewModel m_cachedModel; // 0x28
	private CharUISkinStruct m_cachedSkin; // 0x30
	private UIPage m_page; // 0x40
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_ApplyState; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnPreviewClicked; // 0x10
	private static DelegateBridge __Hotfix0__PlayDynEntranceCoroutine; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x23d4210 VA: 0x75949ec210
	public Void InitData(UIPage page) { }
	// RVA: 0x23d4328 VA: 0x75949ec328
	public Void ApplyState(SkinSelectViewModel viewModel) { }
	// RVA: 0x23d44ac VA: 0x75949ec4ac
	public Void OnBtnPreviewClicked() { }
	// RVA: 0x23d46bc VA: 0x75949ec6bc
	private IEnumerator _PlayDynEntranceCoroutine() { }
	// RVA: 0x23d4790 VA: 0x75949ec790
	public Void .ctor() { }
}
```