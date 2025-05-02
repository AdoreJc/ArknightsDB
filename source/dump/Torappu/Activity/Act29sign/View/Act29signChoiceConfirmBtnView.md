# Act29signChoiceConfirmBtnView

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `Text _text`

- `String m_btnOption`


## Methods

- `Void set_onClick(Action`1)`

- `Void Render(String, String)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signChoiceConfirmBtnView : MonoBehaviour, IHotfixable
{
	private Text _text; // 0x18
	private String m_btnOption; // 0x20
	private Action`1 <onClick>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onClick { get; set; }

	// RVA: 0x3259df8 VA: 0x7595871df8
	private Action`1 get_onClick() { }
	// RVA: 0x3259e60 VA: 0x7595871e60
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x3259ee4 VA: 0x7595871ee4
	public Void Render(String text, String btnOption) { }
	// RVA: 0x3259f90 VA: 0x7595871f90
	public Void EventOnClick() { }
	// RVA: 0x325a030 VA: 0x7595872030
	public Void .ctor() { }
}
```