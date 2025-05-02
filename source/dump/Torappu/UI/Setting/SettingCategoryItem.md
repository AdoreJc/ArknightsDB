# SettingCategoryItem

**Namespace:** `Torappu.UI.Setting`


## Fields

- `TwoStateToggle _toggle`

- `Button _button`

- `Boolean m_isSelected`

- `SettingCategory m_category`


## Methods

- `Void Init(SettingCategory, Action`1)`

- `Void ApplyState(Boolean)`

- `Void Start()`

- `Void _OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Setting
public class SettingCategoryItem : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _toggle; // 0x18
	private Button _button; // 0x20
	private Action`1 m_onClicked; // 0x28
	private Boolean m_isSelected; // 0x30
	private SettingCategory m_category; // 0x34
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_ApplyState; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0__OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x247a35c VA: 0x7594a9235c
	public Void Init(SettingCategory category, Action`1 onClicked) { }
	// RVA: 0x247a3ec VA: 0x7594a923ec
	public Void ApplyState(Boolean isSelected) { }
	// RVA: 0x247a494 VA: 0x7594a92494
	private Void Start() { }
	// RVA: 0x247a560 VA: 0x7594a92560
	private Void _OnClick() { }
	// RVA: 0x247a5e8 VA: 0x7594a925e8
	public Void .ctor() { }
}
```