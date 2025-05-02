# Act12d6GameEndTitleView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Single _logoTweenDuration`

- `Image _imageBkgFail`

- `Image _imageBkgEnding`

- `Image _imageTitle`

- `HorizontalLayoutGroup _logoLayoutGroup`

- `Boolean m_inited`

- `Tween m_tweener`


## Methods

- `Void Render(Act12D6GameEndViewModel)`

- `Sprite _GetTitleSprite(String)`

- `Sprite _GetLogoSprite(String)`

- `Vector2 _GetLogoSize(String)`

- `Void _TryPlayLogoTween()`

- `IEnumerator _PlayLogoTween()`

- `Void OnEnable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12d6GameEndTitleView : MonoBehaviour, IHotfixable
{
	private List`1 _endingDatas; // 0x18
	private Single _logoTweenDuration; // 0x20
	private Image _imageBkgFail; // 0x28
	private Image _imageBkgEnding; // 0x30
	private Image _imageTitle; // 0x38
	private HorizontalLayoutGroup _logoLayoutGroup; // 0x40
	private List`1 _logos; // 0x48
	private Boolean m_inited; // 0x50
	private Tween m_tweener; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GetTitleSprite; // 0x8
	private static DelegateBridge __Hotfix0__GetLogoSprite; // 0x10
	private static DelegateBridge __Hotfix0__GetLogoSize; // 0x18
	private static DelegateBridge __Hotfix0__TryPlayLogoTween; // 0x20
	private static DelegateBridge __Hotfix0__PlayLogoTween; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x34753f0 VA: 0x7595a8d3f0
	public Void Render(Act12D6GameEndViewModel viewModel) { }
	// RVA: 0x347563c VA: 0x7595a8d63c
	private Sprite _GetTitleSprite(String id) { }
	// RVA: 0x3475784 VA: 0x7595a8d784
	private Sprite _GetLogoSprite(String id) { }
	// RVA: 0x34758cc VA: 0x7595a8d8cc
	private Vector2 _GetLogoSize(String id) { }
	// RVA: 0x3475a40 VA: 0x7595a8da40
	private Void _TryPlayLogoTween() { }
	// RVA: 0x3475ad4 VA: 0x7595a8dad4
	private IEnumerator _PlayLogoTween() { }
	// RVA: 0x3475ba8 VA: 0x7595a8dba8
	public Void OnEnable() { }
	// RVA: 0x3475c10 VA: 0x7595a8dc10
	public Void .ctor() { }
}
```