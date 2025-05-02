# Activity4D0StoryItem

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `Text _title`

- `Text _titleB`

- `GameObject _normalRoot`

- `GameObject _newHintRoot`

- `GameObject _lockRoot`

- `Text _unlockCondition`

- `Button _readStoryButton`

- `GameObject _lockDisableRoot`

- `Act4D0StoryItemViewModel m_data`


## Methods

- `Void OnItemClick()`

- `Void Refresh(Act4D0StoryItemViewModel, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Activity4D0StoryItem : MonoBehaviour, IHotfixable
{
	private Text _title; // 0x18
	private Text _titleB; // 0x20
	private GameObject _normalRoot; // 0x28
	private GameObject _newHintRoot; // 0x30
	private GameObject _lockRoot; // 0x38
	private Text _unlockCondition; // 0x40
	private Button _readStoryButton; // 0x48
	private GameObject _lockDisableRoot; // 0x50
	private Act4D0StoryItemViewModel m_data; // 0x58
	private Action`1 m_callback; // 0x60
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x0
	private static DelegateBridge __Hotfix0_Refresh; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31e0344 VA: 0x75957f8344
	public Void OnItemClick() { }
	// RVA: 0x31dfdd4 VA: 0x75957f7dd4
	public Void Refresh(Act4D0StoryItemViewModel data, Action`1 callback) { }
	// RVA: 0x31e0438 VA: 0x75957f8438
	public Void .ctor() { }
}
```