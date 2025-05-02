# UIBattleSandboxConstructTopBar

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Image _icon`

- `Sprite _baseIcon`

- `Sprite _portIcon`

- `Text _lvlText`

- `Text _nameText`

- `Text _uidText`

- `UIAnimationLocation _location`

- `UIAnimationLocation _locationOut`

- `Ease _ease`

- `Tween m_tween`


## Methods

- `Void Init(Option)`

- `Void MoveWithAnim(Boolean)`

- `Void <MoveWithAnim>b__12_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxConstructTopBar : MonoBehaviour, IHotfixable
{
	public Image _icon; // 0x18
	public Sprite _baseIcon; // 0x20
	public Sprite _portIcon; // 0x28
	public Text _lvlText; // 0x30
	public Text _nameText; // 0x38
	public Text _uidText; // 0x40
	public UIAnimationLocation _location; // 0x48
	public UIAnimationLocation _locationOut; // 0x58
	public Ease _ease; // 0x68
	private Tween m_tween; // 0x70
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_MoveWithAnim; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2094ec4 VA: 0x75946acec4
	public Void Init(Option option) { }
	// RVA: 0x20970e0 VA: 0x75946af0e0
	public Void MoveWithAnim(Boolean isLeft) { }
	// RVA: 0x209a7d8 VA: 0x75946b27d8
	public Void .ctor() { }
	// RVA: 0x209a850 VA: 0x75946b2850
	private Void <MoveWithAnim>b__12_0() { }
}
```