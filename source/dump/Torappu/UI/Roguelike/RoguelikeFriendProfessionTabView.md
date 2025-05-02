# RoguelikeFriendProfessionTabView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `TwoStateToggle _selectStateToggle`

- `Image _selectedProfessionImg`

- `Image _unselectedProfessionImg`

- `ProfessionCategory m_professionCategory`


## Methods

- `Void Render(Boolean, ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFriendProfessionTabView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _selectStateToggle; // 0x18
	private Image _selectedProfessionImg; // 0x20
	private Image _unselectedProfessionImg; // 0x28
	private ProfessionCategory m_professionCategory; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2a3c08c VA: 0x759505408c
	public Void Render(Boolean isActive, ProfessionCategory profession) { }
	// RVA: 0x2a3c410 VA: 0x7595054410
	public Void .ctor() { }
}
```