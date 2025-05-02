# ActMultiV3SquadCharItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `RectTransform _charCardRoot`

- `ActMultiV3CharCardView _charCardPrefab`

- `UIColorGraphic _colorGraphic`

- `ActMultiV3CharCardView m_charCardView`

- `ActMultiV3CharViewModel m_viewModel`

- `ActMultiV3IdentityType m_idType`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(ActMultiV3IdentityType, ActMultiV3CharViewModel)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadCharItemView : MonoBehaviour, IHotfixable
{
	private RectTransform _charCardRoot; // 0x18
	private ActMultiV3CharCardView _charCardPrefab; // 0x20
	private UIColorGraphic _colorGraphic; // 0x28
	private ActMultiV3CharCardView m_charCardView; // 0x30
	private ActMultiV3CharViewModel m_viewModel; // 0x38
	private ActMultiV3IdentityType m_idType; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31367d8 VA: 0x759574e7d8
	public Void Render(ActMultiV3IdentityType idType, ActMultiV3CharViewModel charModel) { }
	// RVA: 0x3136aa8 VA: 0x759574eaa8
	public Void EventOnItemClick() { }
	// RVA: 0x3136c14 VA: 0x759574ec14
	public Void .ctor() { }
}
```