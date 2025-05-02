# RL04NodeUpgradeConfig

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Sprite _imgTitle`

- `Sprite _imgThemeColor`

- `Sprite _imgMuralBg`

- `Sprite _iconCenterEye`

- `Sprite _bgBtnConfirmCommon`

- `Sprite _bgBtnConfirmPlus`

- `Sprite _btnTypeSelect`

- `Sprite _btnTypeUnselect`

- `Color _colorTheme`

- `Color _colorCaption1`

- `Color _colorCaption2`

- `Color _colorLineLock`


## Methods

- `Sprite GetImgTitle()`

- `Sprite GetBgThemeColor()`

- `Sprite GetBgMural()`

- `Sprite GetMuralByLevel(Int32)`

- `Sprite GetIconCenterEye()`

- `Sprite GetBgBtnConfirmCommon()`

- `Sprite GetBgBtnConfirmPlus()`

- `Sprite GetBtnTypeSelect()`

- `Sprite GetBtnTypeUnselect()`

- `Color GetColorTheme()`

- `Color GetColorCaption1()`

- `Color GetColorCaption2()`

- `Color GetColorLineLock()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04NodeUpgradeConfig : MonoBehaviour, IHotfixable
{
	private Sprite _imgTitle; // 0x18
	private Sprite _imgThemeColor; // 0x20
	private Sprite _imgMuralBg; // 0x28
	private Sprite[] _imgMuralList; // 0x30
	private Sprite _iconCenterEye; // 0x38
	private Sprite _bgBtnConfirmCommon; // 0x40
	private Sprite _bgBtnConfirmPlus; // 0x48
	private Sprite _btnTypeSelect; // 0x50
	private Sprite _btnTypeUnselect; // 0x58
	private Color _colorTheme; // 0x60
	private Color _colorCaption1; // 0x70
	private Color _colorCaption2; // 0x80
	private Color _colorLineLock; // 0x90
	private static DelegateBridge __Hotfix0_GetImgTitle; // 0x0
	private static DelegateBridge __Hotfix0_GetBgThemeColor; // 0x8
	private static DelegateBridge __Hotfix0_GetBgMural; // 0x10
	private static DelegateBridge __Hotfix0_GetMuralByLevel; // 0x18
	private static DelegateBridge __Hotfix0_GetIconCenterEye; // 0x20
	private static DelegateBridge __Hotfix0_GetBgBtnConfirmCommon; // 0x28
	private static DelegateBridge __Hotfix0_GetBgBtnConfirmPlus; // 0x30
	private static DelegateBridge __Hotfix0_GetBtnTypeSelect; // 0x38
	private static DelegateBridge __Hotfix0_GetBtnTypeUnselect; // 0x40
	private static DelegateBridge __Hotfix0_GetColorTheme; // 0x48
	private static DelegateBridge __Hotfix0_GetColorCaption1; // 0x50
	private static DelegateBridge __Hotfix0_GetColorCaption2; // 0x58
	private static DelegateBridge __Hotfix0_GetColorLineLock; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2b2f948 VA: 0x7595147948
	public Sprite GetImgTitle() { }
	// RVA: 0x2b2f9b0 VA: 0x75951479b0
	public Sprite GetBgThemeColor() { }
	// RVA: 0x2b2fa18 VA: 0x7595147a18
	public Sprite GetBgMural() { }
	// RVA: 0x2b2fa80 VA: 0x7595147a80
	public Sprite GetMuralByLevel(Int32 level) { }
	// RVA: 0x2b2fb1c VA: 0x7595147b1c
	public Sprite GetIconCenterEye() { }
	// RVA: 0x2b2fb84 VA: 0x7595147b84
	public Sprite GetBgBtnConfirmCommon() { }
	// RVA: 0x2b2fbec VA: 0x7595147bec
	public Sprite GetBgBtnConfirmPlus() { }
	// RVA: 0x2b2fc54 VA: 0x7595147c54
	public Sprite GetBtnTypeSelect() { }
	// RVA: 0x2b2fcbc VA: 0x7595147cbc
	public Sprite GetBtnTypeUnselect() { }
	// RVA: 0x2b2fd24 VA: 0x7595147d24
	public Color GetColorTheme() { }
	// RVA: 0x2b2fd8c VA: 0x7595147d8c
	public Color GetColorCaption1() { }
	// RVA: 0x2b2fdf4 VA: 0x7595147df4
	public Color GetColorCaption2() { }
	// RVA: 0x2b2fe5c VA: 0x7595147e5c
	public Color GetColorLineLock() { }
	// RVA: 0x2b2fec4 VA: 0x7595147ec4
	public Void .ctor() { }
}
```