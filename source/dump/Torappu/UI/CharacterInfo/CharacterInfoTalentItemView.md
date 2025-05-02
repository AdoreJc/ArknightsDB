# CharacterInfoTalentItemView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _textContent`

- `Image _lockIcon`

- `GameObject _backImg`

- `GameObject _backLockedImg`

- `UIColorGraphic _alpha`


## Properties

- `String content`


## Methods

- `Void InitText(TalentUnlockType, UnlockCondition)`

- `String get_content()`

- `Void set_content(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoTalentItemView : MonoBehaviour
{
	private Text _textContent; // 0x18
	private Image _lockIcon; // 0x20
	private Sprite[] _unlockIcon; // 0x28
	private GameObject _backImg; // 0x30
	private GameObject _backLockedImg; // 0x38
	private UIColorGraphic _alpha; // 0x40
	private const Int32 NEW_ONE; // 0x0
	private const Int32 NEW_TWO; // 0x0
	private const Int32 UPDATE_ONE; // 0x0
	private const Int32 UPDATE_TWO; // 0x0
	private const Int32 LVL; // 0x0
	private const Single LOCKED_ALPHA; // 0x0

	public String content { get; set; }

	// RVA: 0x2d8d404 VA: 0x75953a5404
	public Void InitText(TalentUnlockType unlockType, UnlockCondition unlockCondition) { }
	// RVA: 0x2d8d554 VA: 0x75953a5554
	public String get_content() { }
	// RVA: 0x2d8d3e0 VA: 0x75953a53e0
	public Void set_content(String value) { }
	// RVA: 0x2d8d578 VA: 0x75953a5578
	public Void .ctor() { }
}
```