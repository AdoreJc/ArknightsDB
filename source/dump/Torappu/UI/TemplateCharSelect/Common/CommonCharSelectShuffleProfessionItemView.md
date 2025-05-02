# CommonCharSelectShuffleProfessionItemView

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `Image _imgProfession`

- `Color _colorUnselect`

- `Color _colorSelect`

- `ProfessionCategory m_profession`


## Methods

- `Void set_onProfessionClick(Action`1)`

- `Void Render(ProfessionCategory, Boolean)`

- `Sprite _GetProfessionIcon(ProfessionCategory)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectShuffleProfessionItemView : MonoBehaviour, IHotfixable
{
	private Image _imgProfession; // 0x18
	private Color _colorUnselect; // 0x20
	private Color _colorSelect; // 0x30
	private ProfessionIcon[] _professionIconList; // 0x40
	private ProfessionCategory m_profession; // 0x48
	private Action`1 <onProfessionClick>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onProfessionClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onProfessionClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__GetProfessionIcon; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onProfessionClick { get; set; }

	// RVA: 0x2c5adc4 VA: 0x7595272dc4
	private Action`1 get_onProfessionClick() { }
	// RVA: 0x2c5ae2c VA: 0x7595272e2c
	public Void set_onProfessionClick(Action`1 value) { }
	// RVA: 0x2c5aeb0 VA: 0x7595272eb0
	public Void Render(ProfessionCategory profession, Boolean isSelect) { }
	// RVA: 0x2c5afac VA: 0x7595272fac
	private Sprite _GetProfessionIcon(ProfessionCategory profession) { }
	// RVA: 0x2c5b0a4 VA: 0x75952730a4
	public Void EventOnClick() { }
	// RVA: 0x2c5b14c VA: 0x759527314c
	public Void .ctor() { }
}
```