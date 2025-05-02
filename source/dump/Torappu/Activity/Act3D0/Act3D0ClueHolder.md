# Act3D0ClueHolder

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Image _focusSprite`

- `GameObject _focusObj`

- `GameObject _noObj`

- `Act3D0ClueSliderObj _slideObj`

- `Transform _container`

- `GameObject _leftPart`

- `GameObject _rightPart`

- `Animator _animator`

- `Text _countText`

- `Int32 selectId`


## Methods

- `Void Render(List`1)`

- `Void SetSelectId()`

- `Void RefreshImg()`

- `Void AddOne()`

- `Void MinusOne()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0ClueHolder : MonoBehaviour, IHotfixable
{
	private Image _focusSprite; // 0x18
	private GameObject _focusObj; // 0x20
	private GameObject _noObj; // 0x28
	private Act3D0ClueSliderObj _slideObj; // 0x30
	private Transform _container; // 0x38
	private GameObject _leftPart; // 0x40
	private GameObject _rightPart; // 0x48
	private Animator _animator; // 0x50
	private Text _countText; // 0x58
	public Int32 selectId; // 0x60
	private List`1 m_cacheInfo; // 0x68
	private List`1 m_slideObj; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectId; // 0x8
	private static DelegateBridge __Hotfix0_RefreshImg; // 0x10
	private static DelegateBridge __Hotfix0_AddOne; // 0x18
	private static DelegateBridge __Hotfix0_MinusOne; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x322de74 VA: 0x7595845e74
	public Void Render(List`1 clueInfo) { }
	// RVA: 0x323818c VA: 0x759585018c
	public Void SetSelectId() { }
	// RVA: 0x3238254 VA: 0x7595850254
	public Void RefreshImg() { }
	// RVA: 0x3238450 VA: 0x7595850450
	public Void AddOne() { }
	// RVA: 0x323856c VA: 0x759585056c
	public Void MinusOne() { }
	// RVA: 0x3238668 VA: 0x7595850668
	public Void .ctor() { }
}
```