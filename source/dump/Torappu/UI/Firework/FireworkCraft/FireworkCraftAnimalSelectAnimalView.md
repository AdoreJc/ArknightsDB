# FireworkCraftAnimalSelectAnimalView

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `GameObject _pnlNormal`

- `GameObject _pnlEquiped`

- `GameObject _pnlLocked`

- `GameObject _pnlSelected`

- `GameObject _pnlNew`

- `Text _textUnlockDesc`

- `GameObject _pnlSelectedHighlight1`

- `GameObject _pnlSelectedHighlight2`

- `UIAnimationLocation _animEquipedMarkShow`

- `String m_cachedAnimalId`

- `UIStateFinder m_stateFinder`

- `UISwitchTween m_equipedMarkShowTween`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void Render(FireworkCraftAnimalViewModel, FireworkCraftAnimalSelectViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftAnimalSelectAnimalView : MonoBehaviour, IHotfixable
{
	private GameObject _pnlNormal; // 0x18
	private GameObject _pnlEquiped; // 0x20
	private GameObject _pnlLocked; // 0x28
	private GameObject _pnlSelected; // 0x30
	private GameObject _pnlNew; // 0x38
	private Text _textUnlockDesc; // 0x40
	private GameObject _pnlSelectedHighlight1; // 0x48
	private GameObject _pnlSelectedHighlight2; // 0x50
	private UIAnimationLocation _animEquipedMarkShow; // 0x58
	private String m_cachedAnimalId; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private UISwitchTween m_equipedMarkShowTween; // 0x80
	private Boolean m_inited; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29006e0 VA: 0x7594f186e0
	private Void _InitIfNot() { }
	// RVA: 0x29008d4 VA: 0x7594f188d4
	public Void Render(FireworkCraftAnimalViewModel animalViewModel, FireworkCraftAnimalSelectViewModel animalSelectViewModel) { }
	// RVA: 0x2900bf8 VA: 0x7594f18bf8
	public Void OnClick() { }
	// RVA: 0x2900d10 VA: 0x7594f18d10
	public Void .ctor() { }
}
```