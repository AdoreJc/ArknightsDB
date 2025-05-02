# SandboxV2AdminFoodAttrPanel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _noFoodPart`

- `GameObject _hasFoodPart`

- `GameObject _remainTimePart`

- `GameObject _outOfTimePart`

- `Text _remainTime`

- `Text _foodName`

- `Image _foodPic`

- `Image _foodIcon`

- `Text _foodUsage`

- `GameObject _alreadyFight`

- `UIPageFinder m_pageFinder`


## Methods

- `Void RenderFoodState(SandboxV2CharFoodModel, Boolean)`

- `Void _RenderFoodInfo(SandboxV2CharFoodModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminFoodAttrPanel : MonoBehaviour, IHotfixable
{
	private GameObject _noFoodPart; // 0x18
	private GameObject _hasFoodPart; // 0x20
	private GameObject _remainTimePart; // 0x28
	private GameObject _outOfTimePart; // 0x30
	private Text _remainTime; // 0x38
	private Text _foodName; // 0x40
	private Image _foodPic; // 0x48
	private Image _foodIcon; // 0x50
	private Text _foodUsage; // 0x58
	private GameObject _alreadyFight; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private static DelegateBridge __Hotfix0_RenderFoodState; // 0x0
	private static DelegateBridge __Hotfix0__RenderFoodInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x248672c VA: 0x7594a9e72c
	public Void RenderFoodState(SandboxV2CharFoodModel foodModel, Boolean isAlreadyFight) { }
	// RVA: 0x2487374 VA: 0x7594a9f374
	private Void _RenderFoodInfo(SandboxV2CharFoodModel foodModel) { }
	// RVA: 0x2487624 VA: 0x7594a9f624
	public Void .ctor() { }
}
```