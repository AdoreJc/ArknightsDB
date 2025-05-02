# Act35sideEntryCarvingPlugin

**Namespace:** `Torappu.Activity.Act35side`


## Fields

- `UISpineLocation _animHappy`

- `UISpineLocation _animNormal`

- `GameObject _carvingEnable`

- `GameObject _carvingDisable`

- `GameObject _carvingNew`

- `Text _textDisable`

- `GameObject _panelCarvingBtn`

- `Act35sideEntryCarvingViewModel m_viewModel`


## Methods

- `Void OpenCarving()`

- `Void _OnOpenCarvingPage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act35side
public class Act35sideEntryCarvingPlugin : TemplateActivityCommonPlugin, IHotfixable
{
	private UISpineLocation _animHappy; // 0x28
	private UISpineLocation _animNormal; // 0x38
	private GameObject _carvingEnable; // 0x48
	private GameObject _carvingDisable; // 0x50
	private GameObject _carvingNew; // 0x58
	private Text _textDisable; // 0x60
	private GameObject _panelCarvingBtn; // 0x68
	private Act35sideEntryCarvingViewModel m_viewModel; // 0x70
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_OpenCarving; // 0x8
	private static DelegateBridge __Hotfix0__OnOpenCarvingPage; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x325206c VA: 0x759586a06c
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x325240c VA: 0x759586a40c
	public Void OpenCarving() { }
	// RVA: 0x3252474 VA: 0x759586a474
	private Void _OnOpenCarvingPage() { }
	// RVA: 0x325261c VA: 0x759586a61c
	public Void .ctor() { }
}
```