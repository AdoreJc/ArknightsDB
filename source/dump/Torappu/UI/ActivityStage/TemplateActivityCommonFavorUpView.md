# TemplateActivityCommonFavorUpView

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `SimpleLayoutContent _newUpGroup`

- `SimpleLayoutContent _upGroup`

- `GameObject _imageNew`

- `GameObject _panelSplit`

- `ActFavorUpGroupViewAdapter m_newUpGroupAdapter`

- `ActFavorUpGroupViewAdapter m_upGroupAdapter`

- `Boolean m_inited`


## Methods

- `Void OnViewModelRefresh(TemplateActivityViewModel)`

- `Void Render(List`1, String)`

- `Void _InitIfNot()`

- `Int32 _CompareFavorUpChar(ActFavorUpCharData, ActFavorUpCharData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityCommonFavorUpView : MonoBehaviour, IBaseActViewBinder, IHotfixable
{
	private SimpleLayoutContent _newUpGroup; // 0x18
	private SimpleLayoutContent _upGroup; // 0x20
	private GameObject _imageNew; // 0x28
	private GameObject _panelSplit; // 0x30
	private List`1 m_newUpCharList; // 0x38
	private List`1 m_upCharList; // 0x40
	private ActFavorUpGroupViewAdapter m_newUpGroupAdapter; // 0x48
	private ActFavorUpGroupViewAdapter m_upGroupAdapter; // 0x50
	private Boolean m_inited; // 0x58
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__CompareFavorUpChar; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30a5834 VA: 0x75956bd834
	public Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x30a590c VA: 0x75956bd90c
	public Void Render(List`1 favorList, String actId) { }
	// RVA: 0x30a5e60 VA: 0x75956bde60
	private Void _InitIfNot() { }
	// RVA: 0x30a5f84 VA: 0x75956bdf84
	private Int32 _CompareFavorUpChar(ActFavorUpCharData lhs, ActFavorUpCharData rhs) { }
	// RVA: 0x30a602c VA: 0x75956be02c
	public Void .ctor() { }
}
```