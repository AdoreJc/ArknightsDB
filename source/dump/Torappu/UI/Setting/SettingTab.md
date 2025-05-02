# SettingTab

**Namespace:** `Torappu.UI.Setting`


## Fields

- `Button _button`

- `Animator _animator`

- `Text _text`

- `Int32 m_id`


## Methods

- `Void SetString(String, Single, Int32)`

- `Void SetCommonObjectEnabled(Boolean)`

- `Void _OnClick()`

- `Void ChangeType(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Setting
public class SettingTab : MonoBehaviour, IHotfixable
{
	private Button _button; // 0x18
	private Animator _animator; // 0x20
	private Text _text; // 0x28
	private Int32 m_id; // 0x30
	public Action`1 OnChangeTab; // 0x38
	private static DelegateBridge __Hotfix0_SetString; // 0x0
	private static DelegateBridge __Hotfix0_SetCommonObjectEnabled; // 0x8
	private static DelegateBridge __Hotfix0__OnClick; // 0x10
	private static DelegateBridge __Hotfix0_ChangeType; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x247b15c VA: 0x7594a9315c
	public Void SetString(String text, Single offset, Int32 id) { }
	// RVA: 0x247b2ec VA: 0x7594a932ec
	public Void SetCommonObjectEnabled(Boolean enabled) { }
	// RVA: 0x247b3a4 VA: 0x7594a933a4
	private Void _OnClick() { }
	// RVA: 0x247b42c VA: 0x7594a9342c
	public Void ChangeType(Boolean state) { }
	// RVA: 0x247b4d0 VA: 0x7594a934d0
	public Void .ctor() { }
}
```