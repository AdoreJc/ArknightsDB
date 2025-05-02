# SquadFriendProfessionTabView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `TwoStateToggle _selectStateToggle`

- `Image _selectedProfessionImg`

- `Image _unselectedProfessionImg`

- `ProfessionCategory m_professionCategory`


## Methods

- `Void Render(Param)`

- `Void SetSelected(Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendProfessionTabView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _selectStateToggle; // 0x18
	private Image _selectedProfessionImg; // 0x20
	private Image _unselectedProfessionImg; // 0x28
	private Action`1 m_clickEvent; // 0x30
	private ProfessionCategory m_professionCategory; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_SetSelected; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23c928c VA: 0x75949e128c
	public Void Render(Param param) { }
	// RVA: 0x23c9380 VA: 0x75949e1380
	public Void SetSelected(Boolean isSelected) { }
	// RVA: 0x23c940c VA: 0x75949e140c
	public Void OnClick() { }
	// RVA: 0x23c9494 VA: 0x75949e1494
	public Void .ctor() { }
}
```