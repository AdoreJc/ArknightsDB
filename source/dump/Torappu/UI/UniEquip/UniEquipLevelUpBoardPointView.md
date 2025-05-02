# UniEquipLevelUpBoardPointView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `GameObject _tarObj`

- `GameObject _curObj`

- `UIAtlasImage _tarImg`

- `Single _fadeDuration`

- `Single _endAlpha`

- `Single _startAlpha`

- `Tween m_breatheTween`


## Methods

- `Void Render(UniEquipLevelUpBoardObjViewModel)`

- `Void _ResetTween()`

- `Single <_ResetTween>b__8_0()`

- `Void <_ResetTween>b__8_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipLevelUpBoardPointView : MonoBehaviour, IHotfixable
{
	private GameObject _tarObj; // 0x18
	private GameObject _curObj; // 0x20
	private UIAtlasImage _tarImg; // 0x28
	private Single _fadeDuration; // 0x30
	private Single _endAlpha; // 0x34
	private Single _startAlpha; // 0x38
	private Tween m_breatheTween; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__ResetTween; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22ff9f8 VA: 0x75949179f8
	public Void Render(UniEquipLevelUpBoardObjViewModel model) { }
	// RVA: 0x22ffac0 VA: 0x7594917ac0
	private Void _ResetTween() { }
	// RVA: 0x22ffc84 VA: 0x7594917c84
	public Void .ctor() { }
	// RVA: 0x22ffcf4 VA: 0x7594917cf4
	private Single <_ResetTween>b__8_0() { }
	// RVA: 0x22ffd20 VA: 0x7594917d20
	private Void <_ResetTween>b__8_1(Single val) { }
}
```