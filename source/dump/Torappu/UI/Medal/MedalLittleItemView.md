# MedalLittleItemView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `GameObject _hasFlag`

- `CanvasGroup _alphaObj`

- `Image _icon`

- `Image _backImage`

- `UIStringEvent toTargetEvent`

- `String m_cacheMedalId`


## Methods

- `Void Render(String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalLittleItemView : MonoBehaviour, IHotfixable
{
	private GameObject _hasFlag; // 0x18
	private CanvasGroup _alphaObj; // 0x20
	private Image _icon; // 0x28
	private Image _backImage; // 0x30
	public UIStringEvent toTargetEvent; // 0x38
	private String m_cacheMedalId; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x279d03c VA: 0x7594db503c
	public Void Render(String medalId) { }
	// RVA: 0x279d24c VA: 0x7594db524c
	public Void OnClick() { }
	// RVA: 0x279d2f0 VA: 0x7594db52f0
	public Void .ctor() { }
}
```