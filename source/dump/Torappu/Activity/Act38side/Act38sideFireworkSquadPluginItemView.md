# Act38sideFireworkSquadPluginItemView

**Namespace:** `Torappu.Activity.Act38side`


## Fields

- `Image _imgAnimIcon`

- `GameObject _panelSelected`

- `GameObject _panelLocked`

- `GameObject _panelUnlock`

- `String m_cachedAnimId`

- `UIPageFinder m_pageFinder`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Void EventOnItemClicked()`

- `Void Render(Act38sideFireworkSquadPluginItemViewModel, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act38side
public class Act38sideFireworkSquadPluginItemView : MonoBehaviour, IHotfixable
{
	private Config[] _configList; // 0x18
	private Image _imgAnimIcon; // 0x20
	private GameObject _panelSelected; // 0x28
	private GameObject _panelLocked; // 0x30
	private GameObject _panelUnlock; // 0x38
	private String m_cachedAnimId; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private Action`1 <onItemClicked>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClicked { get; set; }

	// RVA: 0x323e8fc VA: 0x75958568fc
	private Action`1 get_onItemClicked() { }
	// RVA: 0x323e964 VA: 0x7595856964
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x323e9e8 VA: 0x75958569e8
	public Void EventOnItemClicked() { }
	// RVA: 0x323ea98 VA: 0x7595856a98
	public Void Render(Act38sideFireworkSquadPluginItemViewModel viewModel, String selectAnimId) { }
	// RVA: 0x323ecb8 VA: 0x7595856cb8
	public Void .ctor() { }
}
```