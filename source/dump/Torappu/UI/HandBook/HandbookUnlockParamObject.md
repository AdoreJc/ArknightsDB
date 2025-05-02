# HandbookUnlockParamObject

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Text _detailText`

- `Image _tinyIcon`

- `GameObject _availIcon`

- `GameObject _notAvailIcon`

- `Sprite _evolveZero`

- `Sprite _evolveOne`

- `Sprite _evolveTwo`

- `Sprite _favorIcon`

- `Sprite _itemIcon`

- `Sprite _defaultIcon`

- `Color BLUE_COLOR`


## Methods

- `Void Render(HandBookUnlockInfo, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandbookUnlockParamObject : MonoBehaviour, IHotfixable
{
	private Text _detailText; // 0x18
	private Image _tinyIcon; // 0x20
	private GameObject _availIcon; // 0x28
	private GameObject _notAvailIcon; // 0x30
	private Sprite _evolveZero; // 0x38
	private Sprite _evolveOne; // 0x40
	private Sprite _evolveTwo; // 0x48
	private Sprite _favorIcon; // 0x50
	private Sprite _itemIcon; // 0x58
	private Sprite _defaultIcon; // 0x60
	private Color BLUE_COLOR; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2eb6d34 VA: 0x75954ced34
	public Void Render(HandBookUnlockInfo param, Boolean isSingle) { }
	// RVA: 0x2eb71a4 VA: 0x75954cf1a4
	public Void .ctor() { }
}
```