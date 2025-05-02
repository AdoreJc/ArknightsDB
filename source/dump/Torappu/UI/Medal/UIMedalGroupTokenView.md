# UIMedalGroupTokenView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Image _icon`

- `Image _bkg`

- `RectTransform m_rectTrans`

- `String m_medalId`


## Properties

- `RectTransform rectTrans`


## Methods

- `RectTransform get_rectTrans()`

- `Void UpdateStatus(MedalConfig, UIPage)`

- `Void PopulateGraphics(List`1)`

- `Void _Render(MedalConfig, UIPage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalGroupTokenView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private Image _bkg; // 0x20
	private List`1 _sizeConfig; // 0x28
	private RectTransform m_rectTrans; // 0x30
	private String m_medalId; // 0x38
	private static DelegateBridge __Hotfix0_get_rectTrans; // 0x0
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x8
	private static DelegateBridge __Hotfix0_PopulateGraphics; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public RectTransform rectTrans { get; }

	// RVA: 0x278e7d8 VA: 0x7594da67d8
	public RectTransform get_rectTrans() { }
	// RVA: 0x278e8d8 VA: 0x7594da68d8
	public Void UpdateStatus(MedalConfig config, UIPage page) { }
	// RVA: 0x278ec98 VA: 0x7594da6c98
	public Void PopulateGraphics(List`1 list) { }
	// RVA: 0x278ea04 VA: 0x7594da6a04
	private Void _Render(MedalConfig config, UIPage page) { }
	// RVA: 0x278ee18 VA: 0x7594da6e18
	public Void .ctor() { }
}
```