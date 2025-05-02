# Act5D1RuneObj

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Text _point`

- `GameObject _hasPoint`

- `GameObject _noPoint`

- `Image _runeImg`

- `GameObject _lockedObj`

- `GameObject _bannedObj`

- `GameObject _selectedObj`

- `GameObject _backImg`

- `CanvasGroup _alphaHandler`

- `UIStringEvent onClickEvent`

- `RuneInfo m_cacheInfoObj`

- `Tween m_showTween`


## Methods

- `Void SetRune(RuneInfo)`

- `Void SetRuneOnlyForShow(RuneInfo)`

- `Void _ShowTransitionFirst()`

- `Void _ShowTransitionSecond(Single)`

- `Void _ResetTween()`

- `Boolean _RenderOnlyForShow(RuneInfo)`

- `Void OnDestroy()`

- `Void OnClick()`

- `Void <_ShowTransitionFirst>b__15_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneObj : MonoBehaviour, IHotfixable
{
	private const Single FADE_DUR; // 0x0
	private Text _point; // 0x18
	private GameObject _hasPoint; // 0x20
	private GameObject _noPoint; // 0x28
	private Image _runeImg; // 0x30
	private GameObject _lockedObj; // 0x38
	private GameObject _bannedObj; // 0x40
	private GameObject _selectedObj; // 0x48
	private GameObject _backImg; // 0x50
	private CanvasGroup _alphaHandler; // 0x58
	public UIStringEvent onClickEvent; // 0x60
	private RuneInfo m_cacheInfoObj; // 0x68
	private Tween m_showTween; // 0x70
	private static DelegateBridge __Hotfix0_SetRune; // 0x0
	private static DelegateBridge __Hotfix0_SetRuneOnlyForShow; // 0x8
	private static DelegateBridge __Hotfix0__ShowTransitionFirst; // 0x10
	private static DelegateBridge __Hotfix0__ShowTransitionSecond; // 0x18
	private static DelegateBridge __Hotfix0__ResetTween; // 0x20
	private static DelegateBridge __Hotfix0__RenderOnlyForShow; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge __Hotfix0_OnClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x31ca830 VA: 0x75957e2830
	public Void SetRune(RuneInfo infoObj) { }
	// RVA: 0x31ca9b0 VA: 0x75957e29b0
	public Void SetRuneOnlyForShow(RuneInfo infoObj) { }
	// RVA: 0x31cad04 VA: 0x75957e2d04
	private Void _ShowTransitionFirst() { }
	// RVA: 0x31cae54 VA: 0x75957e2e54
	private Void _ShowTransitionSecond(Single delay) { }
	// RVA: 0x31cafd8 VA: 0x75957e2fd8
	private Void _ResetTween() { }
	// RVA: 0x31caad0 VA: 0x75957e2ad0
	private Boolean _RenderOnlyForShow(RuneInfo infoObj) { }
	// RVA: 0x31cb078 VA: 0x75957e3078
	private Void OnDestroy() { }
	// RVA: 0x31cb0e0 VA: 0x75957e30e0
	public Void OnClick() { }
	// RVA: 0x31cb17c VA: 0x75957e317c
	public Void .ctor() { }
	// RVA: 0x31cb1ec VA: 0x75957e31ec
	private Void <_ShowTransitionFirst>b__15_0() { }
}
```