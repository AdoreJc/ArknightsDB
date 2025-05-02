# Act24sideStageMeldingView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `Act24sideStageMeldingViewModel m_model`

- `ILoadAsset assetLoader`


## Methods

- `Void OnViewModelRefresh(TemplateActivityViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideStageMeldingView : MonoBehaviour, IBaseActViewBinder, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Boolean m_isInited; // 0x20
	private Adapter m_adapter; // 0x28
	private Act24sideStageMeldingViewModel m_model; // 0x30
	public ILoadAsset assetLoader; // 0x38
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32a0090 VA: 0x75958b8090
	public Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x32a01d4 VA: 0x75958b81d4
	private Void _InitIfNot() { }
	// RVA: 0x32a0344 VA: 0x75958b8344
	public Void .ctor() { }
}
```