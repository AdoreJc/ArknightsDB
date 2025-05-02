# SettingPanel

**Namespace:** `Torappu.UI.Setting`


## Fields

- `GameObject _btnAccountCenter`

- `Boolean m_isInited`

- `Action m_openAccountCenter`


## Methods

- `Void Init(InjectSettingFeedbacks, Action`1)`

- `Void SelectCategory(SettingCategory)`

- `Void EventOnAccountCenterClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Setting
public class SettingPanel : MonoBehaviour, IHotfixable
{
	private Item[] _items; // 0x18
	private GameObject _btnAccountCenter; // 0x20
	private Boolean m_isInited; // 0x28
	private List`1 m_activeItems; // 0x30
	private Action`1 m_onCategoryClicked; // 0x38
	private Action m_openAccountCenter; // 0x40
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_SelectCategory; // 0x8
	private static DelegateBridge __Hotfix0_EventOnAccountCenterClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2478088 VA: 0x7594a90088
	public Void Init(InjectSettingFeedbacks sdkConfigs, Action`1 onCategoryClicked) { }
	// RVA: 0x2477ebc VA: 0x7594a8febc
	public Void SelectCategory(SettingCategory target) { }
	// RVA: 0x247a8bc VA: 0x7594a928bc
	public Void EventOnAccountCenterClicked() { }
	// RVA: 0x247a94c VA: 0x7594a9294c
	public Void .ctor() { }
}
```