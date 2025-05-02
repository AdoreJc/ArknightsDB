# CommonFriendAssistProfessionTabView

**Namespace:** `Torappu.UI.CommonFriendAssist`


## Fields

- `TwoStateToggle _selectStateToggle`

- `Image _selectedProfessionImg`

- `Image _unselectedProfessionImg`

- `Button _hotspot`

- `ICtrl m_ctrl`

- `ProfessionCategory m_professionCategory`


## Methods

- `Void Render(ProfTabModel, ICtrl)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CommonFriendAssist
public class CommonFriendAssistProfessionTabView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _selectStateToggle; // 0x18
	private Image _selectedProfessionImg; // 0x20
	private Image _unselectedProfessionImg; // 0x28
	private Button _hotspot; // 0x30
	private ICtrl m_ctrl; // 0x38
	private ProfessionCategory m_professionCategory; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c48a18 VA: 0x7595260a18
	public Void Render(ProfTabModel model, ICtrl ctrl) { }
	// RVA: 0x2c48b34 VA: 0x7595260b34
	public Void EventOnClick() { }
	// RVA: 0x2c48c1c VA: 0x7595260c1c
	public Void .ctor() { }
}
```