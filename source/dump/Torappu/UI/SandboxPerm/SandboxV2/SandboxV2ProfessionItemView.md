# SandboxV2ProfessionItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


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
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ProfessionItemView : MonoBehaviour, IHotfixable
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

	// RVA: 0x260e0c4 VA: 0x7594c260c4
	private Action`1 get_onProfessionClick() { }
	// RVA: 0x260e12c VA: 0x7594c2612c
	public Void set_onProfessionClick(Action`1 value) { }
	// RVA: 0x260e1b0 VA: 0x7594c261b0
	public Void Render(ProfessionCategory profession, Boolean isSelect) { }
	// RVA: 0x260e2ac VA: 0x7594c262ac
	private Sprite _GetProfessionIcon(ProfessionCategory profession) { }
	// RVA: 0x260e3a4 VA: 0x7594c263a4
	public Void EventOnClick() { }
	// RVA: 0x260e44c VA: 0x7594c2644c
	public Void .ctor() { }
}
```