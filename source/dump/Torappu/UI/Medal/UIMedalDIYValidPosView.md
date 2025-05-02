# UIMedalDIYValidPosView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Image _img`

- `CanvasGroup _alphaHandler`

- `DIYMedalModel m_model`

- `FadeSwitchTween m_fadeSwitch`

- `RectTransform m_rectTrans`


## Properties

- `RectTransform rectTrans`


## Methods

- `RectTransform get_rectTrans()`

- `Void Render(DIYMedalModel, Boolean)`

- `Void _SetActive(Boolean)`

- `SizeConfig _GetSizeConfig(MedalSize)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalDIYValidPosView : MonoBehaviour, IHotfixable
{
	private Image _img; // 0x18
	private CanvasGroup _alphaHandler; // 0x20
	private List`1 _sizeConfigs; // 0x28
	private DIYMedalModel m_model; // 0x30
	private FadeSwitchTween m_fadeSwitch; // 0x38
	private RectTransform m_rectTrans; // 0x40
	private static DelegateBridge __Hotfix0_get_rectTrans; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__SetActive; // 0x10
	private static DelegateBridge __Hotfix0__GetSizeConfig; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public RectTransform rectTrans { get; }

	// RVA: 0x278dbe4 VA: 0x7594da5be4
	public RectTransform get_rectTrans() { }
	// RVA: 0x278dce4 VA: 0x7594da5ce4
	public Void Render(DIYMedalModel model, Boolean hasValidPos) { }
	// RVA: 0x278ddfc VA: 0x7594da5dfc
	private Void _SetActive(Boolean hasValidPos) { }
	// RVA: 0x278dee8 VA: 0x7594da5ee8
	private SizeConfig _GetSizeConfig(MedalSize size) { }
	// RVA: 0x278e058 VA: 0x7594da6058
	public Void .ctor() { }
}
```